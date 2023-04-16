<template>
<main>
    <div class="chapter" id="chapter1">
        <div class="chapterTitle">食事編</div>
        <div class="question_answer">
            <div class="question">Q1チートデイってなに？意味あるの？</div>
            <div class="answer">A</div>
            <div>基礎代謝の維持、ストレス発散、栄養補給などのメリットがあります。体重制限を行っている方に効果が期待できる方法であり、ダイエット停滞期に実施すると体重が減りやすくなります。<br>
                ペースとしては週に一日が良いです。</div>
        </div>
        <div class="question_answer">
            <div class="question">Q2タンパク質の摂りすぎってデメリットある？</div>
            <div class="answer">A</div>
            <div>十分な研究結果があるわけではありませんが、極端な過剰摂取は悪影響を体に及ぼします。</div>
            <ul>
                <li>内臓疲労<br>
                    摂取したタンパク質のうち余分なものは分解されて窒素となります。<br>過剰に摂取すると多くの窒素を尿に変換しなければならず、負担が普段よりも大きくなってしまいます。
                </li>
                <li>尿路結石のリスク<br>
                    尿路結石の原因の一つに動物性たんぱく質の摂りすぎがあります。<br>
                    動物性たんぱく質は摂取すると体内でシュウ酸や尿酸などが増加します。<br>
                    腸で吸収しきれないシュウ酸は尿として排泄されますが、尿に含まれるカルシウムと結合すると石になります。
                </li>
                <li>腸内環境の乱れ<br>
                    動物性たんぱく質を取りすぎると吸収しきれなかったタンパク質が腸内に送り込まれ、悪玉菌の餌になってしまいます。<br>
                    結果、食中毒菌や病原菌による感染の危険性、発がん性をもつ腐敗産物が多く作られてしまう可能性があります。
                </li>
                <li>肌荒れ<br>
                    乾燥肌の最大の原因の一つに動物性たんぱく質の摂りすぎがあります。<br>
                    摂りすぎにより、細胞代謝で生じる老廃物などの体内毒素がたまってしまうからです。
                </li>
            </ul>
        </div>
        <div class="question_answer">
            <div class="question">Q3白米が好きなので抜きたくない</div>
            <div class="answer">A</div>
            <div>糖質を摂りすぎると下っ腹が出るし老けます。</div>
        </div>
    </div>
    <div class="chapter" id="chapter2">
        <div class="chapterTitle">トレーニング編</div>
        <div class="question_answer">
            <div class="question">Q1トレーニングなんかして何目指しているの？</div>
            <div class="answer">A</div>
            <div>オマエのようになりたくないから。</div>
        </div>
        <div class="question_answer">
            <div class="question">Q2中身を磨く方が大事なんじゃないの？</div>
            <div class="answer">A</div>
            <div>否定ばかりしているオマエはどうなの？</div>
        </div>
    </div>
</main>
</template>

<style lang="css">

main .chapter .chapterTitle {
    background-color: rgb(0, 176, 240);
    color: white;
    font-size: 20px;
    font-weight: bold;
    width: fit-content;
    padding: 10px 40px 10px 10px;
    margin-top: 20px;
}

main .chapter .question_answer .question {
    font-family: 'Roboto', sans-serif;
    font-weight: bold;
    color: #252525;
    font-size: 16px;
    text-align: left;
    text-decoration: underline black solid 2px;
}

main .chapter .question_answer .answer {
    font-family: 'Roboto', sans-serif;
    font-weight: bold;
    color: red;
    font-size: 16px;
    text-align: left;
    text-decoration: underline red solid 2px;
}

</style>
<script setup lang="ts">
</script>