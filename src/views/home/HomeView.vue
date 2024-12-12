<template>
  <div class="landingpage--container">
    <Header />
    <main>
      <div class="vfgskfBC"></div>

      <div class="section">
        <div class="main--head--text--wrapper">
          <div class="head--text--innner">
            <div class="head--text--content">
              <h2>Proudly Launched on Base!</h2>
            </div>
            <div class="sub--head--text">
              <p>
                Unleash WaggyDog into the crypto wild—a token co-built for our
                loyal community! Together, we’ve created more than just a meme.
                WaggyDog is a blend of playful innovation and community
                strength, crafted to bring you rewards, laughs, and all the
                wagging you could ask for! 🌐💫 The pack has arrived, and the
                blockchain will never be the same. Are you ready to join the
                waggiest family on Base? 🐶💰
              </p>
            </div>
            <!-- <div class="main--head--button--wrapper">
              <button>Get started for free</button>
            </div> -->
          </div>
        </div>
      </div>

      <div class="ert43gh">
        <div class="gh3sdf">
          <div class="nh421sd">
            <div class="bghkasd2">
              <div width="360" class="left--image">
                <div class="left--image--wrapper">
                  <img
                    src="../../assets/images/dog1.jpg"
                    alt="AIDOGE"
                    class="main--left--image"
                  />
                </div>
              </div>
              <div width="100" class="bnhuiwd"></div>
              <div class="right--container">
                <h2 color="text" class="head-text">What is Waggy Dog?</h2>
                <div class="subtext top">
                  Waggy Dog is a community-driven meme coin that's all about
                  spreading joy, positivity, and a healthy dose of humor. Born
                  on the [Base Blockchain] blockchain, Waggy Dog aims to bring
                  people together through laughter and good vibes.
                </div>
                <h2 color="text" class="sub-head-text">
                  The Story Behind Waggy Dog
                </h2>
                <div class="subtext">
                  Waggy Dog is more than just a meme coin – it's a symbol of
                  community, friendship, and the power of humor. Our story began
                  with a simple idea: to create a cryptocurrency that would
                  bring people together and put a smile on their faces. And so,
                  Waggy Dog was born!
                </div>
                <div class="btn--wrap">
                  <a
                    target="_blank"
                    rel="noreferrer noopener"
                    class="info-btn"
                    href="/"
                    ><button class="kngWYa" scale="md">Buy Waggy</button>
                  </a>
                  <a
                    target="_blank"
                    rel="noreferrer noopener"
                    class="info-btn"
                    href="/"
                  >
                    <button class="jVaupd" scale="md">
                      View Docs
                      <svg
                        viewBox="0 0 12 12"
                        width="12"
                        xmlns="http://www.w3.org/2000/svg"
                        class="Svg"
                      >
                        <g stroke="none" stroke-width="1" fill-rule="evenodd">
                          <polygon
                            id="icon_link_2"
                            fill-rule="nonzero"
                            points="1.90530401 2.35495382 1.89425863 0 11.9528226 0.0471774476 12 10.1057414 9.64504618 10.094696 9.61637515 4.05511448 1.67301408 12 0 10.3269859 7.94286438 2.38362485"
                            style="fill: rgb(23, 243, 221)"
                          ></polygon>
                        </g>
                      </svg>
                    </button>
                  </a>
                </div>
              </div>
            </div>

            <div class="card-feature-section">
              <div class="feature-text">
                <h2>Key Features of Waggy Dog</h2>
              </div>
              <div class="card-container">
                <div class="card" v-for="(card, index) in cards" :key="index">
                  <h3 class="card-title">{{ card.title }}</h3>
                  <p class="card-subtext">{{ card.subtext }}</p>
                </div>
              </div>
            </div>

            <Piechart />

            <div class="nbhjder">
              <div type="secondary" width="720" class="box--inner">
                <div class="bhdr34s">
                  <h4 scale="xl" color="text" class="box-head-text">
                    Our Commitment.
                  </h4>
                  <div width="560" color="textSubtle" class="gbddf34">
                    By designing our tokenomics in this way, we aim to create a
                    stable and secure ecosystem that benefits all participants.
                  </div>
                  <div width="560" color="textSubtle" class="gbddf34">
                    Stay tuned for more updates on our tokenomics and ecosystem!
                  </div>
                </div>
                <div class="hju34a"></div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- <div class="siding--section">
        <div class="sliding--container">
          <div class="slide">
            <div class="slider-item-container">
              <div class="slider-item" style="--transform: none">
                <div height="138" width="320" class="slider--item--inner">
                  <div font-size="32px" color="text" class="slide-head-text">
                    210,000T
                  </div>
                  <div font-size="14px" color="text" class="slide-sub-text">
                    AIDOGE Total Supply
                  </div>
                </div>
              </div>
              <div class="slider-item" style="--transform: none">
                <div height="138" width="320" class="slider--item--inner">
                  <div font-size="32px" color="text" class="slide-head-text">
                    188,019T
                  </div>
                  <div font-size="14px" color="text" class="slide-sub-text">
                    AIDOGE Current Supply
                  </div>
                </div>
              </div>
              <div class="slider-item" style="--transform: none">
                <div height="138" width="320" class="slider--item--inner">
                  <div font-size="32px" color="text" class="slide-head-text">
                    21,981.4T
                  </div>
                  <div font-size="14px" color="text" class="slide-sub-text">
                    AIDOGE Total Burn
                  </div>
                </div>
              </div>
              <div class="slider-item" style="--transform: none">
                <div height="138" width="320" class="slider--item--inner">
                  <div font-size="32px" color="text" class="slide-head-text">
                    641,980T
                  </div>
                  <div font-size="14px" color="text" class="slide-sub-text">
                    AIDOGE Trading Volume
                  </div>
                </div>
              </div>
              <div class="slider-item" style="--transform: none">
                <div height="138" width="320" class="slider--item--inner">
                  <div font-size="32px" color="text" class="slide-head-text">
                    2.77567M
                  </div>
                  <div font-size="14px" color="text" class="slide-sub-text">
                    Lucky Drop Reward $ARB
                  </div>
                </div>
              </div>
              <div class="slider-item" style="--transform: none">
                <div height="138" width="320" class="slider--item--inner">
                  <div font-size="32px" color="text" class="slide-head-text">
                    2.08874M
                  </div>
                  <div font-size="14px" color="text" class="slide-sub-text">
                    AIDOGE Accumulated $ARB
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="slide">
            <div class="slider-item-container">
              <div class="slider-item" style="--transform: none">
                <div height="138" width="320" class="slider--item--inner">
                  <div font-size="32px" color="text" class="slide-head-text">
                    210,000T
                  </div>
                  <div font-size="14px" color="text" class="slide-sub-text">
                    AIDOGE Total Supply
                  </div>
                </div>
              </div>
              <div class="slider-item" style="--transform: none">
                <div height="138" width="320" class="slider--item--inner">
                  <div font-size="32px" color="text" class="slide-head-text">
                    188,019T
                  </div>
                  <div font-size="14px" color="text" class="slide-sub-text">
                    AIDOGE Current Supply
                  </div>
                </div>
              </div>
              <div class="slider-item" style="--transform: none">
                <div height="138" width="320" class="slider--item--inner">
                  <div font-size="32px" color="text" class="slide-head-text">
                    21,981.4T
                  </div>
                  <div font-size="14px" color="text" class="slide-sub-text">
                    AIDOGE Total Burn
                  </div>
                </div>
              </div>
              <div class="slider-item" style="--transform: none">
                <div height="138" width="320" class="slider--item--inner">
                  <div font-size="32px" color="text" class="slide-head-text">
                    641,980T
                  </div>
                  <div font-size="14px" color="text" class="slide-sub-text">
                    AIDOGE Trading Volume
                  </div>
                </div>
              </div>
              <div class="slider-item" style="--transform: none">
                <div height="138" width="320" class="slider--item--inner">
                  <div font-size="32px" color="text" class="slide-head-text">
                    2.77567M
                  </div>
                  <div font-size="14px" color="text" class="slide-sub-text">
                    Lucky Drop Reward $ARB
                  </div>
                </div>
              </div>
              <div class="slider-item" style="--transform: none">
                <div height="138" width="320" class="slider--item--inner">
                  <div font-size="32px" color="text" class="slide-head-text">
                    2.08874M
                  </div>
                  <div font-size="14px" color="text" class="slide-sub-text">
                    AIDOGE Accumulated $ARB
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div> -->

      <!-- <div class="cards--section">
        <Carousel
          wrap-around="true"
          :breakpoints="breakpoints"
          :autoplay="5000"
          :pause-autoplay-on-hover="true"
        >
          <Slide v-for="slide in slides" :key="slide.id">
            <a class="card-contain" :href="slide.link">
              <div type="primary" width="216" class="card-contain-inner">
                <div class="vgwer23">
                  <img :src="slide.image" :alt="slide.title" class="image" />
                </div>
                <div class="text-wrapper">
                  <div font-size="20px" color="text" class="head-bottom-text">
                    {{ slide.title }}
                  </div>
                  <div color="textSubtle" class="sub-text">
                    {{ slide.subtitle }}
                  </div>
                </div>
                <div class="background--image"></div>
              </div>
            </a>
          </Slide>

          <template #addons>
            <Navigation />
            <Pagination />
          </template>
        </Carousel>
      </div> -->

      <div class="roadmap">
        <Roadmap />
      </div>
      <div class="contact-section">
        <h2 scale="xl" color="text" class="contact-head">
          Waggy dog is a meme coin built on the Base blockchain, combining humor
          with utility in the crypto space. Inspired by the loyal and
          playful nature of dogs.
        </h2>
        <div class="social-media-wrap">
          <a
            target="_blank"
            rel="noreferrer noopener"
            margin="0 24px"
            class="media-icon-wrap"
            href="https://x.com/Waggydogz"
          >
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="white"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M18.79 2H15.6L12 7.9 8.35 2H5.2L10.53 10.3 4 20.8h3.24l5.04-8.2L17.3 22h3.27l-6.61-9.3L18.79 2Z"
              />
            </svg>
          </a>
         
          <a
            target="_blank"
            rel="noreferrer noopener"
            margin="0 24px"
            color="text"
            class="media-icon-wrap"
            href="https://t.me/waggydogz"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 240 240"
              width="48"
              height="48"
            >
              <path
                fill="#FFFFFF"
                d="M53.3 119.5l94.8-38.6c4.7-1.9 20.4-8.4 20.4-8.4 7.4-3 10.2.7 6.9 8.1 0 0-1.7 4.2-3.5 8.6l-32.6 77.5c-3.1 7.5-6.1 9.1-12.4 5.6l-17.4-13.1-8.4 8c-1 1-1.8 1.8-3.5 1.8l1.3-18.4 66.7-60.3c2.9-2.6 3.1-4.3 0-2.2L82 136l-16.5-5.2c-6.6-2.1-6.7-6.6 1.3-9.3z"
              />
            </svg>
          </a>
        </div>
      </div>
    </main>
    <!-- <Footer /> -->
  </div>
