<template>
  <div id="slider">
    
    <b-container>
        <b-carousel
                controls
                indicators
                img-width="1024"
                img-height="480"
                :interval="3000"
                v-model="slider"
        >
                <b-carousel-slide img-src="img\watch-navidad.jpg"
                ></b-carousel-slide>
                <b-carousel-slide img-src="img\watch-mujer.jpg">
                    <h1>No te quedes sin tu smartwatch</h1>
                </b-carousel-slide>
                <b-carousel-slide img-src="img\navidad.jpg"></b-carousel-slide>
            </b-carousel>
    </b-container>
  </div>
</template>

<script>

export default {
    name:'slider',
     data () {
    return {
        slide: 3
    }
  },
}
</script>
<style scoped>
#slider{
  background: red;
  height: 200px;  
}

</style>