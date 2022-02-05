<template>
  <div>
      <Header />
      <h1 class="text-center text-5xl text-blue uppercase font-bold m-5">pengasuhan</h1>
      <div v-for="n in news" :key="n.id">
        <div v-if="n.category == 'pengasuhan'">
            <Article :id="n.id" :image="n.image" :title="n.title" :desc="n.desc" :category="n.category" :date="n.date" />
        </div>
      </div>
      <Footer />
    </div>
</template>

<script>
import {news} from '../utils/news'
export default {
  data(){
    return{
      news
    }
  },
};
</script>

<style>

</style>