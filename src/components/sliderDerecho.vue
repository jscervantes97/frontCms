<template>
    <div>
        <h4>Secciones Disponibles En El Blog</h4>
        <b-list-group>
        <b-list-group-item>
           <router-link :to="{ name: 'publicacion', params: { userId: 123 }}">User</router-link>
        </b-list-group-item>
        <b-list-group-item>Articulo 2</b-list-group-item>
        <b-list-group-item>Articulo 3</b-list-group-item>
        <b-list-group-item>Articulo 4</b-list-group-item>
        <b-list-group-item>Articulo 5</b-list-group-item>
        </b-list-group>
    </div>
</template>
<script >
</script>