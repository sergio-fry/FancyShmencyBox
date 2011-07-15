FancyShmancyBox
===============

This is s [FancyBox](http://fancybox.net/) fork.

## Features
* All Fancybox 1.3.4 features
* open element inside fancybox by method
* open generated html

## Example

### By method
    <div id="message">Hallo!</div>

    <script type="text/javascript">
      $(function() {
        $("#message").showFancybox();
      });
    </script>

### Generated html
    <script type="text/javascript">
      $(function() {
        $("<h1>Hi! I am generated H1!</h1>").showFancybox();
      });
    </script>
