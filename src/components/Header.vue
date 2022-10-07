<script setup> 
    import { RouterLink } from 'vue-router'
</script>


<template>
    <nav class="navbar navbar-light bg-light sticky-top">
        <div class="container-fluid d-flex justify-content-between top-bar">
            <div>  
                <a class="text-decoration-none" href="#">
                    <img src='../assets/logo.png' alt="" class="logo">
                </a>
            </div>
            <div class="navbar-test">
                <ul class="d-flex gap-3 list-unstyled my-auto">
                    <RouterLink to="/" class="navbar-list">Home</RouterLink>
                    <RouterLink to="/about" class="navbar-list">About</RouterLink>
                    <li class="nav-item dropdown navbar-list">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDarkDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Dropdown
                        </a>
                        <ul class="dropdown-menu dropdown-menu-dark" aria-labelledby="navbarDarkDropdownMenuLink">
                            <li><a class="dropdown-item" href="#">Action</a></li>
                            <li><a class="dropdown-item" href="#">Another action</a></li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    </li>
                    <RouterLink to="/product" class="navbar-list">Product</RouterLink>
                </ul>
            </div>
            <div class="d-flex gap-2">
                <form class="d-flex">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                </form>
                <button class="btn btn-primary">Sign In</button>
            </div>
        </div>
    </nav>
</template>

<style scoped>
    .navbar-list {
        text-decoration: none;
        list-style: none;
        color: black;
    }

    .logo{
        width: 20rem;
    }

    .navbar-list:hover {
        color: rgb(97, 97, 97);
        transform: translateY(-2px);
    }

    .top-bar {
        box-shadow: 0px 2px 3px rgba(81, 81, 81, .3);
    }

</style>