<template>
  <section class="hero is-fullheight">
    <div class="columns is-multiline">
      <div class="column is-one-quarter" v-for="item in orang">
        <div class="box">
            <figure class="image">
              <img src="../static/user.svg" alt="Image">
            </figure>
          <div class="card-content">
                <p class="title is-4">Sukijohn</p>
                <p class="subtitle is-6"><a>@johnsmith</a></p>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Suscipit, officia.
                </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
  .hero {
    padding-top: 2rem;
    max-width: 100%;
  }
  .columns {
    margin: 0;
  }
  @media (max-device-width: 768px) {
    .column {
      box-sizing: border-box;
      padding: 0px;
    }
  }
</style>
<script>
  export default {
    data: function () {
      return {
        orang: ['alo', 'bello', 'aloha', 'a', 'a']
      }
    }
  }

</script>
