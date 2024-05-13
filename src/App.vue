<script>

import AppSponsor from "./components/AppSponsor.vue";
import AppItaly from "./components/AppItaly.vue";
import AppHeader from "./components/AppHeader.vue";
import AppFlashSale from "./components/AppFlashSale.vue";

export default {
    components: {
        AppSponsor,
        AppItaly,
        AppHeader,
        AppFlashSale
    }
}

</script>

<template>
    <AppHeader></AppHeader>
    <main>
        <AppItaly></AppItaly>
        <AppFlashSale></AppFlashSale>
        <AppSponsor></AppSponsor>
    </main>
</template>