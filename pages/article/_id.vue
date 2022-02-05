<template>
    <div>
        <Header />
        <div class="w-1/2 m-auto">
            <img :src="article.image" class="w-3/4 m-auto" />
            <div class="tag-yellow w-44 p-2 my-5 text-white uppercase text-center">
            <p class="font-semibold text-2xl">{{ article.category }}</p>
            </div>
            <h1 id="title-article" class="text-6xl font-semibold">
            {{ article.title }}
            </h1>
            <div class="my-5">
            <h2 class="text-xl font-semibold text-gray-500">
                Ditulis oleh
                <span class="text-gray-700 font-bold">{{ article.author }}</span>
            </h2>
            <h2 class="text-xl font-semibold text-gray-500">
                Direview oleh
                <span class="text-gray-700 font-bold">{{ article.reviewer }}</span>
            </h2>
            <h2 class="text-xl font-semibold text-gray-500">
                <font-awesome-icon
                :icon="['fas', 'clock']"
                class="text-gray-500 text-xl mt-2"
                />
                {{ article.date }}
            </h2>
            </div>
            <div id="text-wrapper" :v-html="text" class="text-3xl text-blue mb-10">
                {{ article.text }}
            </div>
        </div>
        <Footer />
    </div>
</template>

<script>
import { news } from "../../utils/news";
export default {
  data() {
    return {
      article: {},
      text: {},
    };
  },
  beforeMount() {
    news.map((n) => {
      if (n.id === this.$route.params.id) {
        this.article = n;
      }
    });
  },
};
</script>

<style></style>
