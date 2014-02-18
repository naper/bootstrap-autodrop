# Bootstrap AutoDrop

Forked from Daniel Farell's original plugin (https://github.com/danielfarrell/bootstrap-combobox).  
This plugin does not use a select list and works similar to the original bootstrap split-dropdown except with the need of an input box in place of a button

## How to use it

The dependencies are the Bootstrap stylesheet(CSS or LESS).  Include it and then the stylesheet(CSS or LESS) and javascript.

Augment the original Twitter Bootstrap v3 dropdown code as follows, then just initialize the plugin!

    <div class="btn-group autodrop">
    <input type="text" placeholder="Field" >
    <button type="button" data-toggle="dropdown" class="btn btn-default btn-sm dropdown-toggle">
    <span class="caret"></span><span class="sr-only">Toggle DropDown</span>
    </button>
    <ul class="dropdown-menu typeahead typeahead-long">
    <li><a href="x">Address</a></li>
    <li><a href="x">City</a></li>
    <li><a href="x">CompanyName</a>
    </li><li><a href="x">ContactName</a></li>
    <li><a href="x">ContactTitle</a></li></ul>
    <input type="hidden" data-name="Field">
    </div>

    <script type="text/javascript">
      $(document).ready(function(){
        $('.combobox').AutoDrop();
      });
    </script>

## Live Example

coming soon

## License

Licensed under the Apache License, Version 2.0
