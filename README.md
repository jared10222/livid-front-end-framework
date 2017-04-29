# Livid Front End Web Framework

![N|Solid](https://cdn.pixabay.com/photo/2015/12/13/13/55/samuel-l-jackson-1091138_960_720.png)

## It's a bad mother fucker
Dealing with unruly clients?
Take Livid Framework for a test drive and blow off some steam!
---
### Getting Started
Add the livid.css file to the header in your index.html file
```html
<!--basic template-->
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
  <title>Livid Framework Basic Template</title>
  <link rel="stylesheet" href="css/livid.css">
  <!--[if lt IE 9]>
    <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
    <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
  <![endif]-->
</head>
<body>

  <header class="row-mother-fucker">
    <div class="md-ass-col-12">
      <h1>Hello Mother Fucker!</h1>
    </div><!--end col-12-->
  </header>

</body>
</html>
```

---
## Livid Grid System
The grid system is based off of a 12 column layout.
Keep those mother fucking clients happy by designing a nice fluid
mobile first website.

### Grid Options
| Empty | Tiny Screens | Small Screens | Medium Screens |  Large Screens | XL Screens |
|-------|--------------|---------------|----------------|----------------|------------|
|Class prefix| .tiny-ass-col-|.sm-ass-col-|.md-ass-col- |.lg-ass-col-    |xlg-ass-col-|
|Break Points| &lt;480px     | &ge;480px  |&ge;768px    | &ge; 968px     | &ge; 1200px|
|columns|12  |12             |12          |12           |12              |12          |

### Example: 3 columns on medium screen size
To get three columns of equal width:
```html
<div class="row-mother-fucker">
  <div class="md-ass-col-4">
    col one
  </div><!--end md-ass-col-4-->
  <div class="md-ass-col-4">
    col two
  </div><!--end md-ass-col-4-->
  <div class="md-ass-col-4">
    col three
  </div><!--end md-ass-col-4-->
</div><!--end row-->
```

| .md-ass-col-4 | .md-ass-col-4 | .md-ass-col-4|
|---------------|---------------|--------------|

<dl>
  <dt>.row-mother-fucker</dt>
  <dd>Will produce a row with a max-width of 1200px</dd>

  <dt>.row-fluid-mother-fucker</dt>
  <dd>Will produce a row that is always 100% width</dd>
</dl>

---
### Positioning Your Columns
*when using the following classes, each row must have a total of 12 columns in it.*<br />
*if you have 3 columns, then you have 3 different positions you can order them in.*<br />
__tiny-ass-pos-1__ thru **tiny-ass-pos-12**<br />
__sm-ass-pos-1__ thru **sm-ass-pos-12**<br />
__md-ass-pos-1__ thru **md-ass-pos-12**<br />
__lg-ass-pos-1__ thru **lg-ass-pos-12**<br />
__xlg-ass-pos-1__ thru **xlg-ass-pos-12**
```html
<div class="row-mother-fucker">
  <div class="sm-ass-col-4 sm-ass-pos-2">pos-2</div>
  <div class="sm-ass-col-4 sm-ass-pos-3">pos-3</div>
  <div class="sm-ass-col-4 sm-ass-pos-1">pos-4</div>
</div><!--end row-->
```
---
