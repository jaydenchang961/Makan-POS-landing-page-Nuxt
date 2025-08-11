<template>
  <div class="contact3-contact20 thq-section-padding">
    <div class="contact3-max-width thq-section-max-width">
      <div class="contact3-section-title">
        <span class="thq-body-small">
          <slot name="content2">
            <!--Default content for content2-->
            <div class="contact3-fragment4">
              <span class="contact3-text22">Get in touch with us today!</span>
            </div>
          </slot>
        </span>
        <div class="contact3-content1">
          <h2 class="thq-heading-2">
            <slot name="heading1">
              <!--Default content for heading1-->
              <div class="contact3-fragment6">
                <span class="contact3-text24">Contact Us</span>
              </div>
            </slot>
          </h2>
          <p class="contact3-text12 thq-body-large">
            <slot name="content1">
              <!--Default content for content1-->
              <div class="contact3-fragment1">
                <span class="contact3-text19">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  <span v-html="raw95wo"></span>
                </span>
              </div>
            </slot>
          </p>
        </div>
      </div>
      <div class="contact3-row">
        <div class="contact3-content2">
          <svg viewBox="0 0 1024 1024" class="thq-icon-medium">
            <path
              d="M854 342v-86l-342 214-342-214v86l342 212zM854 170q34 0 59 26t25 60v512q0 34-25 60t-59 26h-684q-34 0-59-26t-25-60v-512q0-34 25-60t59-26h684z"
            ></path>
          </svg>
          <div class="contact3-contact-info1">
            <div class="contact3-content3">
              <h3 class="contact3-text13 thq-heading-3">Email</h3>
              <p class="contact3-text14 thq-body-large">
                <slot name="content3">
                  <!--Default content for content3-->
                  <div class="contact3-fragment9">
                    <span class="contact3-text27">
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                      Suspendisse varius enim in ero.
                    </span>
                  </div>
                </slot>
              </p>
            </div>
            <span class="contact3-email thq-body-small">
              <slot name="email1">
                <!--Default content for email1-->
                <div class="contact3-fragment3">
                  <span class="contact3-text21">info@poscompany.com</span>
                </div>
              </slot>
            </span>
          </div>
        </div>
        <div class="contact3-content4">
          <svg viewBox="0 0 1024 1024" class="thq-icon-medium">
            <path
              d="M282 460q96 186 282 282l94-94q20-20 44-10 72 24 152 24 18 0 30 12t12 30v150q0 18-12 30t-30 12q-300 0-513-213t-213-513q0-18 12-30t30-12h150q18 0 30 12t12 30q0 80 24 152 8 26-10 44z"
            ></path>
          </svg>
          <div class="contact3-contact-info2">
            <div class="contact3-content5">
              <h3 class="contact3-text15 thq-heading-3">Phone</h3>
              <p class="contact3-text16 thq-body-large">
                <slot name="content4">
                  <!--Default content for content4-->
                  <div class="contact3-fragment8">
                    <span class="contact3-text26">
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                      Suspendisse varius enim in ero.
                    </span>
                  </div>
                </slot>
              </p>
            </div>
            <span class="contact3-phone thq-body-small">
              <slot name="phone1">
                <!--Default content for phone1-->
                <div class="contact3-fragment7">
                  <span class="contact3-text25">+1 (555) 123-4567</span>
                </div>
              </slot>
            </span>
          </div>
        </div>
        <div class="contact3-content6">
          <svg viewBox="0 0 1024 1024" class="thq-icon-medium">
            <path
              d="M512 0c-176.732 0-320 143.268-320 320 0 320 320 704 320 704s320-384 320-704c0-176.732-143.27-320-320-320zM512 512c-106.040 0-192-85.96-192-192s85.96-192 192-192 192 85.96 192 192-85.96 192-192 192z"
            ></path>
          </svg>
          <div class="contact3-contact-info3">
            <div class="contact3-content7">
              <h3 class="contact3-text17 thq-heading-3">Office</h3>
              <p class="contact3-text18 thq-body-large">
                <slot name="content5">
                  <!--Default content for content5-->
                  <div class="contact3-fragment2">
                    <span class="contact3-text20">
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                      Suspendisse varius enim in ero.
                    </span>
                  </div>
                </slot>
              </p>
            </div>
            <span class="contact3-address thq-body-small">
              <slot name="address1">
                <!--Default content for address1-->
                <div class="contact3-fragment5">
                  <span class="contact3-text23">
                    123 Main Street, Cityville, State, 12345
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
  name: 'Contact3',
  props: {},
  data() {
    return {
      rawb234: ' ',
      raw95wo: ' ',
    }
  },
}
</script>

<style scoped>
.contact3-contact20 {
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-direction: column;
}
 
.contact3-max-width {
  gap: var(--dl-layout-space-twounits);
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.contact3-section-title {
  gap: var(--dl-layout-space-unit);
  width: auto;
  display: flex;
  max-width: 800px;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.contact3-content1 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
 
.contact3-text12 {
  text-align: center;
}
 
.contact3-row {
  gap: var(--dl-layout-space-threeunits);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
}
 
.contact3-content2 {
  gap: var(--dl-layout-space-oneandhalfunits);
  flex: 1;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.contact3-contact-info1 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
 
.contact3-content3 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-self: stretch;
  align-items: stretch;
  flex-direction: column;
}
 
.contact3-text13 {
  align-self: stretch;
  text-align: center;
}
 
.contact3-text14 {
  text-align: center;
}
 
.contact3-email {
  text-align: center;
}
 
.contact3-content4 {
  gap: var(--dl-layout-space-oneandhalfunits);
  flex: 1;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.contact3-contact-info2 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
 
.contact3-content5 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-self: stretch;
  align-items: stretch;
  flex-direction: column;
}
 
.contact3-text15 {
  align-self: stretch;
  text-align: center;
}
 
.contact3-text16 {
  text-align: center;
}
 
.contact3-phone {
  text-align: center;
}
 
.contact3-content6 {
  gap: var(--dl-layout-space-oneandhalfunits);
  flex: 1;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
 
.contact3-contact-info3 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
 
.contact3-content7 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-self: stretch;
  align-items: stretch;
  flex-direction: column;
}
 
.contact3-text17 {
  align-self: stretch;
  text-align: center;
}
 
.contact3-text18 {
  text-align: center;
}
 
.contact3-address {
  text-align: center;
}
 
.contact3-fragment1 {
  display: contents;
}
 
.contact3-text19 {
  display: inline-block;
}
 
.contact3-fragment2 {
  display: contents;
}
 
.contact3-text20 {
  display: inline-block;
}
 
.contact3-fragment3 {
  display: contents;
}
 
.contact3-text21 {
  display: inline-block;
}
 
.contact3-fragment4 {
  display: contents;
}
 
.contact3-text22 {
  display: inline-block;
}
 
.contact3-fragment5 {
  display: contents;
}
 
.contact3-text23 {
  display: inline-block;
}
 
.contact3-fragment6 {
  display: contents;
}
 
.contact3-text24 {
  display: inline-block;
}
 
.contact3-fragment7 {
  display: contents;
}
 
.contact3-text25 {
  display: inline-block;
}
 
.contact3-fragment8 {
  display: contents;
}
 
.contact3-text26 {
  display: inline-block;
}
 
.contact3-fragment9 {
  display: contents;
}
 
.contact3-text27 {
  display: inline-block;
}
 
@media(max-width: 767px) {
  .contact3-row {
    flex-direction: column;
  }
}
 
@media(max-width: 479px) {
  .contact3-row {
    align-items: stretch;
  }
}
</style>
