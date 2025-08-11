<template>
  <div class="features21-layout302 thq-section-padding">
    <div class="features21-max-width thq-section-max-width">
      <div class="features21-section-title thq-flex-column">
        <span class="thq-body-small">
          <slot name="slogan">
            <!--Default content for slogan-->
            <div class="features21-fragment10">
              <span class="features21-text13">Slogan</span>
            </div>
          </slot>
        </span>
        <h2 class="thq-heading-2">
          <slot name="sectionTitle">
            <!--Default content for sectionTitle-->
            <div class="features21-fragment14">
              <span class="features21-text17">Key Features</span>
            </div>
          </slot>
        </h2>
        <p class="thq-body-large">
          <slot name="sectionDescription">
            <!--Default content for sectionDescription-->
            <div class="features21-fragment13">
              <span class="features21-text16">
                Discover the powerful features that make Makan Smart POS the
                perfect choice for your business.
              </span>
            </div>
          </slot>
        </p>
      </div>
      <div class="features21-content1">
        <div class="thq-grid-5">
          <div class="features21-feature1 thq-flex-column">
            <img
              :alt="feature1ImageAlt"
              :src="feature1ImageSrc"
              class="thq-team-image-round"
            />
            <div class="thq-flex-column">
              <h3 class="features21-title11 thq-heading-3">
                <slot name="feature1Title">
                  <!--Default content for feature1Title-->
                  <div class="features21-fragment16">
                    <span class="features21-text19">Admin Portal</span>
                  </div>
                </slot>
              </h3>
              <span class="thq-body-small">
                <slot name="feature1Description">
                  <!--Default content for feature1Description-->
                  <div class="features21-fragment23">
                    <span class="features21-text26">
                      Manage your business with ease through our intuitive admin
                      portal.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="features21-feature2 thq-flex-column">
            <img
              :alt="feature2ImageAlt"
              :src="feature2ImageSrc"
              class="thq-team-image-round"
            />
            <div class="thq-flex-column">
              <h3 class="thq-heading-3">
                <slot name="feature2Title">
                  <!--Default content for feature2Title-->
                  <div class="features21-fragment18">
                    <span class="features21-text21">Efficient Cashiering</span>
                  </div>
                </slot>
              </h3>
              <span class="thq-body-small">
                <slot name="feature2Description">
                  <!--Default content for feature2Description-->
                  <div class="features21-fragment24">
                    <span class="features21-text27">
                      Speed up transactions and streamline your checkout process
                      for improved customer satisfaction.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="features21-feature3 thq-flex-column">
            <img
              :alt="feature3ImageAlt"
              :src="feature3ImageSrc"
              class="thq-team-image-round"
            />
            <div class="thq-flex-column">
              <h3 class="thq-heading-3">
                <slot name="feature3Title">
                  <!--Default content for feature3Title-->
                  <div class="features21-fragment11">
                    <span class="features21-text14">
                      Seamless QR Scan Ordering
                    </span>
                  </div>
                </slot>
              </h3>
              <span class="thq-body-small">
                <slot name="feature3Description">
                  <!--Default content for feature3Description-->
                  <div class="features21-fragment22">
                    <span class="features21-text25">
                      Allow customers to place orders conveniently by scanning QR
                      codes for a seamless ordering experience.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="features21-feature4 thq-flex-column">
            <img
              :alt="feature4ImageAlt"
              :src="feature4ImageSrc"
              class="thq-team-image-round"
            />
            <div class="thq-flex-column">
              <h3 class="thq-heading-3">
                <slot name="feature4Title">
                  <!--Default content for feature4Title-->
                  <div class="features21-fragment17">
                    <span class="features21-text20">Comprehensive Analytics</span>
                  </div>
                </slot>
              </h3>
              <span class="thq-body-small">
                <slot name="feature4Description">
                  <!--Default content for feature4Description-->
                  <div class="features21-fragment19">
                    <span class="features21-text22">
                      Gain valuable insights into your business performance with
                      detailed analytics and reporting tools.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="features21-feature5 thq-flex-column">
            <img
              :alt="feature5ImageAlt"
              :src="feature5ImageSrc"
              class="thq-team-image-round"
            />
            <div class="thq-flex-column">
              <h3 class="thq-heading-3">
                <slot name="feature5Title">
                  <!--Default content for feature5Title-->
                  <div class="features21-fragment21">
                    <span class="features21-text24">Inventory Tracking</span>
                  </div>
                </slot>
              </h3>
              <span class="thq-body-small">
                <slot name="feature5Description">
                  <!--Default content for feature5Description-->
                  <div class="features21-fragment15">
                    <span class="features21-text18">
                      Keep track of your inventory in real-time to optimize stock
                      levels and prevent shortages.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
        </div>
        <div class="features21-actions">
          <button class="thq-button-filled features21-button1">
            <span class="thq-body-small">
              <slot name="mainAction">
                <!--Default content for mainAction-->
                <div class="features21-fragment20">
                  <span class="features21-text23">Main action</span>
                </div>
              </slot>
            </span>
          </button>
          <button class="thq-button-outline features21-button2">
            <span class="thq-body-small">
              <slot name="secondaryAction">
                <!--Default content for secondaryAction-->
                <div class="features21-fragment12">
                  <span class="features21-text15">Secondary action</span>
                </div>
              </slot>
            </span>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Features21',
  props: {
    feature2ImageAlt: {
      type: String,
      default: 'Efficient Cashiering Image',
    },
    feature3ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1550999280-b8a04844e8e7?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1NDcxNTgxNXw&ixlib=rb-4.1.0&q=80&w=1080',
    },
    feature5ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1633307057722-a4740ba0c5d0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1NDcxNTgxM3w&ixlib=rb-4.1.0&q=80&w=1080',
    },
    feature4ImageAlt: {
      type: String,
      default: 'Comprehensive Analytics Image',
    },
    feature1ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1624638299925-6966fac6914f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1NDcxNTgxNHw&ixlib=rb-4.1.0&q=80&w=1080',
    },
    feature1ImageAlt: {
      type: String,
      default: 'Admin Portal Image',
    },
    feature5ImageAlt: {
      type: String,
      default: 'Inventory Tracking Image',
    },
    feature4ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1440407876336-62333a6f010f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1NDcxNTgxM3w&ixlib=rb-4.1.0&q=80&w=1080',
    },
    feature2ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1538105891735-5ec7eadd8aa7?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1NDcxNTgxNHw&ixlib=rb-4.1.0&q=80&w=1080',
    },
    feature3ImageAlt: {
      type: String,
      default: 'QR Scan Ordering Image',
    },
  },
}
</script>

