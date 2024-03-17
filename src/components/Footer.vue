<template>
  <div class="frame3486">
    <h1>Следующая статья</h1>
    <div class="news-card">
      <div class="card-news">
        <div class="label-text-card">
          {{ day }}.{{ month }}.{{ year }}
        </div>
        <img src="https://s3-alpha-sig.figma.com/img/ac64/eb04/4b00d88c04048a5844684030287930bd?Expires=1711324800&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=WJdkGyLDJ5j29VtxdACFxGh9e2G0HLaTLZSN9xmQYKUnCEH7VkvNjuKuZq0LoIen41EK5cAiKCrAG7YTOyzcuUJM0Can1Ufwh2ZyzR735-NWZBl24ghuoCTRDXsBa7tSIv1zyZ680s7GAVx2Iz8eaCeds9lmsDnOFEJzk27CrZ4dgCy6VF9BNTAtmwu2lnmt3owyunIEYKxKA3-HrYCveOyJE~7bGk3CQVPCmENlKMnTTdU8jX73gAqTWMZYPT6i9dRAFc~QcSrRvoyRDI6jb8OAZnsQv9CyUMMBh~LILqd87mk-8DrDWELDdhsuQUh~yD3kSw3boPYiV4JECa5x~w__" alt="card-news">
      </div>
      <div class="frame3188">
        <div class="frame3385">
          <h1>Правительство продлило «Льготную ипотеку» и расширило «Семейную».</h1>
        </div>
        <div class="frame3459">
          <div class="tag1"><a href="#">в СМИ</a></div>
          <div class="tag2"><a href="#">акции</a></div>
        </div>
      </div>
      <div class="btn-shadow">
        <button class="btn">&rarr;</button>
      </div>
    </div>
  </div>
</template>

<script setup>
    import { defineProps } from 'vue';

  defineProps(['day', 'month', 'year']);
</script>

<style scoped>
  .frame3486 {
    margin-top: 30px;
    height: 404px;

    h1 {
      font-size: 40px;
      font-weight: 700;
      margin-top: 10px;
    }

    .news-card {
      height: 228px;
      margin-top: 20px;
      background: #CFCFCF;
      border-radius: 26px;
      display: flex;
      justify-content: space-between;
      position: relative;

      img {
        width: 320px;
        height: 220px;
        margin: 4px 0 0 4px;
        border-radius: 24px;
      }

      .frame3188 {
        width: 410px;
        height: 220px;
        margin-top: 4px;
        margin-left: -70px;

        h1 {
          font-size: 24px;
          font-weight: 700;
          line-height: 32px;
        }

        .frame3459 {
          display: flex;
          margin-top: 80px;

          a {
            text-decoration: none;
            color: black;
          }

          .tag1 {
            width: 69px;
            height: 26px;
            border-radius: 20px;
            text-align: center;
            border: 1px solid #5B4481;
          }

          .tag2 {
            width: 88px;
            height: 26px;
            margin-left: 8px;
            border-radius: 20px;
            text-align: center;
            border: 1px solid #CA2250;
          }
        }
      }

      .label-text-card {
        width: 110px;
        height: 30px;
        background: #5B4481;
        opacity: 80%;
        border-radius: 16px;
        display: flex;
        justify-content: center;
        align-items: center;
        position: absolute;
        top: 12px;
        left: 12px;
        color: white;
        font-size: 14px;
        line-height: 14px;
        font-weight: 500;
      }

      .btn-shadow {
        width: 120px;
        height: 120px;
        border-radius: 0 20px 0 50px;
        text-align: center;
        background: white;
      }

      .btn {
        width: 80px;
        height: 80px;
        margin-left: 37px;
        border-radius: 24px;
        background: white;
        border: none;
        font-size: 40px;
        color: #CA2250;
        box-shadow: 0px 5px 10px 0px rgba(0, 0, 0, 0.5); 
      }
    }
  }
</style>