# Bootstrap AutoDrop

Forked from Daniel Farell's original plugin (https://github.com/danielfarrell/bootstrap-combobox).  
This plugin uses the original bootstrap<a href="http://getbootstrap.com/components/#input-groups-buttons-segmented"> segmented button </a> and transforms it into an auto predicted dropdown

## How to use it

The dependencies are the Bootstrap stylesheet(CSS or LESS).  Include it and then the stylesheet(CSS or LESS) and javascript.

Add the original Twitter Bootstrap v3 segmented button code as follows, then just initialize the plugin!
```HTML
 <div class="input-group autoddl">
    <input type="text" class="form-control" placeholder="Field">
    <div class="input-group-btn">
        <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown"> <span class="caret"></span>
        </button>
        <ul class="dropdown-menu typeahead typeahead-long">
            <li><a href="x"> Address   	  </a></li>
            <li><a href="x"> City   	     </a></li>
            <li><a href="x"> CompanyName  </a></li>
            <li><a href="x"> ContactName  </a></li>
            <li><a href="x"> ContactTitle </a></li>
        </ul>
        <input type="hidden" data-name="Field">
    </div>
    <!-- /btn-group -->
</div>
<!-- /input-group -->
<script type="text/javascript">
    $(document).ready(function () {
        $('.autoddl').autodrop();
    });
</script>
```
## Live 
<a target="_blank" href="https://dl.dropboxusercontent.com/u/269057305/autodrop/index.html">
Example
</a>

## License

Licensed under the Apache License, Version 2.0
