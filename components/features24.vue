<template>
  <div class="thq-section-padding">
    <div class="features24-container2 thq-section-max-width">
      <div class="features24-image-container">
        <video
          :src="videoSrc"
          muted="true"
          poster="https://play.teleporthq.io/static/svg/videoposter.svg"
          autoplay="true"
          class="features24-video"
        ></video>
      </div>
      <div class="features24-tabs-menu">
        <div @click="activeTab = 0" class="features24-tab-horizontal1">
          <div class="features24-divider-container1">
            <div v-if="activeTab = 0" class="features24-container3"></div>
          </div>
          <div class="features24-content1">
            <h2 class="thq-heading-2">
              <slot name="feature1Title">
                <!--Default content for feature1Title-->
                <div class="features24-fragment3">
                  <span class="features24-text3">Admin Portal</span>
                </div>
              </slot>
            </h2>
            <span class="thq-body-small">
              <slot name="feature1Description">
                <!--Default content for feature1Description-->
                <div class="features24-fragment6">
                  <span class="features24-text6">
                    Manage your POS system with ease through the admin portal
                  </span>
                </div>
              </slot>
            </span>
          </div>
        </div>
        <div @click="activeTab = 1" class="features24-tab-horizontal2">
          <div class="features24-divider-container2">
            <div v-if="activeTab = 1" class="features24-container4"></div>
          </div>
          <div class="features24-content2">
            <h2 class="thq-heading-2">
              <slot name="feature2Title">
                <!--Default content for feature2Title-->
                <div class="features24-fragment5">
                  <span class="features24-text5">Cashiering</span>
                </div>
              </slot>
            </h2>
            <span class="thq-body-small">
              <slot name="feature2Description">
                <!--Default content for feature2Description-->
                <div class="features24-fragment2">
                  <span class="features24-text2">
                    Streamlined cashiering process for quick transactions
                  </span>
                </div>
              </slot>
            </span>
          </div>
        </div>
        <div @click="activeTab = 2" class="features24-tab-horizontal3">
          <div class="features24-divider-container3">
            <div v-if="activeTab = 2" class="features24-container5"></div>
          </div>
          <div class="features24-content3">
            <h2 class="thq-heading-2">
              <slot name="feature3Title">
                <!--Default content for feature3Title-->
                <div class="features24-fragment1">
                  <span class="features24-text1">QR Scan Ordering</span>
                </div>
              </slot>
            </h2>
            <span class="thq-body-small">
              <slot name="feature3Description">
                <!--Default content for feature3Description-->
                <div class="features24-fragment4">
                  <span class="features24-text4">
                    Efficient QR scan ordering system for customers
                  </span>
                </div>
              </slot>
            </span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Features24',
  props: {
    videoSrc: String,
  },
  data() {
    return {
      activeTab: 0,
    }
  },
}
</script>

<style scoped>
.features24-container2 {
  width: 100%;
  display: grid;
  grid-gap: var(--dl-layout-space-fiveunits);
  position: relative;
  grid-template-columns: 1fr 1fr;
}
 
.features24-image-container {
  height: 100%;
  display: flex;
  position: relative;
}
 
.features24-video {
  width: 415px;
  height: 329px;
}
 
.features24-tabs-menu {
  gap: var(--dl-layout-space-twounits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
 
.features24-tab-horizontal1 {
  gap: var(--dl-layout-space-twounits);
  cursor: pointer;
  display: flex;
  overflow: hidden;
  align-self: stretch;
  align-items: flex-start;
  flex-shrink: 0;
}
 
.features24-divider-container1 {
  display: flex;
  align-self: stretch;
  align-items: flex-start;
}
 
.features24-container3 {
  width: 2px;
  align-self: stretch;
  background-color: var(--dl-color-theme-neutral-dark);
}
 
.features24-content1 {
  gap: 16px;
  flex: 1;
  display: flex;
  overflow: hidden;
  flex-grow: 1;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
  justify-content: center;
}
 
.features24-tab-horizontal2 {
  gap: var(--dl-layout-space-twounits);
  cursor: pointer;
  display: flex;
  overflow: hidden;
  align-self: stretch;
  align-items: flex-start;
  flex-shrink: 0;
}
 
.features24-divider-container2 {
  display: flex;
  align-self: stretch;
  align-items: flex-start;
}
 
.features24-container4 {
  width: 2px;
  align-self: stretch;
  background-color: var(--dl-color-theme-neutral-dark);
}
 
.features24-content2 {
  gap: 16px;
  flex: 1;
  display: flex;
  overflow: hidden;
  flex-grow: 1;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
  justify-content: center;
}
 
.features24-tab-horizontal3 {
  gap: var(--dl-layout-space-twounits);
  cursor: pointer;
  display: flex;
  overflow: hidden;
  align-self: stretch;
  align-items: flex-start;
  flex-shrink: 0;
}
 
.features24-divider-container3 {
  display: flex;
  align-self: stretch;
  align-items: flex-start;
}
 
.features24-container5 {
  width: 2px;
  align-self: stretch;
  background-color: var(--dl-color-theme-neutral-dark);
}
 
.features24-content3 {
  gap: 16px;
  flex: 1;
  display: flex;
  overflow: hidden;
  flex-grow: 1;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
  justify-content: center;
}
 
.features24-fragment1 {
  display: contents;
}
 
.features24-text1 {
  display: inline-block;
}
 
.features24-fragment2 {
  display: contents;
}
 
.features24-text2 {
  display: inline-block;
}
 
.features24-fragment3 {
  display: contents;
}
 
.features24-text3 {
  display: inline-block;
}
 
.features24-fragment4 {
  display: contents;
}
 
.features24-text4 {
  display: inline-block;
}
 
.features24-fragment5 {
  display: contents;
}
 
.features24-text5 {
  display: inline-block;
}
 
.features24-fragment6 {
  display: contents;
}
 
.features24-text6 {
  display: inline-block;
}
 
@media(max-width: 991px) {
  .features24-container2 {
    grid-gap: var(--dl-layout-space-twounits);
    grid-template-columns: 1fr;
  }
}
</style>
