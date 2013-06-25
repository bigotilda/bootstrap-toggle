Bootstrap Toggle Switches
=========================

* Checkbox state setting now compatible to jQuery 1.10.1
* [LESS](http://lesscss.org) support for both `bootstrap-toggle.css` and `bootstrap-toggle-animated.css`
* Check out `examples` for usage
* Enjoy, Nijiko and Nate tried to make it as versatile as possible!

### Requirements

1. [jQuery](http://jquery.com) 1.10
2. [Bootstrap](http://twitter.github.com/bootstrap) 2.3.2

### Installation

First, include `bootstrap-toggle.css` right after Bootstrap's CSS;
alternatively use `bootstrap-toggle-animated.css` for animated switches.

Second, include `bootstrap-toggle.js` after jQuery.


####HTML:

    <div class='toggle basic' data-enabled="ON" data-disabled="OFF" data-toggle="toggle">
        <input type="checkbox" value="1" name="myCheckbox" class="checkbox" checked="checked" />
        <label class="check" for="myCheckbox"></label>
    </div>


####Javascript:

    <script>
    $('.basic').toggleSlide();
    </script>


### Contributors

* Nate Nadeau <https://github.com/bigotilda>
* Nijiko Yonskai <http://twitter.com/nijikokun>


Copyright 2012 Goodybag, Inc.
