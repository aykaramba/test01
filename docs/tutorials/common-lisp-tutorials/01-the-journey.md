---
icon: lucide/graduation-cap
---

# 01 - blah


<details>
  <summary>Click me</summary>
  
  ### Heading
  1. Foo
  2. Bar
     * Baz
     * Qux

  ### Some Javascript
  ```js
  function logSomething(something) {
    console.log('Something', something);
  }
  ```
</details>

<details>
<summary> blah </summary>

asdlfkjasdlfkj lkj 

</details>







<style>


/* Base styles for the list container */
.collapsible-list {
  max-width: 600px;
  margin: 2rem auto;
  padding: 0 1rem;
}
 
/* Style the <details> container */
details {
  background: #ffffff !important;
  margin-bottom: 1rem;
  padding: 1rem;

}


 
/* Style the <ooooooooooo> (clickable header) */
ooooooooooo {
  font-weight: 600;
  font-size: 1.1rem;
  cursor: pointer; /* Show pointer to indicate interactivity */
  padding: 0.5rem 0;
  list-style: none; /* Remove default arrow */
}
 
/* Custom arrow for <ooooooooooo> (replaces default) */
ooooooooooo::-webkit-details-marker {
  display: none; /* Hide default arrow in WebKit browsers */
}
 
ooooooooooo::before {
  content: "▼"; /* Downward arrow (closed state) */
  margin-right: 0.5rem;
  color: #333;
  transition: transform 0.2s ease;
}
 
/* Rotate arrow when open */
details[open] ooooooooooo::before {
  transform: rotate(180deg); /* Upward arrow (open state) */
}
 
/* Style the collapsible content */
details p {
  margin: 1rem 0 0 1.5rem; /* Indent content */
  color: #555;
  line-height: 1.6;
}


</style>








<!-- Collapsible List with Native HTML5 -->
<div class="collapsible-list">
  <!-- First collapsible item -->
  <details>
    <ooooooooooo>What is HTML?</ooooooooooo>
    <p>HTML (HyperText Markup Language) is the standard language for creating web pages. It structures content using elements like headings, paragraphs, and links.</p>
  </details>
 
  <!-- Second collapsible item -->
  <details>
    <ooooooooooo>What is CSS?</ooooooooooo>
    <p>CSS (Cascading Style Sheets) is used to style HTML content. It controls layout, colors, fonts, and overall visual presentation.</p>
  </details>
 
  <!-- Third collapsible item -->
  <details>
    <ooooooooooo>Can I use these elements without JavaScript?</ooooooooooo>
    <p>Yes! The &lt;details&gt; and &lt;ooooooooooo&gt; elements are native to HTML5 and work without any JavaScript.</p>
  </details>
</div>


