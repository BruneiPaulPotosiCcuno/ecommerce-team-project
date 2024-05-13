<script>
    export default{
        name: 'FlashCard',
        props: ["item"]
    }
</script>

<template>
    <div class="FlashCard">
        <div class="d-flex align-items-center">
            <small class="badge-flash">
                {{ item.discount }}% di sconto
            </small>
            <small class="badge-text">
                Offerta Lampo
            </small>
        </div>
    </div>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;

    .FlashCard{
        width: 20%;
    }

    .badge-flash{
        background-color: $rapid_offer;
        color: white;
        padding: 4px 8px;
    }

    .badge-text{
        color: $rapid_offer;
        font-weight: 600;
        margin-left: 10px
    }
</style>