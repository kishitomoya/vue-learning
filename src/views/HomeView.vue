<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
import {RouterLink} from "vue-router";
</script>

<template>
    <main style="margin: auto;
    margin-top: 16px;">
        <div class="header">
            <div class="headLine">
                対象読者とこのサイトで伝えたいこと
            </div>
            <div class="mainText">
                健康的な生活に必要なのはやはり、食事と運動です。しかし、普段仕事に追われている
                サラリーマンが適度な運動と食生活を送るのは、難しいですよね。
                ストレスと食欲との関係には、様々なホルモンが関係しており、ノルアドレナリンが増加し食欲が
                増加します。
                また、運動に関しても、何から始めればいいのかわからない人が多数だと思います。
                このサイトでは、サラリーマンのような時間が確保できない方に向けた食事方法やトレーニングメニューをご紹介します。
            </div>
        </div>
        <div class="mainContents">
            <div class="tiles" style="display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: auto;
    grid-column-gap: 16px;">
                <RouterLink to="/eating">
                    <section class="tile" id="eating" style="border: black 2px solid;">
                        <header>
                            食事編
                        </header>
                        <main>
                            <img src="../../public/kaisya_snack_man.png" width="80" height="77" alt="会社男飯">
                            <img src="../../public/kaisya_snack_woman.png" width="80" height="77" alt="会社女飯">
                        </main>
                        <footer>
                            詳しくはこちら
                        </footer>
                    </section>
                </RouterLink>
                <RouterLink to="/training">
                    <section class="tile" id="training" style="border: black 2px solid;">
                        <header>
                            トレーニング編
                        </header>
                        <main>
                            <img src="../../public/business_man_macho.png" width="80" height="80" alt="筋肉男">
                            <img src="../../public/business_woman_macho.png" width="75" height="80" alt="筋肉女">
                        </main>
                        <footer>
                            詳しくはクリック
                        </footer>
                    </section>
                </RouterLink>
            </div>
        </div>
    </main>
</template>

<style lang="css">

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

main .header .mainText {
    margin-top: 10px;
    text-align: left;
}

main .mainContents {
    margin-top: 20px;
}

//tile
//なぜか適用されない
main .mainContents .tiles {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: auto;
    grid-column-gap: 16px;
}

main .mainContents .tiles section.tile {
    border: black 2px solid;
    border-radius: 8px;
    color: white;
    display: flex;
    flex-direction: column;
}

main .mainContents .tiles section.tile#eating {
    background-color: rgb(237, 125, 49);
}

main .mainContents .tiles section.tile#training {
    background-color: rgb(127, 127, 127);
}

main .mainContents .tiles section.tile header {
    text-align: left;
    margin: 10px;
    font-size: 30px;
    font-weight: bold;
}

main .mainContents .tiles section.tile main {
    display: grid;
    grid-template-columns: 1fr 1fr;
    justify-items: center;
    align-items: center;
}

main .mainContents .tiles section.tile footer {
    text-align: right;
    margin: 10px;
    align-items: flex-end;
}
</style>