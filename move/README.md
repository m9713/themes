<h1>MOVE</h1>
<p>A retro/vaporwave inspired about page</p>

<p><a href="https://aurthms.tumblr.com/move/preview" target="_blank">static preview</a></p>

<h2>Customization</h2>
<h4>How to change picture</h4>
<p>Go to line <a href="https://github.com/m9713/themes/blob/2a4714d54dfbbcbfe3ad4215b6c8295012e43f5f/move/move.html#L376">#376</a> and replace the link picture
<pre>&lt;div class="aesthetic-windows-95-modal-content"&gt;
  &lt;img src="<b>//static.tumblr.com/nuyvmrm/LtJqcvas6/14446002_1128442050582648_7929411903479268760_n.jpg</b>"/&gt;
&lt;/div&gt;
</pre></p>
<h4>How to add a new link</h4>
<p>Go to line <a href="https://github.com/m9713/themes/blob/2a4714d54dfbbcbfe3ad4215b6c8295012e43f5f/move/move.html#L403">#403</a> and inside <code> &lt;div class="etcetera"&gt; </code> paste this code
<pre>&lt;div class="aesthetic-windows-95-button"&gt;
  &lt;button onclick="window.open('<b>LINK_URL</b>','_self'); return false;"&gt;<b>LINK NAME</b>&lt;/button&gt;
&lt;/div&gt;</pre></p>
<h4>How to customize colors</h4>
<p>Go to <a href="//torch2424.github.io/aesthetic-css/#colorsColors">aesthetic.css/#colors</a> and find the one you like then copy the class and add it to the div you want to change the color</p>
<p><b>Example:</b>
<pre>
<!--NAVIGATION-->
&lt;div class="aesthetic-windows-95-modal-content <b>aesthetic-light-purple-bg-color</b>"&gt;
  &lt;li&gt;Home&lt;/li&gt;
  &lt;li&gt;About&lt;/li&gt;
  &lt;li&gt;F.A.Q.&lt;/li&gt;
&lt;/div>
</pre></p>

<h2>Credits</h2>
<ul>
<li><a href="//torch2424.github.io/aesthetic-css/">AESTHETIC.css</a></li>
<li><a href="//draggabilly.desandro.com/">Draggabilly</a></li>
<li><a href="//github.com/necolas/normalize.css">normalize.css</a></li>
<li><a href="//codepen.io/louh/pen/oZJQvm">Windows 95-era scrollbars</a></li>
</ul>
