<template>
  <div v-for="item in myworkItems" :key="item.id">
    <div class="card">
      <div class="card-body">
        <h4 class="card-title">
          <a :href="item.link" class="card-link" target="_blank" rel="noopener noreferrer">{{ item.title }}</a>
        </h4>
        <h5 class="card-subtitle mb-2 text-muted">{{ item.skill }}</h5>
        <p class="card-text">{{ item.overview }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainContentItem',
  data() {
    return {
      myworkItems: [
        {
          id: 1,
          title: "Kabuboard",
          link: "https://kabuboard2.0gravity0.com/",
          skill: "PHP/Laravel/MySQL",
          overview: "Yahooファイナンスをスクレイピングし株価を表示などするWebサイト"
        },
        {
          id: 2,
          title: "Resume",
          link: "https://resume-0gravity.an.r.appspot.com/",
          skill: "vue.js+JavaScript/Flask+python/GCP(GAE+Datastore)",
          overview: "履歴書の作成支援Webサイト"
        },
        {
          id: 6,
          title: "Video Libraly",
          link: "https://videolibrary.0gravity0.com/",
          skill: "Laravel+PHP/MySQL",
          overview: "Amazon Prime Videoをスクレイピングして表示するWebサイト"
        },
        {
          id: 7,
          title: "Game Libraly",
          link: "https://gamelibrary.0gravity0.com/",
          skill: "Laravel+PHP/MySQL/Youtube API",
          overview: "Youtube APIを使って、ゲーム動画を表示するWebサイト"
        },
        {
          id: 4,
          title: "Rails チュートリアル Sample app",
          link: "https://thawing-cliffs-92135.herokuapp.com/",
          skill: "Ruby on Rails/Postgres/SQLite3",
          overview: "Ruby on Rails チュートリアル Sample app"
        },
        {
          id: 3,
          title: "BitCode",
          link: "https://bitcode.0gravity0.com/",
          skill: "Laravel+PHP/Vue.js+JavaScript/MySQL",
          overview: "コードのスニペットを投稿、閲覧できるWebアプリ"
        },
        {
          id: 5,
          title: "DVD Rental",
          link: "https://dvdrental.0gravity0.com/",
          skill: "Laravel+PHP/MySQL",
          overview: "DVD Rentalデモサイト"
        },
        {
          id: 8,
          title: "Nuxt.js Demoサイト",
          link: "https://nuxtdemo.0gravity0.com/",
          skill: "Nuxt.js+Vue.js+JavaScript",
          overview: "Nuxt.js+Vue.jsの実験サイトその2"
        },
        {
          id: 9,
          title: "Nuxt.jsデモサイト",
          link: "https://vuejsdemo.0gravity0.com/",
          skill: "Nuxt.js+Vue.js+JavaScript",
          overview: "Nuxt.js+Vue.jsの実験サイトその1"
        },
        {
          id: 10,
          title: "Memoサイト",
          link: "https://memoapp-nuxt.0gravity0.com/memo/",
          skill: "Nuxt.js+Vue.js+JavaScript",
          overview: "簡易Memo登録Webサイト"
        },
        {
          id: 11,
          title: "DB Device",
          link: "https://dbdevice.0gravity0.com/",
          skill: "Laravel+PHP/MySQL",
          overview: "スマホ一覧を表示するWebサイト"
        },
        {
          id: 12,
          title: "数値文字参照 Convert",
          link: "http://convertnumchr.0gravity0.com/",
          skill: "HTML+JavaScript",
          overview: "数値文字参照を文字に変換するサイト"
        },
        {
          id: 13,
          title: "TaskManeger",
          link: "https://taskmaneger.0gravity0.com/",
          skill: "Laravel+PHP/Vue.js+Javascript",
          overview: "タスク管理アプリ。axios使用し、非同期API通信をする"
        },
        {
          id: 14,
          title: "Sites",
          link: "https://sites.0gravity0.com/",
          skill: "HTML/CSS",
          overview: "静的なWebサイトのサンプル集。実験や動作確認など"
        },
        {
          id: 15,
          title: "カフェ1",
          link: "https://sites.0gravity0.com/sample01/index.html",
          skill: "HTML/CSS",
          overview: "カフェのサンプルサイト"
        },
        {
          id: 16,
          title: "文房具購入サイト",
          link: "https://sites.0gravity0.com/sample02/index.html",
          skill: "Vue.js+Javescript",
          overview: "文房具購入デモサイト"
        },
      ]
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
