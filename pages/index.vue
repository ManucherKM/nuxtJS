<template>
  <div class="app">
    <div class="container">
      <ul class="app-list">
        <li class="app-list__element">
          <a href="#" class="element__link">Most popular</a>
        </li>
        <li class="app-list__element">
          <a href="#" class="element__link">New</a>
        </li>
      </ul>
      <div class="app__comment-parent">
        <div class="app__comment-container">
          <div class="app__comment-block">
            <div class="app__comment-nav">
              <div class="comment__block-name">
                <div class="block-name__img">
                  <img src="../assets/img/photo-user.png" alt="Photo" />
                </div>
                <div class="block-name__comment-name">
                  <div class="block-name__name block-name__title">John Smith</div>
                  <div class="block-name__time block-name__subtitle">Yesterday at 11:45 PM</div>
                </div>
              </div>
              <div class="comment-nav__grade">
                <img src="../assets/img/like.svg" alt="Photo" class="grade__img like">
                <img src="../assets/img/dislike.svg" alt="Photo" class="grade__img dislike">
                <img src="../assets/img/repost.svg" alt="Photo" class="grade__img repost">
              </div>
            </div>
            <div class="app__comment-body"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// vuedefa
export default {
  name: 'IndexPage'
}
</script>

<style lang="scss">
h1 {
  color: red;
}
</style>
