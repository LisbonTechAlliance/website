<template>
  <section id="conversation">
    <div class="wrap container-fluid">
      <div class="row">
        <div class="col-xs-12 content-wrapper">
          <h2
            v-sticky
            :z-index="100"
            :sticky-top="100"
            class="section-title"
          >
            <div>
              Junta-te à conversa
            </div>
          </h2>

          <div class="social">
            <a
              href="https://github.com/LisbonTechLeague"
              title="GitHub"
            >
              <i class="fa fa-github fa-2x" />
            </a>
          </div>

          <div class="row">
            <div class="col-xs-12 col-sm-6 col">
              <div class="section-content section-content-center">
                <p>Convidamos todos a juntarem-se ao nosso grupo, juntem-se à conversa com as comunidades de</p>

                <p>
                  <a href="https://discord.gg/2xyDrH4">
                    <img
                      src="/images/discord.png"
                      alt="Discord"
                    >
                  </a>
                </p>

                <p>
                  <a
                    href="https://discord.gg/2xyDrH4"
                    class="btn"
                  >
                    Pede o teu convite aqui
                  </a>
                </p>
              </div>
            </div>
            <div class="col-xs-12 col-sm-6 col">
              <a
                class="twitter-timeline"
                data-theme="light"
                data-height="400"
                data-width="400"
                data-border-color="#e84a5f"
                data-chrome="nofooter"
                href="https://twitter.com/GDGLisbon/lists/lisbon-tech-communities"
              >
                Tweets das comunidades em Lisboa
              </a>
              <script
                async
                src="https://platform.twitter.com/widgets.js"
                charset="utf-8" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'ConversationSection'
  }
</script>
