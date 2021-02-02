<template>
    <div id="productos">
        <div class="cajas">
            <div><img src="\img\swblack.png" alt="" width="65">
            <h4>Oppo Watch </h4></div>
            <div><img src="\img\swnegro.png" alt="" width="100">
            <h4>Swatch Slim</h4></div>
            <div><img src="\img\swdeport.png" alt="" width="80">
            <h4>Sport Watch</h4></div>
            <div><img src="\img\swrosa.png" alt="" width="80">
            <h4>Apple Watch</h4></div>
            <div><img src="\img\swduo.png" alt="" width="105">
            <h4>Wings Watch</h4></div>
            <div><img src="\img\swoscuro.png" alt="" width="80">
            <h4>Huawei GT2</h4></div>
        </div>
    </div>
</template>

<script>
export default {
    name:"productos",
}
</script>

<style scoped>
#productos{
    background:url('https://t3.ftcdn.net/jpg/02/96/61/86/360_F_296618633_xFJ5DjWxQOoNs1qrRJg4HKJsowPBgCaT.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    height: 510px;
    

}
.cajas{
    display: flex;
    justify-content: space-around;
    width: 100%;
    height: 100%;
    align-items: center;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
}
</style>