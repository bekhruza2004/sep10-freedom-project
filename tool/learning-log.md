# Tool Learning Log

## Tool: **Bulma**

## Sources:

[YouTube Bulma CSS Playlist](https://www.youtube.com/playlist?list=PL4cUxeGkcC9iXItWKbaQxcyDT1u6E7a8a)  

[Bulma Documentation](https://bulma.io/documentation/)

### 3/3/25:

### Learned

* Bulma is designed with a mobile-first framework in mind, meaning it allows developers to build responsive websites that look great on all devices from the start.
* Flexbox Grid System: Utilizes a powerful Flexbox-based grid system, enabling easy creation of responsive layouts. You can structure your page with a simple class structure:

```
<div class="columns">
    <div class="column is-half">...</div>
    <div class="column is-half">...</div>
</div>
```
* Typography Management: Bulma offers rich typography styling with various classes to manage text sizes, weights, and colors effectively, such as:

```
<h1 class="title is-1">Main Title</h1>
```

### 3/16/25:

* Desktop Navbar: The desktop navbar is a horizontal navigation bar typically displayed at the top of the webpage. It is designed for larger screens, such as laptops and desktops, providing easy access to various sections of the site. The desktop navbar often includes branding, links, and sometimes dropdown menus for more options.

```
<nav class="navbar">
  <div class="navbar-brand">
    <a class="navbar-item" href="#">Brand</a>
  </div>
  <div class="navbar-menu">
    <div class="navbar-start">
      <a class="navbar-item" href="#">Home</a>
      <a class="navbar-item" href="#">About</a>
      <a class="navbar-item" href="#">Services</a>
      <a class="navbar-item" href="#">Contact</a>
    </div>
  </div>
</nav>
```

* Mobile Navbar: The mobile navbar adapts to smaller screen sizes by collapsing into a more compact format. Typically, it features a hamburger menu icon that, when clicked, reveals the navigation links.

```
<nav class="navbar">
  <div class="navbar-brand">
    <a class="navbar-item" href="#">Brand</a>
    <a class="navbar-burger" role="button" aria-label="menu" aria-expanded="false">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>
  <div class="navbar-menu">
    <div class="navbar-start">
      <a class="navbar-item" href="#">Home</a>
      <a class="navbar-item" href="#">About</a>
      <a class="navbar-item" href="#">Services</a>
      <a class="navbar-item" href="#">Contact</a>
    </div>
  </div>
</nav>
```

### 3/23/25:

* Basic Structure: Breadcrumbs use a `<nav>` container with an unordered list `<ul>`, where each item `<li>` represents a step in navigation, with the current page marked by the `is-active` class.  

```
<nav class="breadcrumb" aria-label="breadcrumbs">
  <ul>
    <li><a href="#">Home</a></li>
    <li class="is-active"><a href="#">Current Page</a></li>
  </ul>
</nav>
```

* Separator Styles: Bulma allows different separator styles, such as `has-arrow-separator` and `has-dot-separator`, to customize the appearance of breadcrumbs.  

```
<nav class="breadcrumb has-dot-separator" aria-label="breadcrumbs">
  <ul>
    <li><a href="#">Home</a></li>
    <li class="is-active"><a href="#">Current Page</a></li>
  </ul>
</nav>
```

### 4/6/25:

<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
