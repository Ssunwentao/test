<template>
    <div id="container">
        <div class="top">
            <ul class="left">
                <li>话费撒方式</li>
                <li>话费撒方式</li>
                <li>话费撒方式</li>
                <li>话费撒方式</li>
                <li>话费撒方式</li>
                <li>话费撒方式</li>
            </ul>
            <ul class="right">
                <li>话费撒方式</li>
                <li>话费撒方式</li>
                <li>话费撒方式</li>
                <li>话费撒方式</li>
                <li>话费撒方式</li>
                <li>话费撒方式</li>
            </ul>
        </div>
        <detail></detail>
    </div>
  
</template>

<script>
import Detail from './Detail.vue';
export default {
  components: { Detail },
    name: 'Home',
    data (){
        return ;
    },
    component: {
        Detail
    }

}
</script>

<style scoped>

#contanier {
    margin: 0;
    padding: 0;    
}
.top {
    height: 80px;
}

.left {
    width: 40%;
    float: left;
}

.right {
    width: 40%;
    float: right;
}

ul {
    overflow: hidden;
}

li {
    display: inline;
    margin-right: 20px;
}

</style>