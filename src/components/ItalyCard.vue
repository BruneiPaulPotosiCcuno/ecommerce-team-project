<script>
export default {
    name: 'ItalyCard',
    props: ['cardInfo'],
}
</script>

<template>
    <div class="comic-card">
        <div class="comic-image">
            <img :src="cardInfo.thumb">
        </div>

        <p class="py-2">{{ cardInfo.series }}</p>
    </div>

</template>

<style>
    .comic-card {
        width: calc((100% / 6) - 12px);
        img {
            display: block;
            width: 100%;
            height: 190px;
            object-fit: cover;
            object-position: top;
        }
    }

</style>