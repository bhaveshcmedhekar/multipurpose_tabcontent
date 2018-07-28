<h2 >
New Features Added</h2>

  <ul>
                    <li>can be use for Multiple Tabs (Tabs inside tabs) </li>
                    <li>If there are multiple tabs, <strong>first tab list canbe converted into dropdown</strong> </li>
                </ul>
                
<h2 >
Features</h2>

<ul>  
            <li>Has option to show same structure in accordion </li>
            <li>Tabs transform to accordion based on breakpoint</li>
            <li>Has option for tab's different layout (tabs on top/left/right side)</li>
            <li>Uses javascript / jQuery for the technical tab switching (class based)</li>
            <li>Uses CSS for the desktop/tablet/mobile view</li>
            <li>Has callback events for the tab events</li>
            <li>Tabs can be switched using controllers (previous/ next)</li>
            <li>Specific tab can be kept opened on load</li>
            <li>Tab content can be added using "Ajax"</li>
            <li>Cross browser compatibility (IE7+, Chrome, Firefox, Safari and Opera)</li>
            <li>Multiple device support (Web, Tablet, Mobile, etc)</li>
          </ul>


<h2>
Usage</h2>



<ul>
  <li>Make sure you’ve got jQuery added to your page (minimaly jQuery 1.7.0)</li>
<li>Include jquery.multipurpose_tabcontent.js</li>
    <ul>

   <pre><span class="nt">&lt;script </span><span class="na">src=</span><span class="s">"js/jquery.multipurpose_tabcontent.js"</span><span class="nt">&gt;&lt;/script&gt;</span>
</pre>


  <ul>
  <li>Include style.css for a basic tab/accordion theme</li>
</ul>

<pre><span class="c">&lt;!-- Edit this file to change the style of the tabs/accordion --&gt;</span>
<span class="nt">&lt;link</span> <span class="na">type=</span><span class="s">"text/css"</span> <span class="na">rel=</span><span class="s">"stylesheet"</span> <span class="na">href=</span><span class="s">"css/style.css"</span> <span class="nt">/&gt;</span>
</pre>

<ul>
  <li>Use this HTML markup:</li>
</ul>

<pre><span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"tab_wrapper"</span><span class="nt">&gt;</span>
    <span class="nt">&lt;ul&gt;</span>
        <span class="nt">&lt;li&gt;.... &lt;/li&gt;</span>
        <span class="nt">&lt;li&gt;.... &lt;/li&gt;</span>
        <span class="nt">&lt;li&gt;.... &lt;/li&gt;</span>
        <span class="nt">&lt;li&gt;.... &lt;/li&gt;</span>
    <span class="nt">&lt;/ul&gt;</span>

    <span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"content_wrapper"</span><span class="nt">&gt;</span>
      <span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"tab_content"</span><span class="nt">&gt;</span> ....... <span class="nt">&lt;/div&gt;</span>
      <span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"tab_content"</span><span class="nt">&gt;</span> ....... <span class="nt">&lt;/div&gt;</span>
      <span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"tab_content"</span><span class="nt">&gt;</span> ....... <span class="nt">&lt;/div&gt;</span>
  <span class="nt">&lt;/div&gt;</span>
<span class="nt">&lt;/div&gt;</span>
</pre>

<ul>
  <li>Use this jQuery function to enable responsive tabs on the selected element:</li>
</ul>

<pre><span class="nx">$</span><span class="p">(</span><span class="s1">'.tab_wrapper'</span><span class="p">).</span><span class="nx">champ</span><span class="p">();</span>
</pre>

<h2>
Options</h2>

<p>No two projects are the same. That is why multipurpose_tabcontent is packed full of options that allow the tab/accordion to adapt to the project’s specific needs. Check the options for implementation.</p>

<h3>General</h3>

<h4>plugin_type</h4>
type waht to set as tab or accordion
<pre>
default: 'tab'
options: 'tab', 'accordion'
</pre>
          
<h4>side</h4>
set tab list position.
<pre>
default: 'top'
options: 'left', 'right', 'top'
</pre>
          

          
<h4>active_tab</h4>
set initial active tab
<pre>
default: '1'
options: 'numaric values'
</pre>
          

          
<h4>controllers</h4>
If true, "Next" / "Prev" controls will be added
<pre>
default: 'false'
options: boolean (true / false)
</pre>
          

          
<h4>ajax</h4>
If true, content can be added through ajax.
<pre>
default: 'false'
options: boolean (true / false)
</pre>
          

          
<h4>show_ajax_content_in_tab</h4>
If option 'ajax' is true then, 'show_ajax_content_in_tab' will show content in specified tab number.
<pre>
default: '1'
options: 'numaric values'
</pre>
          

          
<h4>content_path</h4>
If option 'ajax' is true then, 'content_path' will show content in specified tab content area.
<pre>
default: 'false'
options: 'file path'
</pre>
default: '1'
options: 'numaric values'
</pre>
          

          
<h5>controllers</h5>
If true, "Next" / "Prev" controls will be added
<pre>
default: 'false'
options: boolean (true / false)
</pre>
          

          
<h5>ajax</h5>
If true, content can be added through ajax.
<pre>
default: 'false'
options: boolean (true / false)
</pre>
          

          
<h5>show_ajax_content_in_tab</h5>
If option 'ajax' is true then, 'show_ajax_content_in_tab' will show content in specified tab number.
<pre>
default: '1'
options: 'numaric values'
</pre>
          

          
<h5>content_path</h5>
If option 'ajax' is true then, 'content_path' will show content in specified tab content area.
<pre>
default: 'false'
options: 'file path'
</pre>

<h5>multiple_tabs</h5>
If true, First tablist can be converted into dropdown
<pre>
default: 'false'
options: boolean (true / false)
</pre>
                        
                  

