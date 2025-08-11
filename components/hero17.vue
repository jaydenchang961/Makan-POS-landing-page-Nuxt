<template>
  <div class="hero17-header78" v-bind:class="rootClassName">
    <div class="hero17-column thq-section-max-width thq-section-padding">
      <div class="hero17-content1">
        <h1 class="hero17-text1 thq-heading-1">
          <slot name="heading1">
            <!--Default content for heading1-->
            <div class="hero17-fragment3">
              <span class="hero17-text7">Welcome to Our POS System Company</span>
            </div>
          </slot>
        </h1>
        <p class="hero17-text2 thq-body-large">
          <slot name="content1">
            <!--Default content for content1-->
            <div class="hero17-fragment4">
              <span class="hero17-text8">
                Experience the power of our user-friendly POS system with advanced
                features for your business.
              </span>
            </div>
          </slot>
        </p>
      </div>
      <div class="hero17-actions">
        <button class="thq-button-filled hero17-button1">
          <span class="thq-body-small">
            <slot name="action1">
              <!--Default content for action1-->
              <div class="hero17-fragment2">
                <span class="hero17-text6">Main action</span>
              </div>
            </slot>
          </span>
        </button>
        <button class="thq-button-outline hero17-button2">
          <span class="thq-body-small">
            <slot name="action2">
              <!--Default content for action2-->
              <div class="hero17-fragment1">
                <span class="hero17-text5">Secondary action</span>
              </div>
            </slot>
          </span>
        </button>
      </div>
    </div>
    <div class="hero17-content2">
      <div
        class="hero17-row-container1 thq-mask-image-horizontal thq-animated-group-container-horizontal"
      >
        <div class="thq-animated-group-horizontal">
          <img
            :alt="image1Alt"
            :src="image1Src"
            class="hero17-placeholder-image10 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image2Alt"
            :src="image2Src"
            class="hero17-placeholder-image11 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image3Alt"
            :src="image3Src"
            class="hero17-placeholder-image12 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image4Alt"
            :src="image4Src"
            class="hero17-placeholder-image13 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image5Alt"
            :src="image5Src"
            class="hero17-placeholder-image14 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image6Alt"
            :src="image6Src"
            class="hero17-placeholder-image15 thq-img-scale thq-img-ratio-1-1"
          />
        </div>
        <div class="thq-animated-group-horizontal">
          <img
            :alt="image1Alt"
            :src="image1Src"
            class="hero17-placeholder-image16 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image2Alt"
            :src="image2Src"
            class="hero17-placeholder-image17 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image3Alt"
            :src="image3Src"
            class="hero17-placeholder-image18 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image4Alt"
            :src="image4Src"
            class="hero17-placeholder-image19 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image5Alt"
            :src="image5Src"
            class="hero17-placeholder-image20 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            alt="Hero Image"
            src="https://images.unsplash.com/photo-1534312527009-56c7016453e6?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDIxfHxhYnN0cmFjdHxlbnwwfHx8fDE3MTA4NzA5MzB8MA&amp;ixlib=rb-4.0.3&amp;w=1500"
            class="hero17-placeholder-image21 thq-img-scale thq-img-ratio-1-1"
          />
        </div>
      </div>
      <div
        class="hero17-row-container2 thq-mask-image-horizontal thq-animated-group-container-horizontal"
      >
        <div class="thq-animated-group-horizontal-reverse">
          <img
            :alt="image7Alt"
            :src="image7Src"
            class="hero17-placeholder-image22 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image8Alt"
            :src="image8Src"
            class="hero17-placeholder-image23 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image9Alt"
            :src="image9Src"
            class="hero17-placeholder-image24 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image10Alt"
            :src="image10Src"
            class="hero17-placeholder-image25 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image11Alt"
            :src="image11Src"
            class="hero17-placeholder-image26 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image12Alt"
            :src="image12Src"
            class="hero17-placeholder-image27 thq-img-scale thq-img-ratio-1-1"
          />
        </div>
        <div class="thq-animated-group-horizontal-reverse">
          <img
            :alt="image7Alt"
            :src="image7Src"
            class="hero17-placeholder-image28 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image8Alt"
            :src="image8Src"
            class="hero17-placeholder-image29 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image9Alt"
            :src="image9Src"
            class="hero17-placeholder-image30 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image10Alt"
            :src="image10Src"
            class="hero17-placeholder-image31 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            :alt="image11Alt"
            :src="image11Src"
            class="hero17-placeholder-image32 thq-img-scale thq-img-ratio-1-1"
          />
          <img
            alt="Hero Image"
            src="https://images.unsplash.com/photo-1568214379698-8aeb8c6c6ac8?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDEyfHxncmFmaWN8ZW58MHx8fHwxNzE1Nzk0OTk5fDA&amp;ixlib=rb-4.0.3&amp;w=1500"
            class="hero17-placeholder-image33 thq-img-scale thq-img-ratio-1-1"
          />
        </div>
      </div>
    </div>
    <div>
      <div class="hero17-container2">
        <DangerousHTML
          html="<style>
    @keyframes scroll-x {
      from {
        transform: translateX(0);
      }
      to {
        transform: translateX(calc(-100% - 16px));
      }
    }
  
    @keyframes scroll-y {
      from {
        transform: translateY(0);
      }
      to {
        transform: translateY(calc(-100% - 16px));
      }
    }
  </style>
  "
        ></DangerousHTML>
      </div>
    </div>
  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/dist/vue/lib.js'

