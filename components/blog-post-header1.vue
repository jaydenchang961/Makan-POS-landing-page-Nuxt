<template>
  <div
    class="blog-post-header1-content1 thq-section-padding"
    v-bind:class="rootClassName"
  >
    <div class="blog-post-header1-max-width thq-section-max-width">
      <div class="blog-post-header1-header">
        <div class="blog-post-header1-content2"></div>
      </div>
      <h1 class="blog-post-header1-text1 thq-heading-1">
        <slot name="blogPostTitle">
          <!--Default content for blogPostTitle-->
          <div class="blog-post-header1-fragment">
            <span class="blog-post-header1-text2">
              <span>
                Our
                <span v-html="raw2w7t"></span>
              </span>
              <span class="blog-post-header1-text4">Sastisfied</span>
              <span>Customers</span>
            </span>
          </div>
        </slot>
      </h1>
    </div>
    <img
      :alt="blogPostImageAlt"
      :src="blogPostImageSrc"
      class="blog-post-header1-image1 thq-img-ratio-16-9"
    />
  </div>
</template>

<script>
export default {
  name: 'BlogPostHeader1',
  props: {
    rootClassName: String,
    blogPostImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1610224353475-f589ea4993f6?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1NDcxMTkzOXw&ixlib=rb-4.1.0&q=80&w=1500',
    },
    blogPostImageAlt: {
      type: String,
      default: 'Illustration of POS system features',
    },
  },
  data() {
    return {
      rawluqz: ' ',
      raw2w7t: ' ',
    }
  },
}
</script>

<style scoped>
.blog-post-header1-content1 {
  display: flex;
  position: relative;
  align-items: center;
}
 
.blog-post-header1-max-width {
  gap: var(--dl-layout-space-fiveunits);
  width: 100%;
  height: 157px;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.blog-post-header1-header {
  gap: var(--dl-layout-space-threeunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
 
.blog-post-header1-content2 {
  gap: var(--dl-layout-space-oneandhalfunits);
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  overflow: hidden;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.blog-post-header1-text1 {
  height: 7px;
}
 
.blog-post-header1-image1 {
  flex: 1;
  width: 993px;
  height: 492px;
  animation-name: none;
  animation-delay: 0s;
  animation-duration: 300ms;
  animation-direction: normal;
  animation-iteration-count: 1;
  animation-timing-function: ease;
}
 
.blog-post-header1-fragment {
  display: contents;
}
 
.blog-post-header1-text2 {
  display: inline-block;
}
 
.blog-post-header1-text4 {
  color: #e47709;
}
 
.blog-post-header1root-class-name {
  background-color: #f9c270;
}
 
@media(max-width: 1200px) {
  .blog-post-header1-max-width {
    height: 164px;
  }
  .blog-post-header1root-class-name {
    background-color: #f9c270;
  }
}
 
@media(max-width: 991px) {
  .blog-post-header1-max-width {
    height: 157px;
  }
}
 
@media(max-width: 767px) {
  .blog-post-header1-max-width {
    gap: var(--dl-layout-space-threeunits);
    height: 125px;
  }
  .blog-post-header1-header {
    gap: var(--dl-layout-space-oneandhalfunits);
  }
  .blog-post-header1-text1 {
    text-align: center;
  }
  .blog-post-header1-image1 {
    width: 767px;
    height: 557px;
  }
}
 
@media(max-width: 479px) {
  .blog-post-header1-max-width {
    gap: var(--dl-layout-space-oneandhalfunits);
    width: 477px;
    height: 66px;
    margin-right: 0px;
  }
  .blog-post-header1-image1 {
    width: 359px;
    height: 167px;
  }
  .blog-post-header1-text2 {
    font-size: 25px;
  }
  .blog-post-header1-text4 {
    color: #e47709;
  }
}
</style>
