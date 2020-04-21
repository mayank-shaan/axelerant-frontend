<template>
  <section class="world-map-container text-left">
      <div class="container">
        <div class="description">
          <h1>Mauris id bibendum est.Proin dapibus sollicitudin iaculis, Maecanaus condimentum maximus laoreet</h1>
          <p>
            In maximus euismod egestas. Fusce tincidunt posuere est non ele Lorem ipsum dolor sit amet,
            consectetur adipiscing elit. Donec dignissim diam finibus dictum fringilla. Aenean vel diam
            libero. Mauris blandit congue sollicitudin. Fusce tincidunt posuere est non ele Lorem ipsum dolor sit amet.
            Donec dignissim diam finibus dictum fringilla. Aenean vel diam libero. Mauris blandit congue sollicitudin. Fusce tincidunt posuere est non ele Lorem ipsum dolor sit amet
          </p>
        </div>
        <div class="map-wrapper">
          <img src="@/assets/images/social-world.png" alt="world-map">
        </div>
      </div>
    </section>
</template>

<script>

export default {
  name: 'WorldMap',
};

</script>

<style lang="scss">
.world-map-container {
  padding: 40px 0;

  .description {
    margin-bottom: 30px;

    h1 {
      color: #484340;
      font-size: 22px;
    }

    p {
      color: #484340;
      font-size: 16px;

      line-height: 1.3;

    }
  }
}
@media (min-width: 991px) {
  .world-map-container {
    padding: 90px 0 70px;
    .container {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    .description {
      width: 50%;
      h1 {
        font-size: 37px;
        line-height: 1.1;
        p {
          font-size: 18px;
        }
      }
    }
    .map-wrapper {
      width: 40%;
    }
  }
}

@media (min-width: 768px) {
.world-map-container {
    padding: 60px 0;
    .container {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    .description {
      width: 50%;
      h1 {
        font-size: 40px;
        line-height: 1.1;
        p {
          font-size: 18px !important;
        }
      }
    }
    .map-wrapper {
      width: 40%;
    }
  }
}
</style>
