<template>
    <div class="card">
        <img :src="imgUrl" :alt="`immagine del fumetto ${cardTitle}`">
        <div class="card-body">
            {{ cardTitle }}
        </div>

    </div>
</template>

<script>
export default {
    props: {
        imgUrl: String,
        cardTitle: String

    },
    data() {
        return {

        }
    },
};
</script>


<style>
</style>