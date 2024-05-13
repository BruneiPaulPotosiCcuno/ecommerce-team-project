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
        <div class="d-flex py-3">
            <h4>Scopri i prodotti Made in Italy</h4>
            <a class="ms-find px-3 py-2" href="#">Scopri</a>
        </div>
        <section class="card-list container">
            <ItalyCard v-for="card in cards" :cardInfo="card"></ItalyCard>
        </section>

    </div>
</template>

<style scoped lang="scss">
    .container {
        background-color: #fff;
    }
    .ms-find {
        text-decoration: none;
    }
    .card-list {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
    }
</style>