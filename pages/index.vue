<template>
  <div>
    <Navbar />

    <Header id="top" />

    <!-- The basics are -->
    <div class="section bg-white" id="how-it-works">
      <div class="container">
        <h1 class="text-center">The basics are</h1>
        <p class="text-center mb-5"></p>
        <div class="row">
          <div class="col-sm-4 item">
            <img src="/img/basics-1.png" class="mb-3" />
            <h3>Share your talent, culture, DIY projects, and passion with the community.</h3>
            <p class="mt-3">Getting to know your social behaviour, you norms and the way of life of your people is what we care to help show to the world.</p>
          </div>
          <div class="col-sm-4 item">
            <img src="/img/basics-2.png" class="mb-3" />
            <h3>Get your work curated by people who are interested in what you share.</h3>
            <p class="mt-3">Lots of people appreciate the beauty of good work. Someone somewhere is waiting to vote your excellent idea.</p>
          </div>
          <div class="col-sm-4 item">
            <img src="/img/basics-3.png" class="mb-3" />
            <h3>Earn reward in Steem.</h3>
            <p class="mt-3">Rewards will be awarded in steem token, a cryptocurrency that can be exchanged to any currency with immediate effect.</p>
          </div>
        </div>
      </div>
    </div>

    <!-- We value your creative talents -->
    <div class="section">
      <div class="container">
        <h1 class="text-center">We value your creative talents</h1>
        <p class="text-center mb-5"></p>
        <div class="row">
          <div class="col-sm-4 item">
            <div style="height: 100px" class="d-flex justify-content-center">
              <img src="/img/icons/value.svg" />
            </div>
            <h3>We value the things you are passionate about.</h3>
            <p class="mt-3">Yes we truly do. Passion is the genesis of genius. By showing the society your inate ability to add value to life through the things you are good at, we hold your skills in high esteem.</p>
          </div>
          <div class="col-sm-4 item">
            <div style="height: 100px" class="d-flex justify-content-center">
              <img src="/img/icons/invest.svg" />
            </div>
            <h3>We want you to invest your time in your passion.</h3>
            <p class="mt-3">You can make good use of our platform to achieve your dream. That itch about what you love doing can be made time for and scratched. Feel the power that comes from focusing on what excites you.</p>
          </div>
          <div class="col-sm-4 item">
            <div style="height: 100px" class="d-flex justify-content-center">
              <img src="/img/icons/people.svg" />
            </div>
            <h3>We want to let people know what you have to offer</h3>
            <p class="mt-3">Dont isolate your talent, show the world what you are good at, do it with conviction and get noticed.</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Who can contribute? What is steem? -->
    <div class="section bg-white contribute">
      <div class="container">
        <div class="row">
          <div class="col-lg-6 order-lg-2">
            <img src="/img/contribute.png" class="img-fluid mb-5 mb-lg-0" alt="" />
          </div>
          <div class="col-lg-6 d-flex flex-column order-lg-1">
            <h1 class="mb-4">Who can contribute?</h1>
            <div class="d-flex">
              <div class="bluedot"><div></div></div>
              <div>Are you creative? Are you passionate about it? <b>KnackSteem is for you.</b></div>
            </div>
            <div class="d-flex">
              <div class="bluedot"><div></div></div>
              <div>Anyone/everyone from all over the world can share their creativity (culture, talents, DIY projects, and so much more)</div>
            </div>
            <div class="mt-3">
              <a href="https://steemit.com/knacksteem/@knacksteem.org/introducing-knacksteem-a-platform-where-you-can-share-the-things-you-are-passionate-about" class="btn btn-lg btn-primary mt-3">Read more</a>
            </div>
          </div>
        </div>

        <div class="row mt-5 pt-5">
          <div class="col-lg-6">
            <img src="/img/whatissteem.png" class="img-fluid mb-5 mb-lg-0" alt="" />
          </div>
          <div class="col-lg-6 d-flex flex-column">
            <h1 class="mb-4">What is steem?</h1>
            <p>
              To pay the contributor’s rewards, Knacksteem will utilize the Steem blockchain. This means the money generated would be in the form of a cryptocurrency called STEEM, which is the token of the steem blockchain. This is done through community voting. Nobody has to pay for the rewards directly. They are generated and distributed using an algorithm called Proof-of-Brain, which encourages people to create and curate quality content.
            </p>
            <div class="mt-3">
              <a href="https://steem.io/" class="btn btn-lg btn-primary mt-3">Read more</a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Categories -->
    <div class="section" id="categories">
      <div class="container">
        <h1 class="text-center mb-5">Categories</h1>
        <p class="text-center mb-5">We have a variety of categories and sub-categories which you can contribute to, according to your area of expertise.</p>
        <div class="row">
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card mb-4">
              <img src="/img/icons/diy.svg" class="mb-3" />
              <h3>DIY</h3>
              <p>Show the world how to fix things themselves and get rewarded.</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card mb-4">
              <img src="/img/icons/art.svg" class="mb-3" />
              <h3>ART</h3>
              <p>Art is creative visual expression. Show the world your skills and wow everyone.</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card mb-4">
              <img src="/img/icons/altruism.svg" class="mb-3" />
              <h3>ALTRUISM</h3>
              <p>Create a better world by showing love to people you care about. Show it off.</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card mb-4">
              <img src="/img/icons/fashion.svg" class="mb-3" />
              <h3>DOCUMENTARY</h3>
              <p>Share your findings with the greater world and earn some rewards</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card mb-4">
              <img src="/img/icons/trend.svg" class="mb-3" />
              <h3>TECH TRENDS</h3>
              <p>Share your reviews and valuable opinion with the people that matter.</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card mb-4">
              <img src="/img/icons/music.svg" class="mb-3" />
              <h3>MUSIC</h3>
              <p>Share your musical talent directly with your audience, and get rewarded.</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card mb-4">
              <img src="/img/icons/joke.svg" class="mb-3" />
              <h3>JOKES and HUMOR</h3>
              <p>Smart enough to get even the saddest to laugh? Show it off</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card mb-4">
              <img src="/img/icons/gaming.svg" class="mb-3" />
              <h3>GAMING</h3>
              <p>Your experience in gaming is welcome. Play, win and share the fun through your review.</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Our Team / Sponsors -->
    <div class="section bg-white" id="team">
      <div class="container">
        <h1 class="text-center">Our Team</h1>
        <p class="text-center mb-5">Meet our dedicated team of moderator and supervisor. They ensure quality content on this platform</p>
        <div class="row">
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card flat mb-4">
              <div class="avatar" style="background-image: url('https://steemitimages.com/u/ms10398/avatar')"></div>
              <h3>ms10398 (AKA Rebel)</h3>
              <p>Dev instructor</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card flat mb-4">
              <div class="avatar" style="background-image: url('https://steemitimages.com/u/radudangratian/avatar')"></div>
              <h3>radudangratian</h3>
              <p>custodian/graphics designer</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card flat mb-4">
              <div class="avatar" style="background-image: url('https://steemitimages.com/u/tykee/avatar')"></div>
              <h3>tykee</h3>
              <p>supervisor</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card flat mb-4">
              <div class="avatar" style="background-image: url('https://steemitimages.com/u/ckole/avatar')"></div>
              <h3>ckole</h3>
              <p>marven</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card flat mb-4">
              <div class="avatar" style="background-image: url('https://steemitimages.com/u/darewealth/avatar')"></div>
              <h3>darewealth</h3>
              <p>marven</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card flat mb-4">
              <div class="avatar" style="background-image: url('https://steemitimages.com/u/luschn/avatar')"></div>
              <h3>luschn</h3>
              <p>Front-end dev</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card flat mb-4">
              <div class="avatar" style="background-image: url('https://steemitimages.com/u/jaysermendez/avatar')"></div>
              <h3>jaysermendez</h3>
              <p>Back-end dev</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <div class="card flat mb-4">
              <div class="avatar" style="background-image: url('https://steemitimages.com/u/outwork/avatar')"></div>
              <h3>outwork</h3>
              <p>UI/UX design</p>
            </div>
          </div>
        </div>

        <h1 class="text-center mt-5">Sponsors</h1>
        <p class="text-center mb-5">Our sponsors (delegators) are eligible for 12% of the initial 15% beneficiary reward. The reward is directly proportional to the share of all Steem Power (SP) delegated.</p>
        <div class="row">
          <div class="col-sm-6 col-md-4">
            <div class="card flat mb-4">
              <div class="avatar" style="background-image: url('https://steemitimages.com/u/ms10398/avatar')"></div>
              <h3>ms10398 (AKA Rebel)</h3>
              <p>Dev instructor</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4">
            <div class="card flat mb-4">
              <div class="avatar" style="background-image: url('https://steemitimages.com/u/radudangratian/avatar')"></div>
              <h3>radudangratian</h3>
              <p>custodian/graphics designer</p>
            </div>
          </div>
          <div class="col-sm-6 col-md-4">
            <div class="card flat mb-4">
              <div class="avatar" style="background-image: url('https://steemitimages.com/u/tykee/avatar')"></div>
              <h3>tykee</h3>
              <p>supervisor</p>
            </div>
          </div>
        </div>
        <div class="d-flex justify-content-center align-items-center flex-column flex-sm-row">
          <span>Do you like what we do?</span>
          <a href="https://steembottracker.com/delegation.html?delegatee=knacksteem.org" class="btn btn-lg btn-primary mt-3 mt-sm-0 ml-sm-3">Become a sponsor</a>
        </div>
      </div>
    </div>

    <Footer />
  </div>
</template>

<script>
  import Navbar from '~/components/Navbar'
  import Header from '~/components/Header'
  import Footer from '~/components/Footer'

  export default {
    head: {
      bodyAttrs: {
        'data-spy': 'scroll',
        'data-target': '#navbar',
        'data-offset': '100'
      }
    },
    components: {
      Navbar,
      Header,
      Footer
    },
    mounted () {
      // load steem account data via steemconnect
      this.$store.dispatch('login')
    }
  }
</script>
