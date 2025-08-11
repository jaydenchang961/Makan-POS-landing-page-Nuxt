<template>
  <div
    class="features2-layout302 thq-section-padding"
    v-bind:class="rootClassName"
  >
    <div class="features2-max-width thq-section-max-width">
      <div class="features2-section-title thq-flex-column">
        <span class="thq-body-small">
          <slot name="slogan">
            <!--Default content for slogan-->
            <div class="features2-fragment22">
              <span class="features2-text25">About Us</span>
            </div>
          </slot>
        </span>
        <h2 class="thq-heading-2 features2-text11">
          <slot name="sectionTitle">
            <!--Default content for sectionTitle-->
            <div class="features2-fragment10">
              <span class="features2-text13">
                Built on Experience, Designed for Simplicity
              </span>
            </div>
          </slot>
        </h2>
        <p class="features2-text12 thq-body-large">
          <slot name="sectionDescription">
            <!--Default content for sectionDescription-->
            <div class="features2-fragment14">
              <span class="features2-text17">
                Makan Smart POS isn&apos;t just another POS system. It&apos;s the
                result of ten years of listening to users like you. We&apos;ve
                meticulously refined our system based on real-world feedback,
                focusing relentlessly on making it powerful yet incredibly simple
                to operate. Our mission is to provide SMEs with tool that enhances
                efficiency, not complicates it.
              </span>
            </div>
          </slot>
        </p>
      </div>
      <div class="features2-content1">
        <div class="thq-grid-5">
          <div class="features2-feature1 thq-flex-column">
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              class="features2-icon10"
            >
              <g fill="none" fill-rule="evenodd">
                <path
                  d="M24 0v24H0V0zM12.594 23.258l-.012.002l-.071.035l-.02.004l-.014-.004l-.071-.036q-.016-.004-.024.006l-.004.01l-.017.428l.005.02l.01.013l.104.074l.015.004l.012-.004l.104-.074l.012-.016l.004-.017l-.017-.427q-.004-.016-.016-.018m.264-.113l-.014.002l-.184.093l-.01.01l-.003.011l.018.43l.005.012l.008.008l.201.092q.019.005.029-.008l.004-.014l-.034-.614q-.005-.019-.02-.022m-.715.002a.02.02 0 0 0-.027.006l-.006.014l-.034.614q.001.018.017.024l.015-.002l.201-.093l.01-.008l.003-.011l.018-.43l-.003-.012l-.01-.01z"
                ></path>
                <path
                  d="M16 2a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3zm-4 14a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m1.5-11h-3a1 1 0 0 0 0 2h3a1 1 0 1 0 0-2"
                  fill="currentColor"
                ></path>
              </g>
            </svg>
            <div class="features2-content2 thq-flex-column">
              <h3 class="features2-title11 thq-heading-3">
                <slot name="feature1Title">
                  <!--Default content for feature1Title-->
                  <div class="features2-fragment13">
                    <span class="features2-text16">Easy to Use Interface</span>
                  </div>
                </slot>
              </h3>
              <span class="features2-description11 thq-body-small">
                <slot name="feature1Description">
                  <!--Default content for feature1Description-->
                  <div class="features2-fragment19">
                    <span class="features2-text22">
                      Intuitive design that requires minimal training, allowing
                      your staff to start processing sales immediately.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="features2-feature2 thq-flex-column">
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              class="features2-icon14"
            >
              <g fill="currentColor">
                <rect x="16" y="3" rx="2" width="5" height="18"></rect>
                <rect x="9.5" y="9" rx="2" width="5" height="12"></rect>
                <rect x="3" y="16" rx="2" width="5" height="5"></rect>
              </g>
            </svg>
            <div class="features2-content3 thq-flex-column">
              <h3 class="features2-title12 thq-heading-3">
                <slot name="feature2Title">
                  <!--Default content for feature2Title-->
                  <div class="features2-fragment21">
                    <span class="features2-text24">Sales Reports</span>
                  </div>
                </slot>
              </h3>
            </div>
            <span class="features2-description12 thq-body-small">
              <slot name="feature2Description">
                <!--Default content for feature2Description-->
                <div class="features2-fragment11">
                  <span class="features2-text14">
                    Comprehensive analytics and reporting tools to track your
                    business performance in real-time.
                  </span>
                </div>
              </slot>
            </span>
          </div>
          <div class="features2-feature3 thq-flex-column">
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              class="features2-icon19"
            >
              <path
                d="m15.5 19.925l-4.25-4.25l1.4-1.4l2.85 2.85l5.65-5.65l1.4 1.4zM21 10h-2V5h-2v3H7V5H5v14h6v2H5q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h4.175q.275-.875 1.075-1.437T12 1q1 0 1.788.563T14.85 3H19q.825 0 1.413.588T21 5zm-9-5q.425 0 .713-.288T13 4t-.288-.712T12 3t-.712.288T11 4t.288.713T12 5"
                fill="currentColor"
              ></path>
            </svg>
            <div class="thq-flex-column">
              <h3 class="features2-title13 thq-heading-3">
                <slot name="feature3Title">
                  <!--Default content for feature3Title-->
                  <div class="features2-fragment18">
                    <span class="features2-text21">Inventory Tracking</span>
                  </div>
                </slot>
              </h3>
              <span class="features2-description13 thq-body-small">
                <slot name="feature3Description">
                  <!--Default content for feature3Description-->
                  <div class="features2-fragment12">
                    <span class="features2-text15">
                      Know what&apos;s in stock with real-time updates.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="features2-feature4 thq-flex-column">
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              class="features2-icon21"
            >
              <path
                d="M6 19a5 5 0 0 1-5-5a5 5 0 0 1 5-5c1-2.35 3.3-4 6-4c3.43 0 6.24 2.66 6.5 6.03L19 11a4 4 0 0 1 4 4a4 4 0 0 1-4 4zm13-6h-2v-1a5 5 0 0 0-5-5c-2.5 0-4.55 1.82-4.94 4.19C6.73 11.07 6.37 11 6 11a3 3 0 0 0-3 3a3 3 0 0 0 3 3h13a2 2 0 0 0 2-2a2 2 0 0 0-2-2"
                fill="currentColor"
              ></path>
            </svg>
            <div class="features2-content5 thq-flex-column">
              <h3 class="features2-title14 thq-heading-3">
                <slot name="feature4Title">
                  <!--Default content for feature4Title-->
                  <div class="features2-fragment17">
                    <span class="features2-text20">Cloud-Based</span>
                  </div>
                </slot>
              </h3>
              <span class="features2-description14 thq-body-small">
                <slot name="feature4Description">
                  <!--Default content for feature4Description-->
                  <div class="features2-fragment15">
                    <span class="features2-text18">
                      Access your business data anywhere, anytime with secure
                      cloud storage and automatic backups.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
          <div class="features2-feature5 thq-flex-column">
            <svg
              width="32"
              height="32"
              viewBox="0 0 32 32"
              class="features2-icon23"
            >
              <path
                d="m25 14l-2.1-1c-1.7-.8-2.9-2.6-2.9-4.5V2h10v6.5c0 1.9-1.1 3.7-2.9 4.5zM22 4v4.5c0 1.2.7 2.2 1.7 2.7l1.3.6l1.3-.6c1-.5 1.7-1.6 1.7-2.7V4z"
                fill="currentColor"
              ></path>
              <path
                d="M28 16v6H4V6h12V4H4c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h8v4H8v2h16v-2h-4v-4h8c1.1 0 2-.9 2-2v-6zM18 28h-4v-4h4z"
                fill="currentColor"
              ></path>
            </svg>
            <div class="features2-content6 thq-flex-column">
              <h3 class="features2-title15 thq-heading-3">
                <slot name="feature5Title">
                  <!--Default content for feature5Title-->
                  <div class="features2-fragment16">
                    <span class="features2-text19">Secure System</span>
                  </div>
                </slot>
              </h3>
              <span class="features2-description15 thq-body-small">
                <slot name="feature5Description">
                  <!--Default content for feature5Description-->
                  <div class="features2-fragment20">
                    <span class="features2-text23">
                      Enterprise-level security measures to protect your business
                      and customer data.
                    </span>
                  </div>
                </slot>
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Features2',
  props: {
    rootClassName: String,
  },
}
</script>

