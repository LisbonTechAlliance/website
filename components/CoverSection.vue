<template>
  <section id="cover">
    <div class="wrap container-fluid">
      <div class="row">
        <div class="col-xs-12 content-wrapper">
          <div class="content">
            <h1>
              Lisbon Tech
            </h1>

            <h2>
              Comunidades de Lisboa que promovem os mesmos valores de partilha
            </h2>

            <no-ssr>
              <VigotechNextEvent
                v-if="nextEvents"
                :next-events="nextEvents"
              />
            </no-ssr>

            <div class="down-wrapper">
              <a
                v-scroll-to="'#grupos'"
                href="#"
                class="down"
              >
                <i class="fa fa-chevron-down" />
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
  import VigotechNextEvent from "./VigotechNextEvent";
  export default {
    name: 'CoverSection',
    components: {
      VigotechNextEvent
    },
    props: {
      nextEvents: {
        type: [Array],
        required: false,
        default: () => {return []}
      }
    }
  }
</script>
