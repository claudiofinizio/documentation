<span id="install-django-cms-tutorial"></span><h1>Design a new rural water supply<a class="headerlink" href="#design-a-new-rural-water-supply" title="Permalink to this headline">¶</a></h1>
<div class="section" id="first-step">
<h2>First step<a class="headerlink" href="#first-step" title="Permalink to this headline">¶</a></h2>
<p>First, navigate to <a class="reference external" href="http://ruralwater.pythonanywhere.com/">the demo</a>
You will be prompted with a map.</p>
<a class="reference internal image-reference" href="_images/the_map.png"><img alt="the initial map" class="align-center" src="_images/the_map.png" style="width: 800px;" /></a>
<div class="section" id="what-s-happening-here">
<h3>What’s happening here<a class="headerlink" href="#what-s-happening-here" title="Permalink to this headline">¶</a></h3>
<p>Use the mouse to pan and zoom the map in the area of your interest. Here, for illustration purposes, we show the area of ‘Chamkoroma’ in central Tanzania.</p>
<p>Click on the marker icon in the toolbar</p>
<a class="reference internal image-reference" href="_images/tools-select-marker-with-red.png"><img alt="" class="align-center" src="_images/tools-select-marker-with-red.png" style="width: 80px;" /></a>
<p>Place a marker on the position of the spring intake, by clicking on the map.</p>
</div>
<div class="section" id="id1">
<h3>What’s happening here<a class="headerlink" href="#id1" title="Permalink to this headline">¶</a></h3>
<p>Your first click defines the position of the <strong>source</strong> of water.</p>
<p>Proceeed to draw your ‘tree’ of pipe trenches from the spring until the water reservoirs in the ‘villages’ (or near where the benefciries live).</p>
<p>To this end, click in all points of the map, which correpond either to a reservoir or to a junction.
You will end up with a number of markers shown on the map.</p>
<a class="reference internal image-reference" href="_images/markers-drawn1.png"><img alt="" class="align-center" src="_images/markers-drawn1.png" style="width: 800px;" /></a>
</div>
</div>
<div class="section" id="second-step">
<h2>Second step<a class="headerlink" href="#second-step" title="Permalink to this headline">¶</a></h2>
<p>Click on the ‘line’ marker in the toolbar.</p>
<a class="reference internal image-reference" href="_images/tools-select-polyline1.png"><img alt="" class="align-center" src="_images/tools-select-polyline1.png" style="width: 80px;" /></a>
<div class="section" id="id2">
<h3>What’s happening here<a class="headerlink" href="#id2" title="Permalink to this headline">¶</a></h3>
<p>Starting from the water source, connect the various markers with a line that represents the trench where you want to lie down the water pipes.
Notice that the line ‘sticks’ to the markers when you move the mouse near a marker.
When the line ‘sticks’ to a marker, then you complete drawing the line by <strong>double clicking</strong>.</p>
<p>If needed, you can click along the way, while you draw the line, in order to make your water pipe trench bend.</p>
<a class="reference internal image-reference" href="_images/polyline-bending1.png"><img alt="" class="align-center" src="_images/polyline-bending1.png" style="width: 800px;" /></a>
</div>
<div class="section" id="id3">
<h3>What’s happening here<a class="headerlink" href="#id3" title="Permalink to this headline">¶</a></h3>
<p>You draw all the water pipes, one after the other.</p>
<p>For example, from the spring source to the first junction or reservoir.</p>
<a class="reference internal image-reference" href="_images/polyline-first1.png"><img alt="" class="align-center" src="_images/polyline-first1.png" style="width: 800px;" /></a>
<p>Then, from the junction to one of the villages reservoir.</p>
<a class="reference internal image-reference" href="_images/polyline-second.png"><img alt="" class="align-center" src="_images/polyline-second.png" style="width: 800px;" /></a>
<p>Finally, from the junction to the reservoir of the other village reservoir.</p>
<a class="reference internal image-reference" href="_images/polyline-last1.png"><img alt="" class="align-center" src="_images/polyline-last1.png" style="width: 800px;" /></a>
<div class="admonition important">
<p class="admonition-title">Important</p>
<p>This is an initial version of the webapp so the user interface
is basic and assumes that the user completes all operations correctly.</p>
<blockquote>
<div><p>In particular, you must connect all the markers using the ‘sticking’ effect.
If you fail to do so, or if you draw lines which do not end onto markers, the results
will be an error (shown when you click the ‘Forward’ button below the map) and you will be requested to restart from scratch your drawing.</p>
</div></blockquote>
<p>Improvements are under way in a future version.</p>
</div>
<p><strong>Once you have completed drawing</strong> click on the <code class="docutils literal notranslate"><span class="pre">Forward</span></code> button to move to the next step of the wizard.</p>
</div>
</div>
<div class="section" id="third-step">
<h2>Third step<a class="headerlink" href="#third-step" title="Permalink to this headline">¶</a></h2>
<p>You may now define how much water is required at each of the reservoirs.</p>
<div class="section" id="id4">
<h3>What’s happening here<a class="headerlink" href="#id4" title="Permalink to this headline">¶</a></h3>
<p>You are presented a form, with one row for each of the markers you defined in the map, but for the first marker (the one of the spring).</p>
<p>Enter how many cubic meters are needed at each reservoir. The default value of 86, represents one liter per second flowing along the 24 hours.</p>
<p>If you leave one of the demands <strong>empty</strong> that will mean that you do not need water at that point, and the software will consider the point as a junction (under pressure) and not as a reservoir.</p>
<a class="reference internal image-reference" href="_images/define-the-demand-at-nodes1.png"><img alt="" class="align-center" src="_images/define-the-demand-at-nodes1.png" style="width: 800px;" /></a>
<div class="admonition important">
<p class="admonition-title">Important</p>
<p>Again, this is an initial version of the webapp and the user interface is basic and assumes the user performs all operations correctly.
In particular, here, you must define a demand for the <em>leaves</em> of your water supply, i.e.: for the “leaves” of your tree of trenches. Otherwise and error will occour and you will have to restart the drawing process from scratch.</p>
</div>
<p><strong>Once you have defined the demands</strong> click on the <code class="docutils literal notranslate"><span class="pre">Forward</span></code> button to move to the next step of the wizard.</p>
</div>
</div>
<div class="section" id="fourth-step">
<h2>Fourth step<a class="headerlink" href="#fourth-step" title="Permalink to this headline">¶</a></h2>
<p>ruralwater will now carry out its calculations trying to find the best economic pipes to supply by gravity the amount of water you specified.</p>
<p>The unit cost of pipes at present cannot be edited by the user and is inferred from some data from the field.</p>
<p>You will be shown a page with the proposed polyethylene pipes along with the altimetric and hydraulic pressure profiles for each of the branches of your water supply.</p>
<p>If there is no way to carry the water (for example, either the terrain is too flat to carry that amount of water by gravity) then the webapp will inform you that the design failed.</p>
<div class="admonition important">
<p class="admonition-title">Important</p>
<p>The drawings will also show (in green color) the profile at 60 meters above the ground level. If the pressure profile intersects this line, care must be taken to use higher pressure polyethylene pipes. The improved calculations, which optimize taking in account these higher pressure will be released soon. Further, it will be possible to edit the unit costs of polyethylene pipes.</p>
</div>
<p>This completes the use of the webapp in this initial version.</p>
