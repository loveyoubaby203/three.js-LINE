3D lines animation with three.js 
========================================
...and an animated background color


Tags
-----------
HTML5, javascript, canvas, three.js, animation, colors.


What is?
-----------

I took a prebuild three.js [example](http://threejs.org/examples/#canvas_lines) and put a fancy animated background color, adjusted some parameters like number of lines, perspective and colors. Now is ready to use for everyone.


How it works?
-----------

### Javascript initialization

```html
<!-- Main library -->
<script src="js/three.min.js"></script>
      
<!-- Helpers -->
<script src="js/projector.js"></script>
<script src="js/canvas-renderer.js"></script>

<!-- Visualitzation adjustments -->
<script src="js/3d-lines-animation.js"></script>

<!-- Animated background color -->
<script src="http://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.2/jquery.min.js"></script>
<script src="js/color.js"></script>
```

### Layout

```html
<div class="canvas-wrap">
    <div class="canvas-content">
        <h1>Hello world</h1>
    </div>
    <div id="canvas" class="gradient"></div>
</div>
```

### Options

* The script is fully configurable (colors, lines, opacities, perspectives...) but you'll need to dive in to the code to adjust them. Download the files and start checking out the file 3d-lines-animation.js
