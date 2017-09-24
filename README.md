# CSS Variables and JS

<p>Day 3 of Wes Bos's challenge to build 30 things in 30 days using vallina JavaScript.</p>
<p>I created a webpage that allows users to adjust an image's CSS directly from the browser.</p>

<h2>Lessons Learned</h2>

<h3>CSS</h3>
<p>New CSS features allow programmers to create variables with values in a stylesheet, and then assign those variabes to multiple properties. The features works much like variables used in SCSS.</p>

<h3>JS</h3>
<ol>
<li>All input elements are selected and stored in a variable.</li>
<li>Each input element is looped over so that event listeners can be added.</li>
<li>Event listeners call on a function that gets root element, which is then styled according to each input's name and (user-adjusted) value.</li>
</ol>
<p>Note: Because the values for the blur and padding properties require the 'px' suffix, a variable is created to store the input's suffix. The suffix only exists for these properties, in the input element's 'data-sizing' attribute.<p>
