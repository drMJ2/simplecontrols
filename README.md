# Simple HTML5 Controls
This is a a set of easy to use, pure HTML5 (CSS/JS) controls, with no external dependencies. MIT license.

The controls are designed to be used as inline HTML. The only inline overhead is the class name.
Additional CSS classes, inline styles and event handlers can be applied directly to the HTML elements.
Check out the sample file for full details.

## Installation instructions:

Copy the three simplecontrols.* files. Follow one of the two patterns ilustrated in the sample*.html files.

## Usage:

**Panel**:

A panel is a collapsible div.

`<div class="ctl-panel" title="Panel header">Panel body</div>`

![Panel example](/sample_images/panel.JPG?raw=true "Panel example")

**Slider**:

The slider behaves just like an input range control, but renders the label and value inside the slider. 

`<input type="range" class="ctl-hslider" min="1" max="5" value="4.2" step="0.1" title="Simple slider"/>`

![Example of horizontal slider](sample_images/hslider.JPG?raw=true "Example of horizontal slider")

**Horizontal slider with custom style**:

Styles can be applied inline, or through additional CSS classes. The slider can be made read-only (as a meter) by including the "disabled" attribute.

`<input type="range" class="ctl-hslider" min="1" max="5" value="2" title="Styled slider" data-fill-color="red" style="width:300px" />`

![Example of orizontal slider with style](/sample_images/hsliderstyle.JPG?raw=true "Example of horizontal slider with style")

**Vertical slider with an event handler**:

A slider can be oriented verically. Events can be attached directly.

`<input type="range" class="ctl-vslider" min="1" max="5" value="4" title="Vertical slider" oninput="alert(this.value)" />`

![Example of vertical slider with event handler](/sample_images/vslider.JPG?raw=true "Example of vertical slider with event handler")

