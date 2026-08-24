---
layout: post 
title: CSA MCQ Lessons
search_exclude: true
permalink: /csa/mcq
type: lesson
---

{% include hh-theme.html %}

<div class="hh-wrap">

<a href="https://pages.opencodingsociety.com/csa/mcq" target="_blank" class="hh-pill" style="margin-bottom: 1.25rem;">
    <img src="{{ '/favicon.ico' | relative_url }}" alt="OCS logo" style="width: 16px; height: 16px;">
    Official OCS AP CSA MCQ Lessons
</a>

<div class="hh-panel" style="max-width:720px; margin-bottom: 2rem;">
  <div style="display:flex; justify-content:space-between; align-items:baseline; margin-bottom:1rem;">
    <strong style="font-size:1.05rem;">Units 1&ndash;4 Progress</strong>
    <span style="color:var(--hh-muted); font-size:0.9rem;">25 / 32 assigned lessons done</span>
  </div>

  <div class="hh-bar-row">
    <span>Unit 1</span>
    <div class="hh-bar-track"><div class="hh-bar-fill" style="width:100%;"></div></div>
    <span style="text-align:right; color:var(--hh-muted);">15/15</span>
  </div>

  <div class="hh-bar-row">
    <span>Unit 2</span>
    <div class="hh-bar-track"><div class="hh-bar-fill" style="width:100%;"></div></div>
    <span style="text-align:right; color:var(--hh-muted);">7/7</span>
  </div>

  <div class="hh-bar-row">
    <span>Unit 3</span>
    <div class="hh-bar-track"><div class="hh-bar-fill" style="width:100%;"></div></div>
    <span style="text-align:right; color:var(--hh-muted);">3/3</span>
  </div>

  <div class="hh-bar-row" style="margin-bottom:0;">
    <span>Unit 4</span>
    <div class="hh-bar-track"><div class="hh-bar-fill hh-empty" style="width:0%;"></div></div>
    <span style="text-align:right; color:var(--hh-muted);">0/7</span>
  </div>

  <div class="hh-footnote">
    Counts reflect lessons that were assigned/written for each unit (stubs with no assignment are excluded). Full tracker (per-lesson status, screenshots): <a href="https://github.com/HarrishAhilan/portfolio/issues/1">Issue #1</a>.
  </div>
</div>

<h3 class="hh-heading" id="lesson-navigator">Lesson Navigator</h3>
<p class="hh-desc">Every lesson I've worked through, organized by unit. Each card links straight to my actual work for that lesson.</p>

<a id="unit-1"></a>
<details class="hh-unit" open>
  <summary>
    <span>Unit 1: Primitive Types &amp; Objects</span>
    <span class="hh-unit-status hh-status-done">15 / 15 done</span>
  </summary>
  <div class="hh-lesson-list">

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/1_1" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>1.1 &middot; Algorithms<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> an unambiguous, ordered set of steps for solving a problem, usually sketched as pseudocode before any real code gets written.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/1_2" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>1.2 &middot; Variables<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> named storage for a value of a specific type, declared as <code>type name = value;</code>. <code>final</code> turns it into a constant.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/1_3" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>1.3 &middot; Output<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> expressions evaluate to a value, and <code>System.out.print</code> / <code>println</code> push that value to the console.</p></div>
      </a>
      <a href="{{site.baseurl}}/csa/unit_01/1_3/homework" class="hh-pill hh-hw-pill">Homework</a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/1_4" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>1.4 &middot; Input<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> <code>Scanner</code> reads typed input from <code>System.in</code> using methods like <code>nextInt()</code> and <code>nextLine()</code>.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/1_5" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>1.5 &middot; Casting<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> converting a value from one type to another. Widening happens automatically; narrowing needs an explicit cast and can truncate.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/1_6" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>1.6 &middot; Compound Operators<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> shorthand like <code>+=</code>, <code>-=</code>, <code>*=</code> that combine an operation and an assignment into one statement.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/1_7" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>1.7 &middot; APIs<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> a library is a collection of prewritten classes; an API is the documentation describing what those classes do.</p></div>
      </a>
      <a href="{{site.baseurl}}/csa/unit_01/1_7/homework" class="hh-pill hh-hw-pill">Homework</a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/1_8" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>1.8 &middot; Documentation<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> Javadoc comments (<code>/** ... */</code>) describe a method's precondition and postcondition, plus tags like <code>@param</code> and <code>@return</code>.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/1_9" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>1.9 &middot; Method Signatures<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> a method's name plus the number, order, and types of its parameters. Overloading lets methods share a name if signatures differ.</p></div>
      </a>
      <a href="{{site.baseurl}}/csa/unit_01/1_9_hw" class="hh-pill hh-hw-pill">Homework</a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/1_10" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>1.10 &middot; Class Methods<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> a static method belongs to the class itself rather than to any object, called through the class name.</p></div>
      </a>
      <a href="{{site.baseurl}}/csa/unit_01/1_10/homework" class="hh-pill hh-hw-pill">Homework</a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/1_11" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>1.11 &middot; Math Class<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> a built-in class of static utility methods (<code>Math.pow</code>, <code>Math.sqrt</code>, <code>Math.random</code>) so common math operations don't need to be hand-written.</p></div>
      </a>
      <a href="{{site.baseurl}}/csa/unit_01/1_11_hw" class="hh-pill hh-hw-pill">Homework</a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/1_12" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>1.12 &middot; Classes &amp; Objects<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> a class is the blueprint; an object is one specific instance built from it with <code>new</code>. A reference variable points to where the object lives.</p></div>
      </a>
      <a href="{{site.baseurl}}/csa/unit_01/1_12/homework" class="hh-pill hh-hw-pill">Homework</a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/1_13" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>1.13 &middot; Object Creation (Stack vs Heap)<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> <code>new</code> allocates an object on the heap; local primitives live on the stack. Passing an object passes its reference, not a copy. Teacher-flagged best evidence.</p></div>
      </a>
      <a href="{{site.baseurl}}/csa/unit_01/1_13/homework" class="hh-pill hh-hw-pill">Homework</a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/1_14" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>1.14 &middot; Instance Methods<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> a method that acts on a specific object's own data, invoked through that object (<code>obj.method()</code>).</p></div>
      </a>
      <a href="{{site.baseurl}}/csa/unit_01/1_14_homework" class="hh-pill hh-hw-pill">Homework</a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/1_15" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>1.15 &middot; String Manipulation<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> Strings are immutable, so methods like <code>substring()</code>, <code>indexOf()</code>, <code>charAt()</code> return new information rather than modifying the original.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_01/quiz" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-todo"></span>Unit 1 Quiz<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> a cumulative check across primitive types, variables, casting, and basic class/object usage. Not yet completed.</p></div>
      </a>
    </div>

  </div>
