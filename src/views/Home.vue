<template>
  <div class="home container-fluid">
    <div class="row">
      <div class="col-4 col-md-2 sidebar">
        <div
          class="nav flex-column nav-pills"
          id="v-pills-tab"
          role="tablist"
          aria-orientation="vertical"
        >
          <a
            class="nav-link active"
            id="v-pills-welcome-tab"
            data-toggle="pill"
            href="#v-pills-welcome"
            role="tab"
            aria-controls="v-pills-welcome"
            aria-selected="true"
            >Welcome</a
          >
          <a
            class="nav-link"
            id="v-pills-contact-tab"
            data-toggle="pill"
            href="#v-pills-contact"
            role="tab"
            aria-controls="v-pills-contact"
            aria-selected="false"
            >Contact Us</a
          >
          <a
            class="nav-link"
            id="v-pills-location-tab"
            data-toggle="pill"
            href="#v-pills-location"
            role="tab"
            aria-controls="v-pills-location"
            aria-selected="false"
            >Location</a
          >
          <a
            class="nav-link"
            id="v-pills-faqs-tab"
            data-toggle="pill"
            href="#v-pills-faqs"
            role="tab"
            aria-controls="v-pills-faqs"
            aria-selected="false"
            >F.A.Q's</a
          >
        </div>
      </div>
      <div class="col-8 col-md-10 content">
        <div class="tab-content" id="v-pills-tabContent">
          <div
            class="tab-pane fade show active"
            id="v-pills-welcome"
            role="tabpanel"
            aria-labelledby="v-pills-welcome-tab"
          >
            <span
              ><img
                src="../assets/horizonexit.png"
                class="rounded bannerimg"
                alt=""
            /></span>
            <br>
            <br>
Sky Down Skydiving is the place to make your next skydive near Boise. Located in Caldwell, Idaho Skydown Skydiving offers a wide range of options for each potential jumper. Would you like to make that once in a lifetime tandem jump; or are you interested in earning your license through our solo jumper training program?
<br><br>
A tandem skydive is the most popular way for people to experience the thrill of freefall and the serenity of a parachute ride with the least amount of training.  On a tandem skydive, you are attached to the front of a USPA rated tandem instructor during the entire freefall and parachute ride.  Your instructor controls the jump, so you are free to experience the sensations of flying while enjoying the breathtaking view of the valley.
<br><br>
Sky Down Skydiving is the only dropzone in the area that is open 7 days a week and through the winter as long as the weather permits jumping, we don't shut down. Contact us today!
          </div>
          <div
            class="tab-pane fade"
            id="v-pills-contact"
            role="tabpanel"
            aria-labelledby="v-pills-contact-tab"
          >
            Phone:(208)455-2359
            <br>
Email: jumpskydown@gmail.com
<br>
Address: 5111 Aviation Way, Caldwell, ID 83605

          </div>
          <div
            class="tab-pane fade"
            id="v-pills-location"
            role="tabpanel"
            aria-labelledby="v-pills-location-tab"
          >
          <span><img src="../assets/streetview.png" class="bannerimg col rounded" alt=""></span>
          <br>
          <h3>Driving directions from Boise (20 minutes)
</h3>
<h6>Head west on I-84 toward Caldwell.
  <br>
Take exit 29 for Franklin Rd.
<br>
Turn right onto Franklin Rd.
<br>
At the first stop light, turn right onto Aviation Way.
<br>
Drive 2 miles and watch for us on the left.</h6>
          <div class="align-items-end justify-content-around d-flex">
          <a href="http://maps.apple.com/?daddr=Sky+Down+Skydiving,+5111+Aviation+Way,+Caldwell,+ID+83605" target="_blank"><img src="../assets/applemaps.png" height="64" width="64" alt=""></a>
          <a href="https://www.google.com/maps/dir/43.6391301,-116.570314/Sky+Down+Skydiving,+5111+Aviation+Way,+Caldwell,+ID+83605" target="_blank"><img src="../assets/googlemaps.png" height="64" width="64" alt=""></a>
          </div>
          </div>
          <div
            class="tab-pane fade"
            id="v-pills-faqs"
            role="tabpanel"
            aria-labelledby="v-pills-faqs-tab"
          >
            Frequently Asked Questions

How many jumps do I have to do before going solo?

While a tandem is a great way to make your first skydive it is not required. You can sign up for a 4-6 hour class and make your first jump after the class. For more information on the static line class and the process of getting your skydiving license please visit the Learn to Skydive page.

How long will I need to be at the dropzone for my tandem jump?

Generally tandem jumpers should plan on being at the dropzone for about 2 hours from the time the arrive.

What should I wear?

We recommend wearing clothes that are appropriate for the time of the year and weather that day. We also provide jumpsuits for tandem jumpers to wear. Tennis shoes are the best shoes to wear. DO NOT wear boots or shoes with a heel.

How old do I need to be to skydive?

Sky Down Skydiving is a member of the United States Parachute Association, USPA, and all jumpers must be at least 18 years old.

Is there a weight limit?

We will accommodate every jumper we can, but jumpers over 220lbs must call for current pricing.

How experienced are your instructors?

All of our tandem instructors are USPA certified instructors. USPA requires all tandem instructors to have at least 500 jumps. Currently most of our instructors have between 1,000 and 16,000 jumps.

What kind of airplane does the Sky Down Skydiving operate?

Sky Down Skydiving normally operates a Cessna 182. We have two Cessna 182s and during special events we also use a twin engine Cessna 402.

Where do the skydivers land?

We have a grass landing area directly behind our hangar. Friends, family, and any other spectators are welcome to come watch. We have plenty of picnic tables and chairs to accompany your whole group.

How many jumps do you do per day?

We have multiple instructors and each instructor can comfortably perform at least 10 jumps per day.
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: "home",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {},
};
</script>


<style scoped>
/* #region SIDBAR CSS */
.nav-pills a.active {
  background-color: #ff8a00;
}
.sidebar {
  position: -webkit-sticky;
  position: sticky;
  top: 4rem;
  z-index: 1000;
  height: calc(100vh - 4rem);
}
::-webkit-scrollbar {
  width: 15px;
  height: 15px;
}
::-webkit-scrollbar-thumb {
  background: #ff8a00;
  border-radius: 7px;
}
::-webkit-scrollbar-thumb:hover {
  background: #eb8305;
}
::-webkit-scrollbar-track {
  background: #f0f0f000;
  border-radius: 7px;
  box-shadow: inset 0px 0px 0px 0px #f0f0f0;
}
/* #endregion */

/* #region CONTENT CSS */
.content {
  max-height: calc(100vh - 4rem);
  overflow: scroll;
  overflow-x: hidden;
}
.bannerimg {
  -webkit-mask-image: -webkit-gradient(
    linear,
    left top,
    left bottom,
    from(rgba(0, 0, 0, 1)),
    to(rgba(0, 0, 0, 0))
  );
  mask-image: linear-gradient(to bottom, rgba(0, 0, 0, 1), rgba(0, 0, 0, 0));
  max-width: -webkit-fill-available;
}
/* #endregion */
</style>