# sparta-global-mini-website

## Aim
To design a 3 page mini website incorporating all that was learnt in week 1. Using HTML, CSS and Bootstrap to style the website.

## Features
### All pages
* Responsive navbar with hamburger menu
* Jumbotron with background styled with CSS

```CSS
.jumbotron {
  background: url(https://ec4071ced0f087a8dd73-2a0aec697fc362de045ce5e0c53ec223.ssl.cf3.rackcdn.com/56d70468705a1.jpeg);
  background-size: cover;
}
```

* Added pagination to all pages. Used CSS to `float` pagination towards the right.

```HTML
<div class="pagination">
  <a href="">&laquo;</a>
  <a href="">1</a>
  ...
  <a href="">&raquo;</a>
</div>
```

* Footer (remembering to `clear` the footer element in CSS)

```css
footer {
  clear: both;
}
```
<br>
### Page 1
* Used bootstrap to position forms on page

```HTML
<div class="form-group col-md-3">
```
* Placed a Carousel with indicators using CSS to determine `max-width`.

```HTML
<div id="myCarousel" class="carousel slide" data-ride="carousel">
  <!-- Indicators -->
  <ol class="carousel-indicators">
    <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
    <li data-target="#myCarousel" data-slide-to="1"></li>
    ...
  </ol>
```
<br>
### Page 2
* Bootstrap used to position thumbnails
* Videos with controls added to thumbnails

```HTML
<video width="" height="" controls>
```
* Bordered table added in a separate div container

```HTML
<table class="table table-bordered">
```
<br>
### Page 3
* Bootstrap used to position thumbnails across the page
* Content styled in CSS

```css
body > div:nth-child(3) {
  display: block;
  font-family: monospace;
}
```
