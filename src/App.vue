<template>
  <div id="app">
    <nav
      class="navbar is-primary"
      role="navigation"
      aria-label="main navigation"
    >
      <div class="navbar-brand">
        <div class="navbar-item">
          <h1 class="title is-4">JS Gugulable</h1>
        </div>
        <div class="navbar-item">
          <p>検索しにくい・ググれないJSの用語がわかるサービス</p>
        </div>
      </div>
    </nav>
    <div class="container">
      <div class="columns">
        <div class="column ">
          <div class="box">
            <div class="media">
              <div class="media-left">
                <figure class="image is-48x48">
                  <img
                    src="https://bulma.io/images/placeholders/96x96.png"
                    alt="Placeholder image"
                  />
                </figure>
              </div>
              <div class="media-content">
                <p class="title is-4">John Smith</p>
                <p class="subtitle is-6">@johnsmith</p>
              </div>
            </div>
          </div>
        </div>

        <div class="column">
          <div class="box">
            <div class="card">
              <div class="card-content">
                <div class="media">
                  <div class="media-left">
                    <figure class="image is-48x48">
                      <img
                        src="https://bulma.io/images/placeholders/96x96.png"
                        alt="Placeholder image"
                      />
                    </figure>
                  </div>
                  <div class="media-content">
                    <span class="subtitle is-6">@johnsmith</span>
                  </div>
                </div>
              </div>

              <div class="content">
                <table class="table-card">
                  <tbody>
                    <tr>
                      <td class="has-text-left">
                        <span class="subtitle is-6">@johnsmithleft</span>
                      </td>
                      <td class="has-text-right">
                        <span class="icon">
                          <i class="fas fa-home"></i>
                        </span>
                        <span class="subtitle is-6">@johnsmith</span>
                      </td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          お問い合わせはこちら
        </p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style lang="scss">
@import "../node_modules/bulma/bulma.sass";
.container {
  min-height: calc(100vh - 112px);
}
.footer {
  padding: 24px;
}
</style>
