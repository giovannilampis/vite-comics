<script>

export default{
    name: "ComicBook",
    props: {
        comicDetails: Object
    }
}
</script>

<template>
    <div class="card">

            <img :src="comicDetails.thumb" :alt="comicDetails.series">

            <div class="comics-specs">

                <h6 class="text-uppercase">{{ comicDetails.series }}</h6>

                <span>{{ comicDetails.type }} - {{ comicDetails.price }}</span>

            </div>

        </div>
</template>

<style lang="scss" scoped>

</style>