<template>
 <div id="page-wrap">
    <ProductGrid :products="products" />
</div>
</template>

<script>
import {products} from '../fake-data';
import ProductGrid from '../components/ProductGrid.vue';
export default {
 name:'ProductPage',
 components:{
     ProductGrid   
 },
 data(){
    return{
       products
    }
 }
}
</script>

