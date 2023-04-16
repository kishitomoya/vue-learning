<template>
    <main style="margin: auto;
    margin-top: 16px;">
        <div class="header">
            <div class="headLine">
                PFCバランスと食事
            </div>
            <div class="introduction">
                ダイエットや健康管理における指標の一つとしてカロリーが有名です。摂取カロリーを気にすることも大事ですが、栄養が足りない場合筋肉量と代謝が落ちてしまい、逆に太りやすくなることがあります。
                そこで、関心が高まっているのが「PFCバランス」。3大栄養素である、タンパク質（Protein）、脂質(Fat)、炭水化物(Carbohydrate)が由来です。
            </div>
        </div>
        <div class="contents">
            <div>目次</div>
            <div class="item">
                <a class="list" href="#chapter1">1</a>
                <a id="chapter1" href="#chapter1">PFCバランスについて</a>
            </div>
            <div class="item">
                <a class="list" href="#chapter2">2</a>
                <a id="chapter2" href="#chapter2">サラリーマンが摂りがちな料理のPFC</a>
            </div>
        </div>
        <div class="main">
            <div id="chapter1">
                <div class="chapterTitle">PFCバランスと食事</div>
                <div class="introduction">
                    PFCの重要さがわかったところで、普段の食生活ではどのように気を付ければいいのでしょうか。
                    結論としては、一日におけるPFCの量(g)を目的別に定められたバランスに構成します。<br>
                    以下を参考にしてください。
                </div>
                <table border="2">
                    <tr>
                        <th bgcolor="#d3d3d3">目的</th>
                        <th bgcolor="#ff1493">P</th>
                        <th bgcolor="#deb887">F</th>
                        <th bgcolor="#add8e6">C</th>
                    </tr>
                    <tr>
                        <td bgcolor="#fff8dc">適度に筋肉を付けたい方</td>
                        <td bgcolor="#ffc0cb" class="PFCValue">2</td>
                        <td bgcolor="#ffefd5" class="PFCValue">2</td>
                        <td bgcolor="#f0f8ff" class="PFCValue">6</td>
                    </tr>
                    <tr>
                        <td bgcolor="#fff8dc">ダイエットしたい方</td>
                        <td bgcolor="#ffc0cb" class="PFCValue">2</td>
                        <td bgcolor="#ffefd5" class="PFCValue">2</td>
                        <td bgcolor="#f0f8ff" class="PFCValue">6</td>
                    </tr>
                    <tr>
                        <td bgcolor="#fff8dc">さらに体づくりを意識している方</td>
                        <td bgcolor="#ffc0cb" class="PFCValue">2.5</td>
                        <td bgcolor="#ffefd5" class="PFCValue">2</td>
                        <td bgcolor="#f0f8ff" class="PFCValue">5.5</td>
                    </tr>
                    <tr>
                        <td bgcolor="#fff8dc">ボディビルダーを目指す方</td>
                        <td bgcolor="#ffc0cb" class="PFCValue">4</td>
                        <td bgcolor="#ffefd5" class="PFCValue">2</td>
                        <td bgcolor="#f0f8ff" class="PFCValue">4</td>
                    </tr>
                </table>
                <div class="mainText">
                    エネルギー量としては、P=4kcal/g、F=9kcal/g、C=4kcal/gであり、食品の総カロリー計算に使われます。<br>
                    一日の総カロリー数としては、<br>
                    男性：体重*40=一日に必要な総カロリー<br>
                    女性：体重*35=一日に必要な総カロリー<br>
                    タンパク質量は体重1kgにつき1g~3kg必要とされています。トレーニングされていない方は1g、トレーニングしている方は1.5kg以上としてください。<br>
                    例えば、体重65kgの男性の場合、総カロリー数は65*40=2600kcalです。<br>
                    従って、タンパク質量は65*2=130gになります。
                    脂質は細胞膜を形成したり、ホルモンの材料となったり必要不可欠です。<br>
                    厚生労働省の進めている最低量は、総カロリーの2割です。<br>
                    従って、2600kcal*0.2=520kcal<br>
                    脂質は9kcal/gなので、520/9=57.7gです。<br>
                    PF量が決まりましたら、総カロリー数から炭水化物量を計算します。<br>
                    2600kcal-520kcal-520kcal=1560kcal<br>
                    炭水化物は4kcal/gなので、1560/4=390gです。<br>
                    ちなみに、減量を意識するのであれば、計算に用いる体重は徐脂肪体重になります。<br>
                    目的にあった計算を行ってください。
                </div>
                <div id="chapter2">
                    <div class="chapterTitle">サラリーマンが摂りがちな料理のPFC</div>
                    <div class="introduction">
                        ストレスがかかると体に悪いものを食べがちです。個人的には、ストレスがあるぐらいならたまには食べてもいいと思います。ボクも今菓子パンを食べエナジードリンクを飲みながらこのサイトを作っています。<br>
                        しかし、ストレスに関係なく普段から体に悪いものを食べてしまうと問題です。以下はサラリーマンが食べがちな食事のPFCです。<br>
                    </div>
                    <div class="dish">
                        <div class="firstStage">
                            <div class="item">
                                <div>
                                    <img src="../../public/character_food_gohan.png" width="60" height="60" alt="白米">
                                    <div>白米<br>
                                        (1合)
                                    </div>
                                </div>
                                <div class="PFC">
                                    513Kcal<br>
                                    P:8.4g<br>
                                    F:1.0g<br>
                                    C:124.7g
                                </div>
                            </div>
                            <div class="item">
                                <div>
                                    <img src="../../public/food_karaage_lemon.png" width="60" height="60" alt="白米">
                                    <div>から揚げ<br>
                                        (100g)
                                    </div>
                                </div>
                                <div class="PFC">
                                    290Kcal<br>
                                    P:13.21g<br>
                                    F:23.46g<br>
                                    C:3.75g
                                </div>
                            </div>
                            <div class="item">
                                <div>
                                    <img src="../../public/beer_man.png" width="60" height="60" alt="白米">
                                    <div>ビール<br>
                                        (100g)
                                    </div>
                                </div>
                                <div class="PFC">
                                    197Kcal<br>
                                    P:1.0g<br>
                                    F:0g<br>
                                    C:15.6g
                                </div>
                            </div>
                            <div class="item">
                                <div>
                                    <img src="../../public/food_cup_noodle_open.png" width="60" height="60" alt="白米">
                                    <div>カップラーメン<br>
                                    </div>
                                </div>
                                <div class="PFC">
                                    466Kcal<br>
                                    P:7.9g<br>
                                    F:17.6g<br>
                                    C:68.9g
                                </div>
                            </div>
                        </div>
                        <div class="secondStage">
                            <div class="item">
                                <div>
                                    <img src="../../public/pan_melonpan.png" width="60" height="60" alt="白米">
                                    <div>メロンパン<br>
                                        (100g)
                                    </div>
                                </div>
                                <div class="PFC">
                                    314Kcal<br>
                                    P:6.0g<br>
                                    F:9.2g<br>
                                    C:52.4g
                                </div>
                            </div>
                            <div class="item">
                                <div>
                                    <img src="../../public/drink_cola_petbottle.png" width="50" height="65" alt="白米">
                                    <div>炭酸飲料<br>
                                        (100ml)
                                    </div>
                                </div>
                                <div class="PFC">
                                    46Kcal<br>
                                    P:0.1g<br>
                                    F:0g<br>
                                    C:11.4g
                                </div>
                            </div>
                            <div class="item">
                                <div>
                                    <img src="../../public/energy-drink.jpg" width="25" height="70" alt="白米">
                                    <div>エナジードリンク<br>
                                        (1缶185ml)
                                    </div>
                                </div>
                                <div class="PFC">
                                    45Kcal<br>
                                    P:0.0g<br>
                                    F:0.0g<br>
                                    C:11.0g
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>

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

