<template>
  <div class="features22-layout302 thq-section-padding">
    <div class="features22-max-width thq-section-max-width">
      <div class="features22-section-title thq-flex-column">
        <span class="thq-body-small">
          <slot name="slogan">
            <!--Default content for slogan-->
            <div class="features22-fragment18">
              <span class="features22-text21">Slogan</span>
            </div>
          </slot>
        </span>
        <h2 class="thq-heading-2">
          <slot name="sectionTitle">
            <!--Default content for sectionTitle-->
            <div class="features22-fragment21">
              <span class="features22-text24">Key Features</span>
            </div>
          </slot>
        </h2>
        <p class="thq-body-large">
          <slot name="sectionDescription">
            <!--Default content for sectionDescription-->
            <div class="features22-fragment13">
              <span class="features22-text16">
                Discover the powerful features that make Makan Smart POS the
                perfect solution for your business.
              </span>
            </div>
          </slot>
        </p>
      </div>
      <div class="features22-content1">
        <div class="thq-grid-5">
          <div class="features22-feature1 thq-flex-column">
            <img
              :alt="feature1ImageAlt"
              :src="feature1ImageSrc"
              class="thq-team-image-round"
            />
            <div class="thq-flex-column">
              <h3 class="thq-heading-3">
                <slot name="feature1Title">
                  <!--Default content for feature1Title-->
                  <div class="features22-fragment22">
                    <span class="features22-text25">Admin Portal</span>
                  </div>
                </slot>
              </h3>
              <span class="thq-body-small">
                <slot name="feature1Description">
                  <!--Default content for feature1Description-->
                  <div class="features22-fragment12">
                    <span class="features22-text15">
                      Manage your business operations efficiently with our
                      intuitive admin portal.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="features22-feature2 thq-flex-column">
            <img
              :alt="feature2ImageAlt"
              :src="feature2ImageSrc"
              class="thq-team-image-round"
            />
            <div class="thq-flex-column">
              <h3 class="thq-heading-3">
                <slot name="feature2Title">
                  <!--Default content for feature2Title-->
                  <div class="features22-fragment16">
                    <span class="features22-text19">Efficient Cashiering</span>
                  </div>
                </slot>
              </h3>
              <span class="thq-body-small">
                <slot name="feature2Description">
                  <!--Default content for feature2Description-->
                  <div class="features22-fragment23">
                    <span class="features22-text26">
                      Streamline your checkout process and serve customers faster
                      with our efficient cashiering system.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="features22-feature3 thq-flex-column">
            <img
              :alt="feature3ImageAlt"
              :src="feature3ImageSrc"
              class="thq-team-image-round"
            />
            <div class="thq-flex-column">
              <h3 class="thq-heading-3">
                <slot name="feature3Title">
                  <!--Default content for feature3Title-->
                  <div class="features22-fragment10">
                    <span class="features22-text13">
                      Seamless QR Scan Ordering
                    </span>
                  </div>
                </slot>
              </h3>
              <span class="thq-body-small">
                <slot name="feature3Description">
                  <!--Default content for feature3Description-->
                  <div class="features22-fragment17">
                    <span class="features22-text20">
                      Enable customers to place orders easily by scanning QR codes
                      for a seamless ordering experience.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="features22-feature4 thq-flex-column">
            <img
              :alt="feature4ImageAlt"
              :src="feature4ImageSrc"
              class="thq-team-image-round"
            />
            <div class="thq-flex-column">
              <h3 class="thq-heading-3">
                <slot name="feature4Title">
                  <!--Default content for feature4Title-->
                  <div class="features22-fragment20">
                    <span class="features22-text23">Comprehensive Analytics</span>
                  </div>
                </slot>
              </h3>
              <span class="thq-body-small">
                <slot name="feature4Description">
                  <!--Default content for feature4Description-->
                  <div class="features22-fragment14">
                    <span class="features22-text17">
                      Gain valuable insights into your business performance with
                      comprehensive analytics and reporting tools.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="features22-feature5 thq-flex-column">
            <img
              :alt="feature5ImageAlt"
              :src="feature5ImageSrc"
              class="thq-team-image-round"
            />
            <div class="thq-flex-column">
              <h3 class="thq-heading-3">
                <slot name="feature5Title">
                  <!--Default content for feature5Title-->
                  <div class="features22-fragment19">
                    <span class="features22-text22">Inventory Tracking</span>
                  </div>
                </slot>
              </h3>
              <span class="thq-body-small">
                <slot name="feature5Description">
                  <!--Default content for feature5Description-->
                  <div class="features22-fragment24">
                    <span class="features22-text27">
                      Keep track of your inventory levels in real-time to optimize
                      stock management and reduce wastage.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
        </div>
        <div class="features22-actions">
          <button class="thq-button-filled features22-button1">
            <span class="thq-body-small">
              <slot name="mainAction">
                <!--Default content for mainAction-->
                <div class="features22-fragment15">
                  <span class="features22-text18">Main action</span>
                </div>
              </slot>
            </span>
          </button>
          <button class="thq-button-outline features22-button2">
            <span class="thq-body-small">
              <slot name="secondaryAction">
                <!--Default content for secondaryAction-->
                <div class="features22-fragment11">
                  <span class="features22-text14">Secondary action</span>
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
  name: 'Features22',
  props: {
    feature4ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1570294034809-48e058c2b0ea?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1NDcxNTk3MHw&ixlib=rb-4.1.0&q=80&w=1080',
    },
    feature4ImageAlt: {
      type: String,
      default: 'Analytics Image',
    },
    feature1ImageAlt: {
      type: String,
      default: 'Admin Portal Image',
    },
    feature2ImageAlt: {
      type: String,
      default: 'Efficient Cashiering Image',
    },
    feature5ImageAlt: {
      type: String,
      default: 'Inventory Tracking Image',
    },
    feature3ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1633307057722-a4740ba0c5d0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1NDcxNTk3Mnw&ixlib=rb-4.1.0&q=80&w=1080',
    },
    feature3ImageAlt: {
      type: String,
      default: 'QR Scan Ordering Image',
    },
    feature1ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1634777132153-15322f198aff?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1NDcxNTk3MXw&ixlib=rb-4.1.0&q=80&w=1080',
    },
    feature2ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1562327699-e48794711fe9?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1NDcxNTk3MXw&ixlib=rb-4.1.0&q=80&w=1080',
    },
    feature5ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1561538165-411322e90881?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1NDcxNTk3MHw&ixlib=rb-4.1.0&q=80&w=1080',
    },
  },
}
</script>

