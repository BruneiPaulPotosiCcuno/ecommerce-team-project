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

        <p class="subtitle">{{ cardInfo.series }}</p>
    </div>

</template>

<style>
    .comic-card {
        width: calc((100% / 7) - 12px);
        text-align: center;
        img {
            display: block;
            width: 100%;
            height: 170px;
            object-fit: cover;
            object-position: top;
            border-radius: 50%;
            overflow: hidden;
        }

        .subtitle {
            background-color: #fff;
        }
    }

</style>