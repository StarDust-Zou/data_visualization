<template>
    <div id="app">
        <Chart1></Chart1>
<!--        <Chart2></Chart2>-->
        <Chart3></Chart3>
    </div>
</template>

<script>
import Chart1 from "@/components/Chart1";
import Chart2 from "@/components/Chart2";
import Chart3 from "@/components/Chart3";

export default {
    name: 'App',
    components: {
        Chart1,
        Chart2,
        Chart3,
    },

}

</script>

<style>
#app {
    background:url("./assets/bgimg.jpg");
    width:100%;
    height:100%;
    position:fixed;
    background-size:100% 100%;
}


</style>
