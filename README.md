header_responsive_navigation
============================

### header navigatiob bar like bootstrap style

It's a responsive navigation bar on header and it is flat style.

### Feature

* No JavaScript
* Only CSS
* Easy custom style in scss
* Use media query
* Use grunt build custom style

### Demo

[Demo](http://tedshd.github.io/header_responsive_navigation/)

### Usage

Add HTML code

```html
    <div id="masthead">
        <div id="head-bar">
            <a id="logo" href="">
                <img src="" alt="logo" width="100" height="30">
            </a>
            <div id="nav-menu-btn-area">
                <div id="nav-menu-btn">
                    <div class="nav-switch-ico-bar"></div>
                    <div class="nav-switch-ico-bar"></div>
                    <div class="nav-switch-ico-bar"></div>
                </div>
            </div>
        </div>
        <div id="nav-menu">
            <input id="nav-switch" type="checkbox">
            <div id="nav">
                <ul>
                    <li class="vertical-centering">
                        <a href="">About</a>
                    </li>
                    <li class="vertical-centering">
                        <a href="">Product</a>
                    </li>
                    <li class="vertical-centering">
                        <a href="">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
```

Load CSS

```html
<link rel="stylesheet" href="css/style.css">
```

### Principle

Use input checkbox

`:checked` change style

If checkbox checked show navigation

Unchecked hide navigation

### Tips

If want use in IE8

Must use [Respond.js](https://github.com/scottjehl/Respond)