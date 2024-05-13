<script>
export default {
    name: 'AppHeader',
}

</script>

<template>
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container-fluid">
                <!-- Section: Logo -->
                <a class="navbar-brand" href="#">
                    <img src="https://logos-world.net/wp-content/uploads/2020/04/Amazon-Logo.png" height="60"
                        alt="Amazon Logo">
                </a>
                <!-- Section: Nav-left -->
                <div class="d-flex">
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarNav">
                        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                            <li class="nav-item">
                                <a class="nav-link" href="#">
                                    <i class="bi-geo-alt-fill me-1"></i> Spedire a
                                </a>
                            </li>
                            <li class="nav-item">
                                <div class="input-group">
                                    <input type="text" class="form-control" placeholder="Ricerca Amazon.it">
                                    <button class="btn btn-warning" type="button">
                                        <i class="bi-search"></i>
                                    </button>
                                </div>
                            </li>
                        </ul>
                    </div>
                </div>
                <!-- Section: Nav-right -->
            </div>
        </nav>
    </header>
</template>

<style scoped lang="scss"></style>