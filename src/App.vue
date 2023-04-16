<script setup lang="ts">
import {RouterLink, RouterView} from 'vue-router'
import {ref} from "vue";

const openSearchAreaFlag = ref(false);

function openSearchArea(): void {
    if (openSearchAreaFlag.value != null) {
        if (openSearchAreaFlag.value) {
            openSearchAreaFlag.value = false;
        } else {
            openSearchAreaFlag.value = true;
        }
    }
}

</script>

<template>
    <header style="display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: auto;
    margin: 0;
    background-color: white;
    border: black">
        <RouterLink to="/">
            <div class="logo">
                <img src="../public/iron_array.png" alt="アイコン" width="100" height="100">
                <div>サラリーマンのための筋トレ生活</div>
            </div>
        </RouterLink>
        <div class="support">
            <img src="../public/glass_search.png" width="52" height="71" alt="検索アイコン" @click="openSearchArea()">
            <RouterLink to="/question_answer">
                <div class="q_a">Q&A</div>
            </RouterLink>
        </div>
    </header>
    <div class="searchArea" v-if="openSearchAreaFlag">
        <div>
            <input type="text">
            <button>検索</button>
        </div>
    </div>
    <RouterView/>
</template>

<!--<template>-->
<!--  <header>-->
<!--    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />-->

<!--    <div class="wrapper">-->
<!--      <HelloWorld  msg="You did it!" />-->

<!--      <nav>-->
<!--        <RouterLink to="/">Home</RouterLink>-->
<!--        <RouterLink to="/about">About</RouterLink>-->
<!--          <RouterLink to="/eating">Eating</RouterLink>-->
<!--      </nav>-->
<!--    </div>-->
<!--  </header>-->

<!--  <RouterView />-->
<!--</template>-->

<style lang="css">
/*@import "css/normalize.css";*/

//あまり意味ないっぽい
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}

//header
//なぜか適用されない
header {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: auto;
    margin: 0;
}

header .logo {
    grid-column: 1;
    grid-row: 1;
    display: inline-flex;
    align-items: center;
}

header .support {
    grid-column: 2;
    grid-row: 1;
    display: inline-flex;
    justify-content: flex-end;
    align-items: center;
}

header .support .q_a {
    margin-left: 30px;
    margin-right: 20px;
}

.searchArea {
    background-color: rgb(237, 237, 237);
    height: auto;
    padding-top: 30px;
    padding-bottom: 30px;
}

.searchArea div {
    display: flex;
    justify-content: center;
}

.searchArea div button {
    background-color: lightblue;
    border-radius: 0;
    border: solid 1px black;
}


</style>

<!--<style scoped>-->
<!--header {-->
<!--  line-height: 1.5;-->
<!--  max-height: 100vh;-->
<!--}-->

<!--.logo {-->
<!--  display: block;-->
<!--  margin: 0 auto 2rem;-->
<!--}-->

<!--nav {-->
<!--  width: 100%;-->
<!--  font-size: 12px;-->
<!--  text-align: center;-->
<!--  margin-top: 2rem;-->
<!--}-->

<!--nav a.router-link-exact-active {-->
<!--  color: var(&#45;&#45;color-text);-->
<!--}-->

<!--nav a.router-link-exact-active:hover {-->
<!--  background-color: transparent;-->
<!--}-->

<!--nav a {-->
<!--  display: inline-block;-->
<!--  padding: 0 1rem;-->
<!--  border-left: 1px solid var(&#45;&#45;color-border);-->
<!--}-->

<!--nav a:first-of-type {-->
<!--  border: 0;-->
<!--}-->

<!--@media (min-width: 1024px) {-->
<!--  header {-->
<!--    display: flex;-->
<!--    place-items: center;-->
<!--    padding-right: calc(var(&#45;&#45;section-gap) / 2);-->
<!--  }-->

<!--  .logo {-->
<!--    margin: 0 2rem 0 0;-->
<!--  }-->

<!--  header .wrapper {-->
<!--    display: flex;-->
<!--    place-items: flex-start;-->
<!--    flex-wrap: wrap;-->
<!--  }-->

<!--  nav {-->
<!--    text-align: left;-->
<!--    margin-left: -1rem;-->
<!--    font-size: 1rem;-->

<!--    padding: 1rem 0;-->
<!--    margin-top: 1rem;-->
<!--  }-->
<!--}-->
<!--</style>-->