</template>

<script setup>
import Header from '@/components/header/Header.vue';
import Piechart from '@/components/piechart/Piechart.vue';
import Footer from '@/components/Footer.vue';
import Roadmap from '@/components/roadmap/index.vue';

import 'vue3-carousel/dist/carousel.css';
import { Carousel, Slide, Pagination, Navigation } from 'vue3-carousel';

const slides = [
  {
    id: '1',
    image: new URL('../../assets/images/dog01.jpg', import.meta.url).href,
    title: 'WAGGYDOG',
    subtitle: 'Get started',
    link: '/',
  },
  {
    id: '2',
    image: new URL('../../assets/images/dog1.jpg', import.meta.url).href,
    title: 'WAGGYDOG',
    subtitle: 'Get started',
    link: '/',
  },
  {
    id: '3',
    image: new URL('../../assets/images/dog2.jpg', import.meta.url).href,
    title: 'WAGGYDOG',
    subtitle: 'Get started',
    link: '/',
  },
  {
    id: '4',
    image: new URL('../../assets/images/dog3.jpg', import.meta.url).href,
    title: 'WAGGYDOG',
    subtitle: 'Get started',
    link: '/',
  },
];

const cards = [
  {
    title: 'Community-Driven',
    subtext:
      'Waggy Dog is all about community. We believe that cryptocurrency should be fun, accessible, and inclusive.',
  },
  {
    title: 'Meme-Based',
    subtext:
      'We Are not afraid to be a little silly. Waggy Dog is all about embracing the humor and creativity of the meme culture.',
  },
  {
    title: 'Decentralized',
    subtext:
      'Waggy Dog is built on the Base  blockchain, ensuring that our coin is decentralized, secure, and transparent',
  },
  {
    title: 'Limited Supply',
    subtext:
      'With a total supply of [1B], Waggy Dog is a rare and exclusive coin that Is sure to appreciate in value over time.',
  },
];

const breakpoints = {
  // 700px and up
  450: {
    itemsToShow: 2,
    snapAlign: 'center',
  },
  700: {
    itemsToShow: 3,
    snapAlign: 'center',
  },
  1024: {
    itemsToShow: 4,
    snapAlign: 'center',
  },
  // 1024 and up
  1200: {
    itemsToShow: 5,
    snapAlign: 'start',
  },
};
</script>

<style lang="sass" >
@use './home.scss'
</style>