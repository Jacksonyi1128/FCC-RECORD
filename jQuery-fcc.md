#FCC-jQuery

##### `doucment ready function` : without it, your code _may_ run before your HTML is rendered, which would cause bugs.

```html
<script>

   $(document).ready(function() {
  });

</script>
```

##### Target Elements by _Tag/Class/ID_ Using jQuery : 

```html
<script>
  $(document).ready(function() {
    $("button").addClass("animated bounce");
    $(".well").addClass("animated shake");
    $("#target3").addClass("animated fadeOut");
  });
  </script>
```

 
##### Remove & Add Classes from an element with jQuery ` removeClass()` & `addClass()` : 

```html
<script>
  $(document).ready(function() {
  $("button").removeClass("btn-default");
  $("button").addClass("animated bounce");

  });
</script>
```


##### Change the CSS  /Disable /Change Text /Remove /Use appendTo to Move Elements/clone/parent/children/Target a Specific Child/Target Even(odd) Numbered/Modify the Entire Page(fadeOut hinge)/    Using jQuery 
`.html()` that lets you add HTML tags and text within an element.
`.text()` that only alters text without adding tags.

```html
 <script>
  $(document).ready(function() {
    $("#target1").css("color", "red");
    $("#target1").prop("disabled", true);
    $("#target4").remove();
    $("#target2").appendTo("#right-well");
    $("#target5").clone().appendTo("#left-well");
    $("#target1").parent().css("background-color", "red");
    $("#right-well").children().css("color","orange");
    $(".target:nth-child(2)").addClass("animated bounce");
    $(".target:even").addClass("animated shake");
    $("body").addClass("animated hinge");
  });
</script>
```



 
 