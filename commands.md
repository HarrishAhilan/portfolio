# Commands Cheat Sheet

Quick reference for running/managing this portfolio repo. Run these from inside the `portfolio` folder unless noted.

## Getting into the right setup (do this every new terminal window)

```bash
cd "/Users/harrishahilan/Desktop/Projectfolder/portfolio"
export PATH="/opt/homebrew/opt/ruby/bin:/opt/homebrew/lib/ruby/gems/4.0.0/bin:$PATH"
source venv/bin/activate
```

> The `export PATH` line is needed because your Mac's built-in Ruby is too old — this points to the newer Homebrew Ruby instead. Without it, `make` will fail.

## Running the site locally

```bash
make          # start the local server
make stop     # stop it
make clean    # stop + wipe generated files (use if you get weird duplicate pages)
```

Once running, open in your browser:
```
http://localhost:4500/portfolio/
```

## Checking your tools/kernels

```bash
ruby -v
bundle -v
python3 -V
java -version
node -v
npm -v
jupyter kernelspec list
```

## Git — saving and publishing your changes

```bash
git status                  # see what's changed
git add <file(s)>           # stage specific files (avoid `git add .` — stages everything blindly)
git commit -m "message"     # commit staged files
git push origin main        # send commits to GitHub
```

## GitHub login (only needed once, or if push stops working)

```bash
gh auth login
```
Choose: GitHub.com → HTTPS → Login with a web browser → follow the prompts.

## Checking if your GitHub Pages deploy worked

```bash
gh run list --repo HarrishAhilan/portfolio          # see recent Actions runs
gh workflow run "Deploy Jekyll with GitHub Pages dependencies preinstalled" --repo HarrishAhilan/portfolio --ref main   # manually trigger a deploy
```

Live site: https://harrishahilan.github.io/portfolio/

## Reproducing the nav-include bug (for SDLC "before" screenshot)

```bash
make stop
mv _includes/nav/csa_units /tmp/csa_units_backup
make          # this will crash — screenshot the error
```

To restore:
```bash
mv /tmp/csa_units_backup _includes/nav/csa_units
make          # builds clean again
```
