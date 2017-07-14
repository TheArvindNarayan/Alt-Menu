# Alt-Menu
Alternative Menu For Everything. A  small and Fun compilation of Certain Elements I use

<section id="css_files_and_structure">
	<div class="page-header">
    	<h3>Themes and CSS Adjustments </h3>
    </div>
<h3>Accordion Themes </h3>
<h6> to add a theme just add a theme class to the main accordion class for example the turqoise theme </h6>

 

<pre class="prettyprint lang-html linenums"><ol class="linenums"><li class="L0"><span class="tag">&lt;ul</span><span class="pln"> </span><span class="atn">class</span><span class="pun">=</span><span class="atv">"mdn-accordion turqoise-accordion-theme"</span><span class="tag">&gt;</span></li><li class="L1"><span class="pln">    </span></li><li class="L2"><span class="tag">&lt;/ul&gt;</span></li></ol></pre>

<h3>Theme color styles available </h3>
<ol>
	<li><strong>Default light </strong></li>
	<li><strong>Default dark</strong></li>
	<li><strong>blue-accordion-theme</strong></li>
	<li><strong>indigo-accordion-theme</strong></li>
    <li><strong>orange-accordion-theme</strong></li>
	<li><strong>turqoise-accordion-theme</strong></li>
	<li><strong>red-accordion-theme</strong></li>
    <li><strong>pink-accordion-theme</strong></li>
	<li><strong>green-accordion-theme</strong></li>
    <li><strong>purple-accordion-theme</strong></li>        
</ol>


<h3>CSS Adjustments</h3>
	
<h6> All the main styling is done inside <strong>modern-accordion.css</strong> 
this css file - you can edit or modify form elements and styles in this file to suit 
your needs </h6>

<h3>Custom Ripple Color</h3>
<h6> To add a custom ripple color to the accordion panel (accordion-title) just add a data color attribute with the color  <code style="color:#E14D4E; margin:0 3px;">data-accordion-ripple-color="#000000"</code> </h6> 
<pre class="prettyprint lang-html linenums"><ol class="linenums"><li class="L0"><span class="tag">&lt;label</span><span class="pln"> </span><span class="atn">class</span><span class="pun">=</span><span class="atv">"accordion-title"</span><span class="pln"> </span><span class="atn">data-accordion-ripple-color</span><span class="pun">=</span><span class="atv">"#000000"</span><span class="tag">&gt;</span></li></ol></pre>

    
<h3>Main form background CSS</h3> 
<h6>You can change / remove the background color by changing the following styles</h6>

<pre class="prettyprint lang-css linenums"><ol class="linenums"><li class="L0"><span class="pun">.</span><span class="pln">custom</span><span class="pun">-</span><span class="pln">bg</span><span class="pun">{</span><span class="pln"> background</span><span class="pun">:</span><span class="com">#EAF0F2; }</span></li></ol></pre>

<h3>Accordion width variations </h3> 
<h6>You can change the accordion width dimensions by changing the following styles, modify or create your own styles - just change the max-width value</h6>
	
<pre class="prettyprint lang-css linenums"><ol class="linenums"><li class="L0"><span class="pun">.</span><span class="pln">mdn</span><span class="pun">-</span><span class="pln">accordion </span><span class="pun">{</span></li><li class="L1"><span class="pln">	width</span><span class="pun">:</span><span class="pln"> </span><span class="lit">90</span><span class="pun">%;</span></li><li class="L2"><span class="pln">	max</span><span class="pun">-</span><span class="pln">width</span><span class="pun">:</span><span class="pln"> </span><span class="lit">740px</span><span class="pun">;</span></li><li class="L3"><span class="pln">	margin</span><span class="pun">:</span><span class="pln"> </span><span class="lit">4em</span><span class="pln"> </span><span class="kwd">auto</span><span class="pun">;</span></li><li class="L4"><span class="pln">	font</span><span class="pun">-</span><span class="pln">family</span><span class="pun">:</span><span class="str">"Merriweather"</span><span class="pun">,</span><span class="pln"> </span><span class="typ">Arial</span><span class="pun">,</span><span class="pln"> </span><span class="typ">Helvetica</span><span class="pun">,</span><span class="pln"> sans</span><span class="pun">-</span><span class="pln">serif</span><span class="pun">;</span></li><li class="L5"><span class="pln">	</span><span class="pun">-</span><span class="pln">webkit</span><span class="pun">-</span><span class="pln">box</span><span class="pun">-</span><span class="pln">shadow</span><span class="pun">:</span><span class="pln"> </span><span class="lit">0</span><span class="pln"> </span><span class="lit">1px</span><span class="pln"> </span><span class="lit">4px</span><span class="pln"> rgba</span><span class="pun">(</span><span class="lit">0</span><span class="pun">,</span><span class="pln"> </span><span class="lit">0</span><span class="pun">,</span><span class="pln"> </span><span class="lit">0</span><span class="pun">,</span><span class="pln"> </span><span class="lit">0.2</span><span class="pun">);</span></li><li class="L6"><span class="pln">	</span><span class="pun">-</span><span class="pln">moz</span><span class="pun">-</span><span class="pln">box</span><span class="pun">-</span><span class="pln">shadow</span><span class="pun">:</span><span class="pln"> </span><span class="lit">0</span><span class="pln"> </span><span class="lit">1px</span><span class="pln"> </span><span class="lit">4px</span><span class="pln"> rgba</span><span class="pun">(</span><span class="lit">0</span><span class="pun">,</span><span class="pln"> </span><span class="lit">0</span><span class="pun">,</span><span class="pln"> </span><span class="lit">0</span><span class="pun">,</span><span class="pln"> </span><span class="lit">0.2</span><span class="pun">);</span></li><li class="L7"><span class="pln">	box</span><span class="pun">-</span><span class="pln">shadow</span><span class="pun">:</span><span class="pln"> </span><span class="lit">0</span><span class="pln"> </span><span class="lit">1px</span><span class="pln"> </span><span class="lit">4px</span><span class="pln"> rgba</span><span class="pun">(</span><span class="lit">0</span><span class="pun">,</span><span class="pln"> </span><span class="lit">0</span><span class="pun">,</span><span class="pln"> </span><span class="lit">0</span><span class="pun">,</span><span class="pln"> </span><span class="lit">0.2</span><span class="pun">);</span></li><li class="L8"><span class="pln">	font</span><span class="pun">-</span><span class="pln">weight</span><span class="pun">:</span><span class="lit">400</span><span class="pun">;</span></li><li class="L9"><span class="pln">	background</span><span class="pun">:</span><span class="com">#fff;</span></li><li class="L0"><span class="pun">}</span></li></ol></pre>


</section>
