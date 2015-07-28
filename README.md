# 2015-cherub-talent

Paste this into your Wordpress post:

```
<div id="example"></div>
<script type="text/javascript" src="//www.cherubs2015.org/wp-content/themes/cherubs-2015/js/vendor/pym.min.js"></script> <script> var pymParent = new pym.Parent("example", "//medillcherubs.github.io/2015-cherub-talent/index.html", {}); </script>

<!-- Edit: https://github.com/medillcherubs/2015-cherub-talent/edit/gh-pages/index.html -->
```

Paste this into the bottom of your `index.html`:

```
<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script> <script src="https://cdnjs.cloudflare.com/ajax/libs/pym/0.4.5/pym.min.js"></script> <script> $(function(){ var pymChild = new pym.Child({polling: 500}); }); </script> 
```
