<template>
  <div class="getintouch">
    <h3 class="caption">Get in Touch</h3>
    <h4>
      <a href="https://0gravity.xyz/programming-note/" target="_blank" rel="noopener noreferrer">
        Programming Note
      </a>
    </h4>
    <p>プログラミングについてのブログ</p>
    <h4>
      <!--<font-awesome-icon icon="fa-solid fa-github" />-->
      <font-awesome-icon :icon="['fab', 'github']" />
      <a href="https://github.com/0gravity000?tab=repositories" target="_blank" rel="noopener noreferrer">
        Github
      </a>
    </h4>
    <p>0gravityのリポジトリ</p>
    <h4>
      <font-awesome-icon :icon="['fab', 'youtube']" />
      <a href="https://www.youtube.com/channel/UC4C012-4CuQG7QptQcrfyfQ" target="_blank" rel="noopener noreferrer">
        Youtube
      </a>
    </h4>
    <p>Youtubeチャンネル 0gravity</p>
    <h4>
      <font-awesome-icon :icon="['fab', 'twitter']" />
      <a href="https://twitter.com/0gravity000" target="_blank" rel="noopener noreferrer">
        twitter
      </a>
    </h4>
    <p>twitter 0gravity</p>
  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3.caption {
  text-align: center;
}

</style>
