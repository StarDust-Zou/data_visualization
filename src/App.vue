<template>
    <div id="app" style="position: relative">
        <Chart1 @clickFlag="clickFlag($event)"></Chart1>
<!--        <Chart2></Chart2>-->
        <Chart3></Chart3>
        <WordCloud1 v-if="flag" style="position: absolute;top: 0; "></WordCloud1>
<!--        <WordCloud2 v-if="flag" style="position: absolute;top: 0; "></WordCloud2>-->
<!--        <WordCloud3 v-if="flag" style="position: absolute;top: 0; "></WordCloud3>-->
<!--        <WordCloud4 v-if="flag" style="position: absolute;top: 0; "></WordCloud4>-->
<!--        <WordCloud5 v-if="flag" style="position: absolute;top: 0; "></WordCloud5>-->
<!--        <WordCloud6 v-if="flag" style="position: absolute;top: 0; "></WordCloud6>-->
<!--        <WordCloud7 v-if="flag" style="position: absolute;top: 0; "></WordCloud7>-->
<!--        <WordCloud8 v-if="flag" style="position: absolute;top: 0; "></WordCloud8>-->
<!--        <WordCloud9 v-if="flag" style="position: absolute;top: 0; "></WordCloud9>-->
<!--        <WordCloud10 v-if="flag" style="position: absolute;top: 0; "></WordCloud10>-->
<!--        <WordCloud11 v-if="flag" style="position: absolute;top: 0; "></WordCloud11>-->
<!--        <WordCloud12 v-if="flag" style="position: absolute;top: 0; "></WordCloud12>-->
    </div>
</template>

<script>
import Chart1 from "@/components/Chart1";
import Chart2 from "@/components/Chart2";
import Chart3 from "@/components/Chart3";
import WordCloud1 from "@/components/WordCloud1";
import WordCloud2 from "@/components/WordCloud2";
import WordCloud3 from "@/components/WordCloud3";
import WordCloud4 from "@/components/WordCloud4";
import WordCloud5 from "@/components/WordCloud5";
import WordCloud6 from "@/components/WordCloud6";
import WordCloud7 from "@/components/WordCloud7";
import WordCloud8 from "@/components/WordCloud8";
import WordCloud9 from "@/components/WordCloud9";
import WordCloud10 from "@/components/WordCloud10";
import WordCloud11 from "@/components/WordCloud11";
import WordCloud12 from "@/components/WordCloud12";
import { ref, toRefs, reactive }  from 'vue'

export default {
    name: 'App',
    components: {
        Chart1,
        Chart2,
        Chart3,
        WordCloud1,
        WordCloud2,
        WordCloud3,
        WordCloud4,
        WordCloud5,
        WordCloud6,
        WordCloud7,
        WordCloud8,
        WordCloud9,
        WordCloud10,
        WordCloud11,
        WordCloud12,
    },
    data(){
        return{
            flag:true

        }
    },
    methods:{
    },
    setup(){
        function clickFlag(e){

            const flag=ref(true);
            flag.value=true;
            return {flag}
        }
        return {clickFlag}
    }


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
