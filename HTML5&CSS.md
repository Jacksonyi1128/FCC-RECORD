# HTML5&CSS

### HTML

#####  You can start a comment with `<!--` and end a comment with `-->`

```html
<!--comment is here-->
```

#####  Import a Google Font 

```html
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css"/>//字体链接放在最上面
``` 
Add Images 
```html
<img src="https://bit.ly/fcc-relaxing-cat"
          alt="a cat">
```

##### Link to External Pages with Anchor Elements 

```html
 <p>Here's a <a href=" "> link to Free Code Camp</a> for you to follow.</p>
```

##### Turn an Image into a Link 

```html
<a  href="#">
 <img class=" " src=" " alt=" . ">
</a>
```

##### list ul/ol

```html
<ul>
  <li>one thing</li>
  <li>two things</li>
  <li>three things</li>
</ul>
```





### CSS

##### Box :  border & padding & margin

```html
<style>
   .box {
    border-style: solid;
    border-color: black;
    border-width: 5px;
    border-radius: 50%;
    text-align: center;
    background-color: yellow;
    padding: 20px 40px 20px 40px;
    margin: 20px 40px 20px 40px;
  }
</style>
```

##### RGB

```html
<style>
  .red-text {
    color: grb(0,0,0,);
  }
  </style>
```

##### visible
```html
.visible {
    visibility:visible;
    }//元素可见
.invisible {
    visibility:hidden;
}
```


 
 

##### Create a Text Field/Submit Button/Require a Field/ Radio Buttons/Checkboxes 
You can require specific form fields so that your user will not be able to submit your form until he or she has filled them out.
Each of your Radio ButtonsCheckboxes should be nested within its own label element.

```html
 <form action="/submit-cat-photo">
 <input type="text" placeholder="cat photo URL" required>
 <button type="submit">Submit</button>
 <label><input type="radio" name="indoor-outdoor"> Indoor checked</label>
 <label><input type="checkbox"name="personality">Loving</label>
</form>
```



##### Use Responsive Design with Bootstrap Fluid Containers 

```html
<div class=container-fluid>  </div>
```

##### img-responsive

```html
  <img src="https  " alt="***" class="img-responsive">
```

##### text-center

```html
<h2 class="red-text text-center">your text</h2>
```

##### a Block Element Bootstrap Button
This button would take up 100% of the available width.

```html
<button class="btn btn-block">Submit</button>
```

##### Button  
btn-info/btn-danger/btn-primary/btn-default

##### Span
 style different parts of the same element differently.

```html
<p>
Top 3 things cats <span class = "text-danger">hate:</span>
</p>
```

##### Add Font Awesome Icons
You can add Font Awesome to any app just by including it by adding the following code to the top of your HTML:
like`<i class="fa fa-info-circle">`  info`<i class="fa fa-thumbs-up">`  delete`<i class="fa fa-trash">`  

```html
 <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css"/>
 <button class="btn btn-block btn-primary"><i class="fa fa-thumbs-up">Like</i></button>
```


















 

 