export default {
  name: 'Hero17',
  props: {
    image2Alt: {
      type: String,
      default: 'Hero Image',
    },
    image12Alt: {
      type: String,
      default: 'Hero Image',
    },
    image8Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1707249789706-ba64b4ee6a58?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MjY3ODQ0NXw&ixlib=rb-4.1.0&q=80&w=1080',
    },
    image2Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1680108484447-492cbbe70685?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MjY3ODQ0M3w&ixlib=rb-4.1.0&q=80&w=1080',
    },
    image6Alt: {
      type: String,
      default: 'Hero Image',
    },
    image6Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1439396812601-0b512add529f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MjY3ODQ0NHw&ixlib=rb-4.1.0&q=80&w=1080',
    },
    image4Alt: {
      type: String,
      default: 'Hero Image',
    },
    image8Alt: {
      type: String,
      default: 'Hero Image',
    },
    image7Alt: {
      type: String,
      default: 'Hero Image',
    },
    image12Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1726064855988-1e4deb0a3392?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MjY3ODQ0NHw&ixlib=rb-4.1.0&q=80&w=1080',
    },
    image7Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1659430243540-16d6b5ebd1d9?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MjY3ODQ0M3w&ixlib=rb-4.1.0&q=80&w=1080',
    },
    rootClassName: String,
    image3Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1586439702132-55ce0da661dd?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MjY3ODQ0MXw&ixlib=rb-4.1.0&q=80&w=1080',
    },
    image1Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1629968417850-3505f5180761?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MjY3ODQ0N3w&ixlib=rb-4.1.0&q=80&w=1080',
    },
    image10Alt: {
      type: String,
      default: 'Hero Image',
    },
    image11Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1551030797-46c120009b82?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MjY3ODQ0M3w&ixlib=rb-4.1.0&q=80&w=1080',
    },
    image5Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1613652072912-526703fcbfc4?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MjY3ODQ0Nnw&ixlib=rb-4.1.0&q=80&w=1080',
    },
    image1Alt: {
      type: String,
      default: 'POS System Company Image',
    },
    image9Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1569933438769-a2231608e06a?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MjY3ODQ0NXw&ixlib=rb-4.1.0&q=80&w=1080',
    },
    image3Alt: {
      type: String,
      default: 'Hero Image',
    },
    image9Alt: {
      type: String,
      default: 'Hero Image',
    },
    image10Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1676401863280-838787381d9e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MjY3ODQ0N3w&ixlib=rb-4.1.0&q=80&w=1080',
    },
    image5Alt: {
      type: String,
      default: 'Hero Image',
    },
    image11Alt: {
      type: String,
      default: 'Hero Image',
    },
    image4Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1701518035740-a33935aeb3ec?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MjY3ODQ0Nnw&ixlib=rb-4.1.0&q=80&w=1080',
    },
  },
  components: {
    DangerousHTML,
  },
}
</script>

<style scoped>
.hero17-header78 {
  gap: var(--dl-layout-space-threeunits);
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.hero17-column {
  gap: var(--dl-layout-space-oneandhalfunits);
  width: auto;
  display: flex;
  align-items: center;
  flex-direction: column;
  padding-bottom: var(--dl-layout-space-unit);
}
 
.hero17-content1 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
 
.hero17-text1 {
  text-align: center;
}
 
.hero17-text2 {
  text-align: center;
}
 
.hero17-actions {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-layout-space-unit);
}
 
.hero17-content2 {
  gap: var(--dl-layout-space-oneandhalfunits);
  width: 100%;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
 
.hero17-row-container1 {
  width: 100%;
}
 
.hero17-placeholder-image10 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image11 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image12 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image13 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image14 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image15 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image16 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image17 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image18 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image19 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image20 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image21 {
  width: 400px;
  height: 400px;
}
 
.hero17-row-container2 {
  width: 100%;
}
 
.hero17-placeholder-image22 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image23 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image24 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image25 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image26 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image27 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image28 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image29 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image30 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image31 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image32 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image33 {
  width: 400px;
  height: 400px;
}
 
.hero17-container2 {
  display: contents;
}
 
.hero17-fragment1 {
  display: contents;
}
 
.hero17-text5 {
  display: inline-block;
}
 
.hero17-fragment2 {
  display: contents;
}
 
.hero17-text6 {
  display: inline-block;
}
 
.hero17-fragment3 {
  display: contents;
}
 
.hero17-text7 {
  display: inline-block;
}
 
.hero17-fragment4 {
  display: contents;
}
 
.hero17-text8 {
  display: inline-block;
}
 
.hero17root-class-name {
  background-image: linear-gradient(0deg, rgb(192, 36, 37) 0.00%,rgb(240, 203, 53) 77.00%);
}
 
@media(max-width: 1200px) {
  .hero17root-class-name {
    background-image: linear-gradient(0deg, rgb(192, 36, 37) 0.00%,rgb(240, 203, 53) 73.00%);
  }
}
 
@media(max-width: 991px) {
  .hero17root-class-name {
    background-image: linear-gradient(0deg, rgb(192, 36, 37) 0.00%,rgb(240, 203, 53) 73.00%);
  }
}
 
@media(max-width: 767px) {
  .hero17-content2 {
    width: 100%;
  }
}
 
@media(max-width: 479px) {
  .hero17-actions {
    width: 100%;
    flex-direction: column;
  }
  .hero17-button1 {
    width: 100%;
  }
  .hero17-button2 {
    width: 100%;
  }
}
</style>
