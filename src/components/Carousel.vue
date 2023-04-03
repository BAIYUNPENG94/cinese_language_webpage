<template>
    <div class="swiper-container">
        <div class="swiper-wrapper">
            <div v-for="(item, index) in items" :key="index" class="swiper-slide">
                <img :src="item.image" class="w-full h-auto cursor-pointer" @click="navigateTo(item.url)" />
            </div>
        </div>
        <div class="swiper-pagination"></div>
    </div>
</template>

<script>
import Swiper from 'swiper';

export default {
    name: 'Carousel',
    props: {
        items: {
            type: Array,
            required: true,
        },
    },
    mounted() {
        this.swiper = new Swiper(this.$el, {
            pagination: {
                el: '.swiper-pagination',
                clickable: true,
            },
            slidesPerView: 3,
            spaceBetween: 16,
            loop: true,
            breakpoints: {
                640: {
                    slidesPerView: 1,
                    spaceBetween: 8,
                },
                768: {
                    slidesPerView: 2,
                    spaceBetween: 16,
                },
                1024: {
                    slidesPerView: 3,
                    spaceBetween: 16,
                },
            },
        });
    },
    beforeDestroy() {
        if (this.swiper) {
            this.swiper.destroy();
        }
    },
    methods: {
        navigateTo(url) {
            window.location.href = url;
        },
    },
};
</script>

<style scoped>
.swiper-slide {
    width: calc(100% / 3 - 16px);
}

.swiper-pagination-bullet-active {
    background-color: #4f46e5;
}
</style>
