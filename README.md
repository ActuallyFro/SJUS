Simple JavaScript UI and Styles (SJUS)
======================================

Navbar Example
--------------

```html
<nav class="navbar navbar-expand-lg navbar-light">
    <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDarkDropdown" aria-controls="navbarNavDarkDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavDarkDropdown">
        <ul class="navbar-nav">
        <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDarkDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
            </a>
            <ul class="dropdown-menu dropdown-menu-light">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
            </ul>
        </li>
        <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDarkSettingsMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Settings
            </a>
            <ul class="dropdown-menu dropdown-menu-light">
            <li>
                <div class="dropdown-item">
                <div class="form-check form-switch">
                    <input class="form-check-input" type="checkbox" id="toggleDarkMode" checked>
                    <label class="form-check-label" for="toggleDarkMode">Dark Mode</label>
                </div>
                </div>
            </li>
            </ul>
        </li>
        </ul>
    </div>
    </div>
    <a class="navbar-brand" href="#">SPA with Dark Mode</a>
</nav>

<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.7/dist/umd/popper.min.js" integrity="sha384-zYPOMqeu1DAVkHiLqWBUTcbYfZ8osu1Nd6Z89ify25QV9guujx43ITvfi12/QExE" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.min.js" integrity="sha384-Y4oOpwW3duJdCWv5ly8SCFYWqFDsfob/3GkgExXKV4idmbt98QcxXYs9UoXAB7BZ" crossorigin="anonymous"></script>
<script src="./scripts/SJUS_1-0-0_DarkModeSwitch.js"></script>
```


Scroll to Top Button
--------------------

```html
<head>
    <link href="./styles/SJUS_1-0-0_ScrollToTop.css" rel="stylesheet">
</head>

<body>
    <button onclick="scrollPageToTopOfPage()" id="scrollButtonToTop" title="Go to top">Top</button>

    <script src="./scripts/SJUS_1-0-0_ScrollToTopButton.js"></script>
<body>
```