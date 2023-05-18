<script>
//Definiamo il nome del componente ed eventualmente i componenti che usa (nessuno)
export default {
    name: "AppHero",
}
</script>

<!-- Quando si importa questo componente verrà visualizzato questo HTML al suo posto -->
<template>
    <div class="container">
        <div class="jumbotron">
            <h1 class="bg-primary">This is Jumbotron inside container!</h1>
            <p>Jumbotron specifies a big box for getting extra attention to some special content or information.</p>
        </div>
        <p>This is some text.</p>
        <p>This is another text.</p>
    </div>
</template>

<style ></style>