<style scoped>
.features2-layout302 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.features2-max-width {
  gap: var(--dl-layout-space-threeunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.features2-section-title {
  align-items: flex-start;
  padding-right: 509px;
}
 
.features2-text12 {
  width: 892px;
}
 
.features2-content1 {
  gap: var(--dl-layout-space-threeunits);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.features2-feature1 {
  align-items: flex-start;
}
 
.features2-icon10 {
  fill: var(--dl-color-theme-neutral-dark);
  color: #fa6447;
}
 
.features2-content2 {
  align-self: flex-start;
}
 
.features2-title11 {
  gap: var(--dl-layout-space-unit);
  width: 249px;
  height: 75px;
  display: flex;
  padding-right: 5px;
}
 
.features2-description11 {
  display: grid;
  place-items: center;
}
 
.features2-feature2 {
  align-items: flex-start;
}
 
.features2-icon14 {
  fill: var(--dl-color-theme-neutral-dark);
  color: #fa6447;
}
 
.features2-content3 {
  width: 174px;
  align-items: center;
  justify-content: center;
}
 
.features2-title12 {
  gap: var(--dl-layout-space-unit);
  width: 163px;
  display: flex;
  text-align: left;
  padding-right: 5px;
}
 
.features2-description12 {
  width: 182px;
  height: 129px;
  display: grid;
}
 
.features2-feature3 {
  align-items: flex-start;
}
 
.features2-icon19 {
  fill: var(--dl-color-theme-neutral-dark);
  color: #fa6447;
}
 
.features2-title13 {
  gap: var(--dl-layout-space-unit);
  width: 243px;
  height: 83px;
  display: flex;
}
 
.features2-description13 {
  height: 76px;
  display: grid;
  place-items: center;
}
 
.features2-feature4 {
  align-items: flex-start;
}
 
.features2-icon21 {
  fill: var(--dl-color-theme-neutral-dark);
  color: #fa6447;
}
 
.features2-content5 {
  align-self: flex-start;
}
 
.features2-title14 {
  gap: var(--dl-layout-space-unit);
  width: 179px;
  display: flex;
  align-self: flex-start;
}
 
.features2-description14 {
  height: 125px;
  display: grid;
  place-items: center;
}
 
.features2-feature5 {
  align-items: flex-start;
}
 
.features2-icon23 {
  fill: var(--dl-color-theme-neutral-dark);
  color: #fa6447;
}
 
.features2-content6 {
  width: 182px;
  display: flex;
}
 
.features2-title15 {
  gap: var(--dl-layout-space-unit);
  width: 100%;
  display: flex;
  align-self: flex-start;
}
 
.features2-description15 {
  height: 108px;
  display: grid;
  place-items: center;
}
 
.features2-fragment10 {
  display: contents;
}
 
.features2-text13 {
  color: #bf4407;
  display: inline-block;
}
 
.features2-fragment11 {
  display: contents;
}
 
.features2-text14 {
  display: inline-block;
}
 
.features2-fragment12 {
  display: contents;
}
 
.features2-text15 {
  display: inline-block;
}
 
.features2-fragment13 {
  display: contents;
}
 
.features2-text16 {
  display: inline-block;
  text-align: left;
}
 
.features2-fragment14 {
  display: contents;
}
 
.features2-text17 {
  display: inline-block;
}
 
.features2-fragment15 {
  display: contents;
}
 
.features2-text18 {
  display: inline-block;
}
 
.features2-fragment16 {
  display: contents;
}
 
.features2-text19 {
  display: inline-block;
}
 
.features2-fragment17 {
  display: contents;
}
 
.features2-text20 {
  display: inline-block;
}
 
.features2-fragment18 {
  display: contents;
}
 
.features2-text21 {
  display: inline-block;
}
 
.features2-fragment19 {
  display: contents;
}
 
.features2-text22 {
  display: inline-block;
}
 
.features2-fragment20 {
  display: contents;
}
 
.features2-text23 {
  display: inline-block;
}
 
.features2-fragment21 {
  display: contents;
}
 
.features2-text24 {
  display: inline-block;
}
 
.features2-fragment22 {
  display: contents;
}
 
.features2-text25 {
  display: inline-block;
}
 
.features2root-class-name {
  background-color: #f9c270;
}
 
@media(max-width: 1200px) {
  .features2-title13 {
    width: 200px;
  }
  .features2root-class-name {
    background-color: #f9c270;
  }
}
 
@media(max-width: 767px) {
  .features2-text12 {
    width: 680px;
  }
}
 
@media(max-width: 479px) {
  .features2-max-width {
    gap: var(--dl-layout-space-oneandhalfunits);
  }
  .features2-section-title {
    width: 479px;
    margin-right: 0px;
  }
  .features2-text11 {
    width: 396px;
    margin-right: 205px;
  }
  .features2-text12 {
    width: 440px;
    height: 217px;
    margin-right: 0px;
  }
}
</style>
