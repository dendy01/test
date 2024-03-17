<template>
  <div class="frame3469">
    <div class="frame3468">
      <div class="frame3464">
        <div class="tag1"><a href="#">в СМИ</a></div>
        <div class="tag2"><a href="#">акции</a></div>
      </div>
      <div class="frame3002">
        <h1>Средняя ставка по ипотеке в России превысила 8%</h1>
      </div>
      <div class="frame3466 ">
        {{ day }}.{{ month }}.{{ year }}
      </div>
      <div class="frame3462">
        <div class="frame3487">
          Аналитики одного из ведущих игроков на российском рынке кредитования объясняют это завершением околонулевых программ и изменением условий по ряду <a href="#">программ с господдержкой</a>.
          При этом специалисты ВТБ прогнозируют в дальнейшем замедление роста средней ставки.
        </div>
      </div>
      <div class="content">
        <img src="https://s3-alpha-sig.figma.com/img/ac64/eb04/4b00d88c04048a5844684030287930bd?Expires=1711324800&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=WJdkGyLDJ5j29VtxdACFxGh9e2G0HLaTLZSN9xmQYKUnCEH7VkvNjuKuZq0LoIen41EK5cAiKCrAG7YTOyzcuUJM0Can1Ufwh2ZyzR735-NWZBl24ghuoCTRDXsBa7tSIv1zyZ680s7GAVx2Iz8eaCeds9lmsDnOFEJzk27CrZ4dgCy6VF9BNTAtmwu2lnmt3owyunIEYKxKA3-HrYCveOyJE~7bGk3CQVPCmENlKMnTTdU8jX73gAqTWMZYPT6i9dRAFc~QcSrRvoyRDI6jb8OAZnsQv9CyUMMBh~LILqd87mk-8DrDWELDdhsuQUh~yD3kSw3boPYiV4JECa5x~w__" alt="content">
      </div>
      <div class="frame3463">
        <div class="text-content">
          <p class="p-first">Если во втором полугодии прошлого года средняя ставка по ипотеке выросла до 7,38%, к концу года упала до 6,65%, то с начала года она выросла: на 1,2 п.п. — в январе, на 0,19 п.п. — в феврале и, по прогнозам ВТБ, на 0,26 п.п. — в марте.</p>
          <p>К концу первого квартала средняя ставка по ипотеке достигла 8,3%.</p>
          <p>Самая низкая ставка сейчас действует на рынке новостроек, благодаря программам господдержки. По оценке специалистов ВТБ, ее мартовское значение составило 5,5%—5,7%.</p>
          <p>Растущая популярность «Семейной ипотеки» в результате ее распространения на все семьи с двумя несовершеннолетними детьми и адаптация участников рынка к новым условиям «ипотеки от застройщика» помогут сбалансировать рынок первичной недвижимости.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
  import { defineProps } from 'vue';

  defineProps(['day', 'month', 'year']);
</script>

<style scoped>
  .frame3469 {
    margin-top: 30px;
  }

  .frame3464 {
    display: flex;

    a {
      text-decoration: none;
      color: black;
    }

    .tag1 {
      width: 69px;
      height: 26px;
      border-radius: 20px;
      text-align: center;
      border: 1px solid red;
    }

    .tag2 {
      width: 88px;
      height: 26px;
      margin-left: 8px;
      border-radius: 20px;
      text-align: center;
      border: 1px solid red;
    }
  }

  .frame3002 {
    font-size: 31px;
    color: #423F3F;
  }

  .frame3466 {
    width: 70px;
    color: #CFCFCF;
    border-bottom: 1px solid #CFCFCF;
  }

  .frame3462 {
    margin-top: 30px;

    .frame3487 {
      width: 510px;
      height: 100px;
      margin-left: 5px;
    }
  }

  .content {
    height: 600px;
    margin-top: 30px;

    img {
      width: 100%;
      height: 100%;
      border-radius: 32px;
    }
  }

  .frame3463 {
    margin-top: 30px;

    .text-content {
      width: 510px;
      margin-left: 5px;

      .p-first {
        margin-top: 0;
      }

      p {
        margin-top: 12px;
      }
    }
  }
</style>