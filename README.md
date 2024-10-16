<h1>Aim</h1>
<p>To study and implement C++ stack implementation using array.</p>
<hr>
<h1>Software Used</h1>
<p>VS code</p>
<hr>
<h1>Theory</h1>
<p>A stack in C++ can be implemented using an array by following the Last In, First Out (LIFO) principle. The array serves as the container for stack elements, and operations like <code>push</code> (adding an element) and <code>pop</code> (removing the top element) are performed. The stack requires tracking the top of the stack with an index variable (<code>top</code>). When pushing, the element is placed at the <code>top</code> position, and when popping, the element is removed from the <code>top</code> . The stack can also check for underflow (if the stack is empty) and overflow (if the stack is full).</p>
<hr>
<h1>Algorithms</h1>
<h2>Stack Using STL</h2>
<ol>
        <li><b>Start</b></li>
        <li>Initialize an empty stack of integers <code>st</code>.</li>
        <li>Push the value <code>30</code> onto the stack.</li>
        <li>Push the value <code>20</code> onto the stack.</li>
        <li>Push the value <code>10</code> onto the stack.</li>
        <li>Print the top element of the stack, which is <code>10</code>.</li>
        <li><b>End</b></li>
</ol>
<hr>
<h2>Stack in Array</h2>
<ol>
        <li><b>Start</b></li>
        <li>Define the <b>Stack</b> class with attributes <code>capacity</code>, <code>top</code>, and a dynamic array <code>arr</code>.</li>
        <li>Initialize the stack with the given capacity and set <code>top</code> to -1 (empty stack).</li>
        <li>Define the following methods:
            <ul>
                <li><b>push()</b>: Add an element to the stack if it's not full; otherwise, output "Stack Overflow".</li>
                <li><b>pop()</b>: Remove the top element if the stack is not empty; otherwise, output "Stack Underflow".</li>
                <li><b>peek()</b>: Return the top element of the stack; return -1 if the stack is empty.</li>
            </ul>
        </li>
        <li>In the main function, create a stack <code>st</code> with a capacity of 5.</li>
        <li>Push the elements 23, 24, and 25 onto the stack.</li>
        <li>Print the top element using <b>peek()</b> (Output: 25).</li>
        <li>Remove the top element using <b>pop()</b>.</li>
        <li>Print the new top element (Output: 24).</li>
        <li><b>End</b></li>
  </ol>
<hr>
<h1>Conclusion</h1>
<p>In conclusion, C++ codes to implement stack in an array and using STL was successfully written and executed.</p>
