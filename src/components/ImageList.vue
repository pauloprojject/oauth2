<template>
    <div>
        ImageList
    </div>
</template>

<script>
import { mapActions } from 'vuex';
export default {
    name: 'ImageList',
    methods: mapActions(['fetchImages']),
    created(){
        this.fetchImages();
        this.fetchImages();
    }
}
</script>