</details>

<a id="unit-2"></a>
<details class="hh-unit">
  <summary>
    <span>Unit 2: Selection &amp; Iteration</span>
    <span class="hh-unit-status hh-status-done">7 / 7 done</span>
  </summary>
  <div class="hh-lesson-list">

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_02/2_3" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>2.3 &middot; if Statements<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> runs a block of code only when a boolean condition evaluates true; <code>else</code> is the fallback path.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_02/2_4" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>2.4 &middot; Nested if Statements<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> <code>else if</code> chains test conditions in order and stop at the first match, sorting a value into a range.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_02/2_7" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>2.7 &middot; while Loops<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> repeats a block as long as a condition stays true, checked again before every pass.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_02/2_8" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>2.8 &middot; for Loops<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> bundles a counter's start, condition, and update into one line instead of managing all three separately.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_02/2_10" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>2.10 &middot; Implementing String Algorithms<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> combining loops with String methods to process text character by character. Teacher-flagged best evidence.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_02/2_11" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>2.11 &middot; Nested Iteration<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> a loop inside another loop, where the inner loop runs to completion for every pass of the outer loop.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_02/2_12" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>2.12 &middot; Informal Run-Time Analysis<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> counting how many times a piece of code actually executes, an early hands-on version of what Big-O later formalizes.</p></div>
      </a>
    </div>

  </div>
</details>

<a id="unit-3"></a>
<details class="hh-unit">
  <summary>
    <span>Unit 3: Classes</span>
    <span class="hh-unit-status hh-status-done">3 / 3 done</span>
  </summary>
  <div class="hh-lesson-list">

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_03/3_3" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>3.3 &middot; Anatomy of a Class<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> where a class gets defined, where an object is instantiated, and where a method actually gets called and data mutated.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_03/3_5" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>3.5 &middot; Methods: How to Write Them<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> a subclass can override an inherited method to replace its behavior. <code>@Override</code> catches spelling mistakes. Teacher-flagged best evidence.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_03/3_9" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-done"></span>3.9 &middot; this Keyword<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> a variable's static type is what it's declared as; its dynamic type is what it references at runtime, that's polymorphism.</p></div>
      </a>
    </div>

  </div>
</details>

<a id="unit-4"></a>
<details class="hh-unit">
  <summary>
    <span>Unit 4: Arrays &amp; ArrayList</span>
    <span class="hh-unit-status hh-status-todo">0 / 7 done</span>
  </summary>
  <div class="hh-lesson-list">

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_04/4_3" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-todo"></span>4.3 &middot; Array Creation and Access<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> declaring a fixed-size array with <code>type[] name = new type[size]</code>, then reading/writing a slot with <code>name[index]</code>.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_04/4_4" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-todo"></span>4.4 &middot; Array Traversals<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> looping over every index of an array to read, sum, search, or modify its elements.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_04/4_8" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-todo"></span>4.8 &middot; ArrayList Methods<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> <code>ArrayList</code> is a resizable, object-only list backed by <code>add()</code>, <code>get()</code>, <code>set()</code>, <code>remove()</code>, <code>size()</code>. Best evidence; may duplicate 4.9, confirm with teacher.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_04/4_9" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-todo"></span>4.9 &middot; ArrayList Traversals<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> looping over an <code>ArrayList</code> with <code>get(i)</code> and <code>size()</code>, or an enhanced for-each loop.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_04/4_11" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-todo"></span>4.11 &middot; 2D Array Creation and Access<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> an array of arrays, declared as <code>type[][] name = new type[rows][cols]</code>. May duplicate 4.12, confirm with teacher.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <a href="{{site.baseurl}}/csa/unit_04/4_12" class="hh-lesson-card">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-todo"></span>4.12 &middot; 2D Array Traversals<span class="hh-lesson-open">Open &rarr;</span></div>
        <div class="hh-lesson-desc"><p><strong>What it is:</strong> a nested loop, outer over rows and inner over columns, to visit every cell of a 2D array.</p></div>
      </a>
    </div>

    <div class="hh-lesson-row">
      <div class="hh-lesson-card" style="cursor: default;">
        <div class="hh-lesson-top"><span class="hh-lesson-dot hh-dot-todo"></span>Images Hack</div>
        <div class="hh-lesson-desc"><p>Assigned per Issue #1, not yet started, no notebook exists for this one yet.</p></div>
      </div>
    </div>

  </div>
</details>

</div>
