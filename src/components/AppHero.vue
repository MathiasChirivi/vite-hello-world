<script>
//Definiamo il nome del componente ed eventualmente i componenti che usa (nessuno)
export default {
    name: "AppHero",
}
</script>

<!-- Quando si importa questo componente verrà visualizzato questo HTML al suo posto -->
<template>
    <div class="jumbotron text-white jumbotron-image shadow" style="
            background-image: url('https://media.geeksforgeeks.org/wp-content/uploads/20200914000601/gfg-300x200.jpg');">

        <h2 class=" mb-4 text-secondary">
            Jumbotron with background image
        </h2>

        <p class="mb-4 text-secondary">
            Hey, check this out.
        </p>

        <a class="btn btn-primary">
            Click!
        </a>
    </div>
</template>

<style scoped ></style>