<style scoped>
.features21-layout302 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.features21-max-width {
  gap: var(--dl-layout-space-threeunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.features21-section-title {
  align-items: flex-start;
}
 
.features21-content1 {
  gap: var(--dl-layout-space-threeunits);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.features21-feature1 {
  align-items: flex-start;
}
 
.features21-title11 {
  width: 203px;
  height: 44px;
}
 
.features21-feature2 {
  align-items: flex-start;
}
 
.features21-feature3 {
  align-items: flex-start;
}
 
.features21-feature4 {
  align-items: flex-start;
}
 
.features21-feature5 {
  align-items: flex-start;
}
 
.features21-actions {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-unit);
  padding-left: 0px;
  padding-right: 0px;
  padding-bottom: 0px;
}
 
.features21-fragment10 {
  display: contents;
}
 
.features21-text13 {
  display: inline-block;
}
 
.features21-fragment11 {
  display: contents;
}
 
.features21-text14 {
  display: inline-block;
}
 
.features21-fragment12 {
  display: contents;
}
 
.features21-text15 {
  display: inline-block;
}
 
.features21-fragment13 {
  display: contents;
}
 
.features21-text16 {
  display: inline-block;
}
 
.features21-fragment14 {
  display: contents;
}
 
.features21-text17 {
  display: inline-block;
}
 
.features21-fragment15 {
  display: contents;
}
 
.features21-text18 {
  display: inline-block;
}
 
.features21-fragment16 {
  display: contents;
}
 
.features21-text19 {
  display: inline-block;
}
 
.features21-fragment17 {
  display: contents;
}
 
.features21-text20 {
  display: inline-block;
}
 
.features21-fragment18 {
  display: contents;
}
 
.features21-text21 {
  display: inline-block;
}
 
.features21-fragment19 {
  display: contents;
}
 
.features21-text22 {
  display: inline-block;
}
 
.features21-fragment20 {
  display: contents;
}
 
.features21-text23 {
  display: inline-block;
}
 
.features21-fragment21 {
  display: contents;
}
 
.features21-text24 {
  display: inline-block;
}
 
.features21-fragment22 {
  display: contents;
}
 
.features21-text25 {
  display: inline-block;
}
 
.features21-fragment23 {
  display: contents;
}
 
.features21-text26 {
  display: inline-block;
}
 
.features21-fragment24 {
  display: contents;
}
 
.features21-text27 {
  display: inline-block;
}
 
@media(max-width: 479px) {
  .features21-max-width {
    gap: var(--dl-layout-space-oneandhalfunits);
  }
  .features21-actions {
    width: 100%;
    flex-direction: column;
  }
  .features21-button1 {
    width: 100%;
  }
  .features21-button2 {
    width: 100%;
  }
}
</style>
