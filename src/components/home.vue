<template>
  <div id="home">
    <div class="info container">
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec
        odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla
        quis sem at nibh elementum imperdiet. Duis sagittis ipsum. Praesent
        mauris. Fusce nec tellus sed augue semper porta. Mauris massa.
        Vestibulum lacinia arcu eget nulla. Class aptent taciti sociosqu ad
        litora torquent per conubia nostra, per inceptos himenaeos. Curabitur
        sodales ligula in libero. Sed dignissim lacinia nunc.
      </p>
      <p>
        Curabitur tortor. Pellentesque nibh. Aenean quam. In scelerisque sem at
        dolor. Maecenas mattis. Sed convallis tristique sem. Proin ut ligula vel
        nunc egestas porttitor. Morbi lectus risus, iaculis vel, suscipit quis,
        luctus non, massa. Fusce ac turpis quis ligula lacinia aliquet. Mauris
        ipsum. Nulla metus metus, ullamcorper vel, tincidunt sed, euismod in,
        nibh. Quisque volutpat condimentum velit. Class aptent taciti sociosqu
        ad litora torquent per conubia nostra, per inceptos himenaeos.
      </p>

      <div class="testimonials">
        <carousel :perPageCustom="[[320, 1], [768, 2], [1199, 3]]">
          <slide>
            <div>
              <b-card
                title="Card Title"
                img-src="https://picsum.photos/600/300/?image=25"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem"
                class="mb-2"
              >
                <b-card-text>
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </b-card-text>

                <b-button href="#" variant="primary">Go somewhere</b-button>
              </b-card>
            </div>
          </slide>

          <slide>
            <div>
              <b-card
                title="Card Title"
                img-src="https://placekitten.com/600/300"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem"
                class="mb-2"
              >
                <b-card-text>
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </b-card-text>

                <b-button href="#" variant="primary">Go somewhere</b-button>
              </b-card>
            </div>
          </slide>

          <slide>
            <div>
              <b-card
                title="Card Title"
                img-src="https://picsum.photos/600/300/?image=25"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem"
                class="mb-2"
              >
                <b-card-text>
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </b-card-text>

                <b-button href="#" variant="primary">Go somewhere</b-button>
              </b-card>
            </div>
          </slide>

          <slide>
            <div>
              <b-card
                title="Card Title"
                img-src="https://placekitten.com/600/300"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem"
                class="mb-2"
              >
                <b-card-text>
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </b-card-text>

                <b-button href="#" variant="primary">Go somewhere</b-button>
              </b-card>
            </div>
          </slide>
        </carousel>
      </div>
    </div>
  </div>
</template>

<script>
import { Carousel, Slide } from "vue-carousel";
export default {
  components: {
    Carousel,
    Slide,
  },
};
</script>

<style scoped>
.info {
  margin-top: 3vh;
  text-align: justify;
}

.testimonials {
  margin-top: 5vh;
}
</style>