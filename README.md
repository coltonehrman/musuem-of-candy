Museum Of Candy
======================
**[View Completed Project](https://coltonehrman.github.io/musuem-of-candy/)**

Created this project as part of Udemy Course - [Course Link](https://www.udemy.com/share/101W9CBUobdVZUQXo=/) to learn how to use [Bootstrap 4](https://getbootstrap.com/) in laying out Web pages in a modern grid layout.

## Structure Of Project
### NavBar

Custom Navbar with a bit of extra CSS to give it a different feel from the default Bootstrap Navbars.

*CSS*
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

*HTML*
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

### First Row

*CSS*
```css
.headingGroup h2 {
    font-size: 2.5rem;
    font-weight: 200;
}

.headingGroup h2 span {
    color: #EA1C2C;
}
```

*HTML*
```html
<!-- First Row -->
<div class="row align-items-center">
    <!-- Museum Of Candy Text -->
    <div class="col-12 col-lg-6 d-none d-lg-block">
        <div class="headingGroup text-white text-center text-uppercase">
            <h2>museum<span>/</span>of<span class="custom-red">/</span>candy</h2>
            <h2>museum<span>/</span>of<span class="custom-red">/</span>candy</h2>
            <h2>museum<span>/</span>of<span class="custom-red">/</span>candy</h2>
            <h2>museum<span>/</span>of<span class="custom-red">/</span>candy</h2>
            <h2>museum<span>/</span>of<span class="custom-red">/</span>candy</h2>
            <h2>museum<span>/</span>of<span class="custom-red">/</span>candy</h2>
            <h2>museum<span>/</span>of<span class="custom-red">/</span>candy</h2>
        </div>
    </div>

    <!-- Hand Image -->
    <div class="col-12 col-lg-6 p-0">
        <img class="img-fluid" src="imgs/hand2.png" alt="">
    </div>
</div>
```