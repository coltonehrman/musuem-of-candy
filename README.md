Museum Of Candy
======================
**[View Completed Project](https://coltonehrman.github.io/musuem-of-candy/)**

Created this project as part of Udemy Course - [Course Link](https://www.udemy.com/share/101W9CBUobdVZUQXo=/) to learn how to use [Bootstrap 4](https://getbootstrap.com/) in laying out Web pages in a modern grid layout.

## Structure Of Project
### NavBar

Custom Navbar with a bit of extra CSS to give it a different feel from the default Bootstrap Navbars.

```css
body {
    background-color: #F5D9D5;
    font-family: "Nunito", sans-serif;
}

#mainNavbar {
    font-size: 1.5rem;
    font-weight: 100;
}

#mainNavbar .navbar-brand {
    color: #EA1C2C;
    font-size: 1.75rem;
}

#mainNavbar .nav-link {
    color: white;
}

#mainNavbar .nav-link:hover {
    color: #EA1C2C;
}
```

```html
<!-- Transparent Fixed NavBar -->
<nav id="mainNavbar" class="navbar navbar-dark navbar-expand-md fixed-top bg-transparent py-0">
    <!-- NavBar Brand -->
    <a href="#" class="navbar-brand mb-0 mr-4 text-uppercase">candy</a>
    <!-- NavBar Toggler Button -->
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navLinks" aria-controls="navLinks" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <!-- NavBar Links -->
    <div class="collapse navbar-collapse" id="navLinks">
        <ul class="navbar-nav">
            <!-- NavBar Link -->
            <li class="nav-item">
                <a class="nav-link mb-0 text-uppercase" href="#">home</a>
            </li>
            <!-- NavBar Link -->
            <li class="nav-item">
                <a class="nav-link mb-0 text-uppercase" href="#">about</a>
            </li>
            <!-- NavBar Link -->
            <li class="nav-item">
                <a class="nav-link mb-0 text-uppercase" href="#">tickets</a>
            </li>
        </ul>
    </div>
</nav>
```

### First Section

```html
<div class="row">
    <div class="col-12 col-md-6" style="background-color: #F4D5E0; padding-top: 7rem; padding-bottom: 7rem;">
        <h2 class="display-4 text-center font-weight-light text-white text-uppercase">museum<span style="color: mediumvioletred">/</span>of<span style="color: mediumvioletred">/</span>candy</h2>
        <h2 class="display-4 text-center font-weight-light text-white text-uppercase">museum<span style="color: mediumvioletred">/</span>of<span style="color: mediumvioletred">/</span>candy</h2>
        <h2 class="display-4 text-center font-weight-light text-white text-uppercase">museum<span style="color: mediumvioletred">/</span>of<span style="color: mediumvioletred">/</span>candy</h2>
        <h2 class="display-4 text-center font-weight-light text-white text-uppercase">museum<span style="color: mediumvioletred">/</span>of<span style="color: mediumvioletred">/</span>candy</h2>
        <h2 class="display-4 text-center font-weight-light text-white text-uppercase">museum<span style="color: mediumvioletred">/</span>of<span style="color: mediumvioletred">/</span>candy</h2>
        <h2 class="display-4 text-center font-weight-light text-white text-uppercase">museum<span style="color: mediumvioletred">/</span>of<span style="color: mediumvioletred">/</span>candy</h2>
        <h2 class="display-4 text-center font-weight-light text-white text-uppercase">museum<span style="color: mediumvioletred">/</span>of<span style="color: mediumvioletred">/</span>candy</h2>
    </div>

    <div class="col-12 col-md-6" style="background-color: #CAECFA">
        <!-- picture colimn -->
    </div>
</div>
```