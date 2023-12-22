<script>

export default {
    card: "card",

    props: {
        cards: Array
    }
}

</script>

<template>
    <div v-for="(card,i) in cards"   :key="i" class="card-iesima">
        <img :src="card.thumb" alt="">
        <div >
            {{ card.series }}
        </div>
    </div>
</template>

<style scoped lang="scss">
@use '../style/general.scss' as *;
@use '../style/partials/variable' as *;

.card-iesima{
    width: calc(100% / 6 - 10px);
    margin: 0px 5px;
    img{
        width: 100%;
    }
}

</style>