<template>
    <div class="card border-0">
        <div class="img-box ratio ratio-1x1">
            <img :src="imgUrl" :alt="`immagine del fumetto ${cardTitle}`">
        </div>
        <div class="card-body text-white text-uppercase">
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


<style lang="scss" scoped>


.card-body {
    background-color: #1C1C1C;
    border:1px solid #1C1C1C;
    font-size: 13px;

.card{
    &:hover{
        .card-overlay:{
            opacity: 1;
        }
        .card-overlay{
            position: absolute;
            left: 0;
            right: 0;
            top: 0;
            bottom: 0;
        }
    }
}

}

.img-box {
    width: 100%;
    overflow: hidden;

}
</style>