<style scoped>
.features22-layout302 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.features22-max-width {
  gap: var(--dl-layout-space-threeunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.features22-section-title {
  align-items: flex-start;
}
 
.features22-content1 {
  gap: var(--dl-layout-space-threeunits);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.features22-feature1 {
  align-items: flex-start;
}
 
.features22-feature2 {
  align-items: flex-start;
}
 
.features22-feature3 {
  align-items: flex-start;
}
 
.features22-feature4 {
  align-items: flex-start;
}
 
.features22-feature5 {
  align-items: flex-start;
}
 
.features22-actions {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-unit);
  padding-left: 0px;
  padding-right: 0px;
  padding-bottom: 0px;
}
 
.features22-fragment10 {
  display: contents;
}
 
.features22-text13 {
  display: inline-block;
}
 
.features22-fragment11 {
  display: contents;
}
 
.features22-text14 {
  display: inline-block;
}
 
.features22-fragment12 {
  display: contents;
}
 
.features22-text15 {
  display: inline-block;
}
 
.features22-fragment13 {
  display: contents;
}
 
.features22-text16 {
  display: inline-block;
}
 
.features22-fragment14 {
  display: contents;
}
 
.features22-text17 {
  display: inline-block;
}
 
.features22-fragment15 {
  display: contents;
}
 
.features22-text18 {
  display: inline-block;
}
 
.features22-fragment16 {
  display: contents;
}
 
.features22-text19 {
  display: inline-block;
}
 
.features22-fragment17 {
  display: contents;
}
 
.features22-text20 {
  display: inline-block;
}
 
.features22-fragment18 {
  display: contents;
}
 
.features22-text21 {
  display: inline-block;
}
 
.features22-fragment19 {
  display: contents;
}
 
.features22-text22 {
  display: inline-block;
}
 
.features22-fragment20 {
  display: contents;
}
 
.features22-text23 {
  display: inline-block;
}
 
.features22-fragment21 {
  display: contents;
}
 
.features22-text24 {
  display: inline-block;
}
 
.features22-fragment22 {
  display: contents;
}
 
.features22-text25 {
  display: inline-block;
}
 
.features22-fragment23 {
  display: contents;
}
 
.features22-text26 {
  display: inline-block;
}
 
.features22-fragment24 {
  display: contents;
}
 
.features22-text27 {
  display: inline-block;
}
 
@media(max-width: 479px) {
  .features22-max-width {
    gap: var(--dl-layout-space-oneandhalfunits);
  }
  .features22-actions {
    width: 100%;
    flex-direction: column;
  }
  .features22-button1 {
    width: 100%;
  }
  .features22-button2 {
    width: 100%;
  }
}
</style>
