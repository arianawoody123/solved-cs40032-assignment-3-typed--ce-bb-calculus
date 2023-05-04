Download Link: https://assignmentchef.com/product/solved-cs40032-assignment-3-typed-%ce%bb-calculus
<br>
<strong>Instructions</strong>: Please solve the questions using pen and paper and scan the images. Every image should contain your roll number and name.

<ol>

 <li>Derive the type of each lambda expression. Show all derivation steps.</li>

</ol>

<strong>[3 * 5 = 15]</strong>

<ul>

 <li>Given E<sub>0 </sub>∪ <em>y </em>: <em>bool </em>:</li>

</ul>

<em>y </em>:= <em>true</em>

<ul>

 <li>Given type constants <em>func</em>1 : <em>A </em>→ <em>B </em>and <em>func</em>2 : (<em>C </em>→ <em>B</em>) :</li>

</ul>

<em>λ</em>(<em>x </em>: <em>A</em>)<em>.</em>(<em>func</em>1 <em>x</em>);<em>λ</em>(<em>q </em>: <em>C</em>)<em>.</em>(<em>func</em>2 <em>q</em>)

<ul>

 <li>Given | be a constant of type <em>Bool </em>→ <em>Bool </em>→ <em>Bool </em>and type of <em>true </em>is <em>Bool λ</em>(<em>ω </em>: <em>Bool </em>→ <em>π</em>)<em>. λ</em>(<em>x </em>: <em>Bool</em>)<em>. </em>(<em>ω </em>(<em>x </em>| <em>true</em>))</li>

 <li>Given + is type constant with the type <em>S </em>→</li>

</ul>

<em>λ</em>(<em>f </em>: <em>S </em>→ <em>C</em>)<em>. λ</em>(<em>x </em>: <em>S</em>)<em>. f</em>(+<em>x</em>)

<ul>

 <li>Given E<sub>0 </sub>= {<em>x </em>: <em>Ref Bool, y </em>: <em>Bool</em>} and the constants <em>succ </em>: <em>Int </em>→ <em>Int, true </em>: <em>Bool, </em>4 : <em>Int </em>:</li>

</ul>

<em>succ </em>4; <em>x </em>:= <em>true</em>

<ol start="2">

 <li>Derive the type of each of the following expression. Any assumptions are welcome. <strong>[5 * 2 = 10]</strong>

  <ul>

   <li>Given the type of <em>φ </em>is <em>Float </em>→ <em>Integer</em></li>

  </ul></li>

</ol>

(<em>λ</em>(<em>p </em>: <em>Float </em>→ <em>Integer</em>)<em>. λ</em>(<em>f </em>: <em>Float </em>→ <em>Float</em>)<em>. λ</em>(<em>y </em>: <em>Float</em>)<em>. p </em>(<em>f </em>(<em>f y</em>))) <em>φ</em>

<ul>

 <li>Given <em>φ </em>be the constant with the type <em>Bool </em>→ <em>Bool </em>→ <em>Bool </em>and <em>true </em>with the type <em>Bool λ</em>(<em>func</em>1 : <em>Bool </em>→ <em>Char</em>)<em>. λ</em>(<em>τ </em>: <em>Bool</em>)<em>. func</em>1 (<em>τ φ true</em>)</li>

</ul>

1