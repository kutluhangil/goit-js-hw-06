<h1>📘 JavaScript Homework 6 — Object Oriented Programming</h1>

<p>
This repository contains solutions for <strong>3 tasks</strong> focused on
<strong>Object-Oriented Programming (OOP)</strong> concepts in JavaScript.
The homework covers <code>this</code> context, classes, private properties,
class methods, and encapsulation.  
Each task is implemented in a separate file:
<code>task-1.js</code>, <code>task-2.js</code>, <code>task-3.js</code>.
</p>

<hr>

<h2>🚀 Overview</h2>

<p>
After completing Module 6, you are almost at the core of JavaScript 💪  
This homework reinforces your understanding of:
</p>

<ul>
  <li>The <code>this</code> keyword in different contexts</li>
  <li><code>this</code> in global scope, object methods, arrow functions, and callbacks</li>
  <li>The <code>call</code>, <code>apply</code>, and <code>bind</code> methods</li>
  <li>Object-Oriented Programming fundamentals</li>
  <li>Classes, instances, and public interfaces</li>
  <li>Prototypes and prototypal inheritance</li>
  <li>Creating objects of the same type with shared behavior and different data</li>
</ul>

<p>
The final step is to correctly use <code>this</code>, build classes for managing data,
and work with string constructors.
</p>

<hr>

<h2>🔹 Task 1: User Account (<code>task-1.js</code>)</h2>

<p>
Refactor an existing object to correctly use the <code>this</code> keyword.
The task simulates a real-world scenario where a developer left broken code
for managing user accounts in a food delivery service.
</p>

<p>
You must fix object methods so they properly access and update object properties
using <code>this</code>.
</p>

<pre><code>const customer = {
  username: "Mango",
  balance: 24000,
  discount: 0.1,
  orders: ["Burger", "Pizza", "Salad"],
};
</code></pre>

<p>✅ <strong>What was practiced:</strong></p>

<ul>
  <li>Correct usage of <code>this</code> inside object methods</li>
  <li>Updating object state via methods</li>
  <li>Working with arrays and numeric calculations inside an object</li>
</ul>

<p>✅ <strong>Expected behavior:</strong></p>

<ul>
  <li>Getting and updating balance and discount</li>
  <li>Adding new orders</li>
  <li>Returning updated orders list</li>
</ul>

<hr>

<h2>🔹 Task 2: Storage (<code>task-2.js</code>)</h2>

<p>
Create a <strong>Storage</strong> class to manage a warehouse inventory.
The class stores items in a <strong>private property</strong> and provides
a clean public interface for interaction.
</p>

<p>Defined methods:</p>

<ul>
  <li><code>getItems()</code> — returns the current list of items</li>
  <li><code>addItem(newItem)</code> — adds a new item to storage</li>
  <li><code>removeItem(itemToRemove)</code> — removes an item by name</li>
</ul>

<pre><code>const storage = new Storage(["Nanitoids", "Prolonger", "Antigravitator"]);
console.log(storage.getItems());
storage.addItem("Droid");
storage.removeItem("Prolonger");
</code></pre>

<p>✅ <strong>What was practiced:</strong></p>

<ul>
  <li>Creating classes with constructors</li>
  <li>Using private class fields</li>
  <li>Encapsulation and controlled access to data</li>
  <li>Modifying internal state through class methods</li>
</ul>

<hr>

<h2>🔹 Task 3: String Builder (<code>task-3.js</code>)</h2>

<p>
Create a <strong>StringBuilder</strong> class for flexible string manipulation.
The class stores a string in a private property and provides methods
to modify it from different sides.
</p>

<p>Defined methods:</p>

<ul>
  <li><code>getValue()</code> — returns the current string value</li>
  <li><code>padStart(str)</code> — adds a string to the beginning</li>
  <li><code>padEnd(str)</code> — adds a string to the end</li>
  <li><code>padBoth(str)</code> — adds a string to both beginning and end</li>
</ul>

<pre><code>const builder = new StringBuilder(".");
builder.padStart("^");
builder.padEnd("^");
builder.padBoth("=");
</code></pre>

<p>✅ <strong>What was practiced:</strong></p>

<ul>
  <li>Working with private class fields</li>
  <li>String manipulation inside class methods</li>
  <li>Designing a clear and minimal public API</li>
</ul>

<hr>

<h2>📌 Summary & Reflection</h2>

<p>
With this homework, you practiced core <strong>Object-Oriented Programming</strong>
concepts in JavaScript:
</p>

<ul>
  <li>Proper usage of <code>this</code></li>
  <li>Building reusable classes</li>
  <li>Encapsulation with private properties</li>
  <li>Clean and predictable class interfaces</li>
  <li>Real-world scenarios using objects and classes</li>
</ul>

<p>
These tasks strengthen your understanding of OOP and prepare you
for building scalable, maintainable JavaScript applications 🚀
</p>
