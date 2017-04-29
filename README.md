# Livid Front End Web Framework

![N|Solid](https://cdn.pixabay.com/photo/2015/12/13/13/55/samuel-l-jackson-1091138_960_720.png)

## It's a bad mother fucker
Dealing with unruly clients?
Take Livid Framework for a test drive and blow off some steam!
---
### Getting Started
Add Our livid.css file to the header in your index.html file
```html
<!--basic template-->
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
  <title>Livid Framework Basic Template</title>
  <link rel="stylesheet" href="livid.css">
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
  <dt>row-mother-fucker</dt>
  <dd>Will produce a row with a max-width of 1200px</dd>

  <dt>row-fluid-mother-fucker</dt>
  <dd>Will produce a row that is always 100% width</dd>
</dl>

---
