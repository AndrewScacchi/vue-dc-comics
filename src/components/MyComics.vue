<template>
    <div class="comix">
        <div v-for="(detail, i) in details" :key="i" class="comic">
            <img :src="detail.thumb" :alt="detail.series">
            <h5>{{ detail.series }}</h5>
        </div>
    </div>
    
</template>

<script>
export default {
  name: 'MyComics',
  props: {
    details: Object
  }
}
</script>