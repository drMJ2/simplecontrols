# Simple HTML5 Controls
This is a a set of easy to use, pure HTML5 (CSS/JS) controls, with no external dependencies. MIT license.
The controls are designed to be used as inline HTML. The only inline overhead is the class name.
Style and event handlers can be applied directly to the HTML elements.
Check out the sample file for full details.

A horizontal slider:
<input type="range" class="ctl-hslider" min="1" max="5" value="4.2" step="0.1" title="Simple slider"/>
![Example of horizontal slider](sample_images/hslider.jpg?raw=true "Example of horizontal slider")

A horizontal slider with custom style:
<input type="range" class="ctl-hslider" min="1" max="5" value="2" title="Styled slider" data-fill-color="red" style="width:300px" />
![Example of orizontal slider with style](sample_images/hsliderstyle.jpg?raw=true "Example of horizontal slider with style")

A vertical slider with an event handler:
<input type="range" class="ctl-vslider" min="1" max="5" value="4" title="Vertical slider" oninput="alert(this.value)" />
![Example of vertical slider with event handler](sample_images/vslider.jpg?raw=true "Example of vertical slider with event handler")

A panel:
<div class="ctl-panel"  title="My panel">Clicking the panel header collapses the panel.</div>
![Panel example](sample_images/panel.jpg?raw=true "Horizontal slider sample")

