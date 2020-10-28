<template>
  <div id="home">
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
    />

    <div>
      <b-modal id="info-modal" title="infoModal">
      <b-form inline>
    <label class="sr-only" for="inline-form-input-name">Name</label>
    <b-input
      id="inline-form-input-name"
      class="mb-2 mr-sm-2 mb-sm-0"
      placeholder="John Doe"
    ></b-input>

    <label class="sr-only" for="inline-form-input-number">mobile number</label>
    <b-input-group prepend="+91" class="mb-2 mr-sm-2 mb-sm-0">
      <b-input id="inline-form-input-username" placeholder="Mobile number"></b-input>
    </b-input-group>

    <b-form-checkbox class="mb-2 mr-sm-2 mb-sm-0">Remember me</b-form-checkbox>

    <b-button variant="primary">Save</b-button>
  </b-form>
      </b-modal>
    </div>

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
        <h3>TESTIMONIALS</h3>
        <carousel
          :perPageCustom="[
            [320, 1],
            [768, 2],
            [1199, 3],
          ]"
        >
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
              </b-card>
            </div>
          </slide>
        </carousel>
      </div>
    </div>
  </div>
</template>


<script>
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
import { Carousel, Slide } from "vue-carousel";

export default {
  data(){
    return{

    }
  },
  components: {
    Carousel,
    Slide,
    FontAwesomeIcon,
  },
  mounted() {
    setTimeout(()=>{
      this.$bvModal.show('info-modal');
    },1000);
  },
};
</script>

<style scoped>


.info {
  text-align: justify;
  position: relative;
  padding-top:3vh;
}

.testimonials {
  margin-top: 6vh;
}

.card{
  color:#000;
}
</style>