//main
//なぜか適用されない
main {
    margin: auto;
    margin-top: 16px;
    width: 1120px;
    background-color: black;
}

main .header .headLine {
    font-family: 'Roboto', sans-serif;
    font-weight: bold;
    color: #252525;
    font-size: 16px;
    text-align: left;
    text-decoration: underline red solid 2px;
}

main .header .introduction {
    margin-top: 10px;
    text-align: left;
}

main .mainContents {
    margin-top: 20px;
}

main .contents {
    border: 2px solid green;
    width: fit-content;
}

main .contents .item {
    display: flex;
    margin: 20px 20px 20px 20px;
}

main .contents .item a.list {
    background-color: rgb(0, 176, 240);
    color: white;
    width: 20px;
    height: 20px;
    text-align: center;
}

main #chapter1 .chapterTitle, #chapter2 .chapterTitle {
    background-color: rgb(0, 176, 240);
    color: white;
    font-size: 20px;
    font-weight: bold;
    width: fit-content;
    padding: 10px 40px 10px 10px;
    margin-top: 20px;
}

main #chapter1 table tbody tr th {
    min-width: 40px;
}

main #chapter1 table tbody tr td.PFCValue {
    text-align: center;
}

main #chapter2 .dish .firstStage, .secondStage {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    justify-content: space-between;
    margin-top: 20px;
    text-align: center;
}




</style>

<!--<style scoped>-->
<!--.logo {-->
<!--    height: 6em;-->
<!--    padding: 1.5em;-->
<!--    will-change: filter;-->
<!--    transition: filter 300ms;-->
<!--}-->

<!--.logo:hover {-->
<!--    filter: drop-shadow(0 0 2em #646cffaa);-->
<!--}-->

<!--.logo.vue:hover {-->
<!--    filter: drop-shadow(0 0 2em #42b883aa);-->
<!--}-->
<!--</style>-->


<!--<template>-->
<!--    <header style="display: grid;-->
<!--    grid-template-columns: 1fr 1fr;-->
<!--    grid-template-rows: auto;-->
<!--    margin: 0;-->
<!--    background-color: white;-->
<!--    border: black">-->
<!--        <div class="logo">-->
<!--            <img src="../../public/iron_array.png" alt="アイコン" width="100" height="100">-->
<!--            <div>サラリーマンのための筋トレ生活-->
<!--            </div>-->
<!--        </div>-->
<!--        <div class="support">-->
<!--            <img src="../../public/glass_search.png" width="52" height="71" alt="検索アイコン">-->
<!--            <div class="q_a">Q&A</div>-->
<!--        </div>-->
<!--    </header>-->
<!--</template>-->


<!--<style scoped>-->

<!--</style>-->
<script setup lang="ts">
import {RouterLink} from "vue-router";
</script>