<template>
    <div class="app-main-layout">
        <nav class="navbar orange lighten-1">

        </nav>
        <ul class="sidenav app-sidenav open">

        </ul>

        <main class="app-content">
            <div class="app-page">
                <router-view />
            </div>
        </main>

<div class="fixed-action-btn">
    <a class="btn-floating btn-large blue" href="#">
        <i class="large material-icons">add</i>
    </a>
</div>
    </div>
</template>