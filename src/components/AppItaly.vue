<script>
import ItalyCard from './ItalyCard.vue';
export default {
    name: 'AppItaly',
    components: {
        ItalyCard
    },
    data() {
        return {
            cards: [
                {
                    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                    "series": "Action Comics",
                },
                {
                    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                    "series": "Action Comics",
                },
                {
                    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                    "series": "Action Comics",
                },
                {
                    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                    "series": "Action Comics",
                },
                {
                    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                    "series": "Action Comics",
                },
                {
                    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                    "series": "Action Comics",
                },
                {
                    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                    "series": "Action Comics",
                }
            ]
        }
    }
}

</script>

<template>
    <div class="container">
        <div class="d-flex">
            <h3>Scopri i prodotti Made in Italy</h3>
            <a href="#">Scopri</a>
        </div>
        <section class="card-list container py-5">
            <ItalyCard v-for="card in cards" :cardInfo="card"></ItalyCard>
        </section>

    </div>
</template>

<style scoped lang="scss">

    .card-list {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
    }
</style>