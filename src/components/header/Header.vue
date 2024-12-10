<template>
  <header>
    <div class="vfgskfBC"></div>
    <div class="header-wrapper">
      <div class="header--inner-wrapper">
        <div class="fgrr23zx">
          <!-- left -->
          <div>
            <a class="logo-wrapper" href="/">
              <div width="174"  class="logo--wrapper__inner">
                <div class="sdewedf">
                  <img
                    src="../../assets/images/wagggylgo.png"
                    alt="logo"
                    class="logo-image"
                  />
                </div>
                <!-- <div class="logo-text">
                  WAGGYDOG
                </div> -->
              </div>
            </a>
          </div>

          <!-- middle -->
          <div class="nav-link-container">
            <div class="nav-link-wrapper">
              <a class="nav-link-item" href="/"> Home </a>
            </div>
            <div class="nav-link-wrapper">
              <a class="nav-link-item" href="/"> Staking </a>
            </div>
            <!-- <div class="nav-link-wrapper">
              <a class="nav-link-item" href="/"> AICODE </a>
            </div> -->
            <div class="nav-link-wrapper">
              <div class="nav-link-dropdown">
                <a class="nav-link-item" href="/">
                  <div class="nav-link-dropdown_inner">
                    NFT
                    <!-- <svg viewBox="0 0 24 24" width="22" class="svg">
                      <path
                        d="M8.11997 9.29006L12 13.1701L15.88 9.29006C16.27 8.90006 16.9 8.90006 17.29 9.29006C17.68 9.68006 17.68 10.3101 17.29 10.7001L12.7 15.2901C12.31 15.6801 11.68 15.6801 11.29 15.2901L6.69997 10.7001C6.30997 10.3101 6.30997 9.68006 6.69997 9.29006C7.08997 8.91006 7.72997 8.90006 8.11997 9.29006Z"
                      ></path>
                    </svg> -->
                  </div>
                </a>
              </div>
            </div>
            <div class="nav-link-wrapper">
              <a
                target="_blank"
                rel="noreferrer noopener"
                class="nav-link-item"
                href="/"
              >
                Waggy.fun
              </a>
            </div>
          </div>

          <!-- right -->
          <div class="button-wrapper">
            <button class="main-button" style="font-size: 14px">
            BUY
            </button>
            <div class="hamburger--wrapper" @click="toggleSidebar">
              <!-- <svg width="24" height="24" viewBox="0 0 24 24" fill="white">
                <rect y="1" width="24" height="3" />
                <rect y="8" width="24" height="3" />
                <rect y="15" width="24" height="3" />
              </svg> -->
              <div class="ham-div"></div>
              <div class="ham-div"></div>
              <div class="ham-div"></div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Sidebar -->
    <div v-if="isSidebarOpen" class="sidebar-overlay" @click="closeSidebar">
      <div class="sidebar" @click.stop>
        <a color="text" class="kjdgerds" href="/">
          <div
            width="174"
            height="48"
            class="bhgsu43"
            style="
              display: block;
              transition: opacity 0.3s 0.4s, transform 0.3s 0.4s;
              opacity: 1;
              margin: 16px 32px;
              transform: translate3d(0px, 0px, 0px);
            "
          >
            <div class="nbuu342">
              <img
                src="../../assets/images/logo.svg"
                alt="logo"
                class="image"
              />
            </div>
          </div>
        </a>
        <div class="huw34sd"></div>
        <nav>
          <div
            class="b87axc"
            style="
              display: block;
              transition: opacity 0.3s 0.4s, transform 0.3s 0.4s;
              opacity: 1;
              transform: translate3d(0px, 0px, 0px);
            "
          >
            <a bold="true" class="hyyuer34" href="/" style="padding: 16px 32px"
              >Home</a
            >
          </div>

          <div
            class="b87axc"
            style="
              display: block;
              transition: opacity 0.3s 0.4s, transform 0.3s 0.4s;
              opacity: 1;
              transform: translate3d(0px, 0px, 0px);
            "
          >
            <a bold="true" class="hyyuer34" href="/" style="padding: 16px 32px"
              >Vault</a
            >
          </div>

          <div
            class="b87axc"
            style="
              display: block;
              transition: opacity 0.3s 0.4s, transform 0.3s 0.4s;
              opacity: 1;
              transform: translate3d(0px, 0px, 0px);
            "
          >
            <a bold="true" class="hyyuer34" href="/" style="padding: 16px 32px"
              >AICODE
            </a>
          </div>

          <div
            class="b87axc"
            style="
              display: block;
              transition: opacity 0.3s 0.4s, transform 0.3s 0.4s;
              opacity: 1;
              transform: translate3d(0px, 0px, 0px);
            "
          >
            <a bold="true" class="hyyuer34" href="/" style="padding: 16px 32px"
              >NFT</a
            >
          </div>

          <div
            class="b87axc"
            style="
              display: block;
              transition: opacity 0.3s 0.4s, transform 0.3s 0.4s;
              opacity: 1;
              transform: translate3d(0px, 0px, 0px);
            "
          >
            <a bold="true" class="hyyuer34" href="/" style="padding: 16px 32px"
              >Launchpad</a
            >
          </div>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      isSidebarOpen: false,
    };
  },
  methods: {
    toggleSidebar() {
      this.isSidebarOpen = !this.isSidebarOpen;
    },
    closeSidebar() {
      this.isSidebarOpen = false;
    },
  },
};
</script>

<style lang="sass" scoped>
@use './header.scss'
</style>
