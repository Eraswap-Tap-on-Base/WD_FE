<template>
  <footer class="footer">
    <div class="footer-content">
      <!-- Logo and description section -->
      <div class="footer-left">
        <a href="/" class="footer-logo">
          <div class="logo--wrapper">
            <img
              src="../assets/images/newwaggy.jpg"
              alt="logo"
              class="logo-image"
            />
          </div>
        </a>
        <p class="footer-description">
          ArbDogeAI, an Experiment in the Arbitrum Ecosystem.
        </p>
      </div>

      <!-- Navigation section -->
      <div class="footer-right">
        <div class="footer-nav">
          <!-- Resources -->
          <div class="nav-column">
            <h4>Resources</h4>
            <ul>
              <li><a href="/documentation">Documentation</a></li>
              <li><a href="/community">Community</a></li>
              <li><a href="/support">Support</a></li>
            </ul>
          </div>

          <!-- Product -->
          <div class="nav-column">
            <h4>Product</h4>
            <ul>
              <li><a href="/features">Features</a></li>
              <li><a href="/pricing">Pricing</a></li>
              <li><a href="/faqs">FAQs</a></li>
            </ul>
          </div>

          <!-- Press -->
          <div class="nav-column">
            <h4>Press</h4>
            <ul>
              <li><a href="/blog">Blog</a></li>
              <li><a href="/news">News</a></li>
              <li><a href="/media-kit">Media Kit</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <!-- Divider and bottom text -->
    <hr class="footer-divider" />
    <p class="footer-bottom-text">© 2024 ArbDogeAI. All rights reserved.</p>
  </footer>
</template>

<style scoped lang="scss">
.footer {
  padding: 2rem;
  background-color: transparent;
  text-align: center;
  max-width: 960px;
  padding-top: 28px;
  margin: auto;

  .footer-content {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: start;

    .footer-left {
      width: 50%;
      text-align: left;
      .logo--wrapper {
        width: 60px;
        height: 60px;
      }
      .footer-logo {
        display: inline-block;
      }

      .logo-image {
        width: 100%;
        height: 100%;
        border-radius: 50%;
        object-fit: cover;
      }

      .footer-description {
        color: rgb(103, 115, 149);
        font-weight: 400;
        line-height: 1.5;
        font-family: 'Manrope';
        margin-top: 20px;
        font-size: 14px;
      }
    }

    .footer-right {
      width: 50%;
      display: flex;
      justify-content: space-between;

      .footer-nav {
        display: flex;
        justify-content: space-between;
        flex: 1;

        .nav-column {
          h4 {
            color: rgb(255, 255, 255);
            font-size: 16px;
            font-weight: 400;
            line-height: 1.5;
            font-family: 'Manrope';
            text-align: left;
          }

          ul {
            list-style: none;
            padding: 0;
            display: flex;
            flex-direction: column;
            text-align: left;

            li {
              margin-bottom: 0.25rem;

              a {
                color: rgb(103, 115, 149);
                font-size: 14px;
                font-weight: 400;
                line-height: 1.5;
                font-family: 'Manrope';
                white-space: nowrap;
                overflow: hidden;
                text-overflow: ellipsis;
                margin-top: 24px;
                &:hover {
                  color: rgb(23, 243, 221);
                  text-decoration: none;
                }
              }
            }
          }
        }
      }
    }
  }

  .footer-divider {
    margin: 1.5rem 0;
    border: none;
    border-top: 1px solid #ddd;
  }

  .footer-bottom-text {
    font-size: 14px;
    color: #6c757d;
  }

  @media (max-width: 600px) {
    .footer-content {
      flex-direction: column;
      text-align: center;

      .footer-left,
      .footer-right {
        width: 100%;
      }
    }

    .footer-nav {
      flex-direction: column;
      align-items: center;
      margin-top: 20px;
      align-items: flex-start;
    }
    .nav-column {
      margin-top: 25px;
    }
  }
}
</style>
