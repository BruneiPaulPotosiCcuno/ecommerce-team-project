<script>
import FlashCard from "./FlashCard.vue"
export default{
    name: 'AppFlashSale',
    components: {
        FlashCard
    },
    data(){
        return{
            flashSaleItems: [
                {
                    name: "Caricabatterie",
                    price: 29,
                    discount: 20
                },
                {
                    name: "Caricabatterie",
                    price: 154,
                    discount: 25
                },
                {
                    name: "Caricabatterie",
                    price: 67,
                    discount: 10,
                    img: "src"
                }
            ]
        }
    }
}

</script>

<template>
    <section id="flash-sales">
        <div class="container mb-2 p-3 d-flex gap-3 bg-ms">
            <FlashCard v-for="item in flashSaleItems" :item="item"></FlashCard>
        </div>
    </section>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;

    .bg-ms{
        background-color: white;
    }
</style>