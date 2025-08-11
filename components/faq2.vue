<template>
  <div class="faq2faq8 thq-section-padding">
    <div class="faq2-max-width thq-section-max-width">
      <div class="thq-flex-row faq2-container">
        <div class="thq-flex-column">
          <div class="faq2-content">
            <h2 class="faq2-text10 thq-heading-2">
              <slot name="heading1">
                <!--Default content for heading1-->
                <div class="faq2-fragment17">
                  <span class="faq2-text19">Frequently Asked Questions</span>
                </div>
              </slot>
            </h2>
            <p class="faq2-text11 thq-body-large">
              <slot name="content1">
                <!--Default content for content1-->
                <div class="faq2-fragment11">
                  <span class="faq2-text13">
                    Find answers to common queries about our POS system below.
                  </span>
                </div>
              </slot>
            </p>
          </div>
          <button class="faq2-button thq-button-outline">
            <span class="thq-body-small">
              <slot name="action">
                <!--Default content for action-->
                <div class="faq2-fragment18">
                  <span class="faq2-text20">Contact us for more information</span>
                </div>
              </slot>
            </span>
          </button>
        </div>
        <div class="thq-flex-column">
          <div class="faq2-list-item1">
            <p class="faq2-faq1-question thq-body-large">
              <slot name="faq1Question">
                <!--Default content for faq1Question-->
                <div class="faq2-fragment16">
                  <span class="faq2-text18">
                    How can I sign up for a free trial?
                  </span>
                </div>
              </slot>
            </p>
            <span class="thq-body-small">
              <slot name="faq1Answer">
                <!--Default content for faq1Answer-->
                <div class="faq2-fragment19">
                  <span class="faq2-text21">
                    To sign up for a free trial, simply click on the &apos;Sign
                    Up&apos; button on the homepage and follow the instructions to
                    create your account.
                  </span>
                </div>
              </slot>
            </span>
          </div>
          <div class="faq2-list-item2">
            <p class="faq2-faq2-question thq-body-large">
              <slot name="faq2Question">
                <!--Default content for faq2Question-->
                <div class="faq2-fragment13">
                  <span class="faq2-text15">
                    What features are included in the POS system?
                  </span>
                </div>
              </slot>
            </p>
            <span class="thq-body-small">
              <slot name="faq2Answer">
                <!--Default content for faq2Answer-->
                <div class="faq2-fragment15">
                  <span class="faq2-text17">
                    The POS system includes features such as admin portal access,
                    efficient cashiering tools, and seamless QR scan ordering
                    capabilities.
                  </span>
                </div>
              </slot>
            </span>
          </div>
          <div class="faq2-list-item3">
            <p class="faq2-faq3-question thq-body-large">
              <slot name="faq3Question">
                <!--Default content for faq3Question-->
                <div class="faq2-fragment14">
                  <span class="faq2-text16">Is customer support available?</span>
                </div>
              </slot>
            </p>
            <span class="thq-body-small">
              <slot name="faq3Answer">
                <!--Default content for faq3Answer-->
                <div class="faq2-fragment21">
                  <span class="faq2-text23">
                    Yes, we offer customer support for any inquiries or issues you
                    may have. You can reach out to our support team via email or
                    phone.
                  </span>
                </div>
              </slot>
            </span>
          </div>
          <div class="faq2-list-item4">
            <p class="faq2-faq4-question thq-body-large">
              <slot name="faq4Question">
                <!--Default content for faq4Question-->
                <div class="faq2-fragment12">
                  <span class="faq2-text14">
                    Can I upgrade my plan after the free trial?
                  </span>
                </div>
              </slot>
            </p>
            <span class="thq-body-small">
              <slot name="faq4Answer">
                <!--Default content for faq4Answer-->
                <div class="faq2-fragment20">
                  <span class="faq2-text22">
                    Yes, you can upgrade your plan at any time. Simply log in to
                    your account and navigate to the subscription settings to
                    choose a plan that suits your needs.
                  </span>
                </div>
              </slot>
            </span>
          </div>
          <div class="faq2-list-item5">
            <p class="faq2-faq5-question thq-body-large">
              <slot name="faq5Question">
                <!--Default content for faq5Question-->
                <div class="faq2-fragment10">
                  <span class="faq2-text12">How secure is the POS system?</span>
                </div>
              </slot>
            </p>
            <span class="thq-body-small">
              <slot name="faq5Answer">
                <!--Default content for faq5Answer-->
                <div class="faq2-fragment22">
                  <span class="faq2-text24">
                    Our POS system prioritizes security and data protection. We
                    use encryption technology to safeguard your information and
                    ensure safe transactions.
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
  name: 'FAQ2',
  props: {},
}
</script>

<style scoped>
.faq2faq8 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
 
.faq2-max-width {
  display: flex;
  align-self: center;
  align-items: flex-start;
  flex-direction: column;
}
 
.faq2-content {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.faq2-text10 {
  fill: var(--dl-color-theme-neutral-dark);
  color: var(--dl-color-theme-neutral-dark);
}
 
.faq2-text11 {
  fill: var(--dl-color-theme-neutral-dark);
  color: var(--dl-color-theme-neutral-dark);
}
 
.faq2-button {
  align-self: flex-start;
}
 
.faq2-list-item1 {
  gap: 16px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.faq2-faq1-question {
  font-style: normal;
  text-align: center;
  font-weight: 600;
}
 
.faq2-list-item2 {
  gap: 16px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.faq2-faq2-question {
  font-style: normal;
  text-align: center;
  font-weight: 600;
}
 
.faq2-list-item3 {
  gap: 16px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.faq2-faq3-question {
  font-style: normal;
  text-align: center;
  font-weight: 600;
}
 
.faq2-list-item4 {
  gap: 16px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.faq2-faq4-question {
  font-style: normal;
  text-align: center;
  font-weight: 600;
}
 
.faq2-list-item5 {
  gap: 16px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.faq2-faq5-question {
  font-style: normal;
  text-align: center;
  font-weight: 600;
}
 
.faq2-fragment10 {
  display: contents;
}
 
.faq2-text12 {
  display: inline-block;
}
 
.faq2-fragment11 {
  display: contents;
}
 
.faq2-text13 {
  display: inline-block;
}
 
.faq2-fragment12 {
  display: contents;
}
 
.faq2-text14 {
  display: inline-block;
}
 
.faq2-fragment13 {
  display: contents;
}
 
.faq2-text15 {
  display: inline-block;
}
 
.faq2-fragment14 {
  display: contents;
}
 
.faq2-text16 {
  display: inline-block;
}
 
.faq2-fragment15 {
  display: contents;
}
 
.faq2-text17 {
  display: inline-block;
}
 
.faq2-fragment16 {
  display: contents;
}
 
.faq2-text18 {
  display: inline-block;
}
 
.faq2-fragment17 {
  display: contents;
}
 
.faq2-text19 {
  display: inline-block;
}
 
.faq2-fragment18 {
  display: contents;
}
 
.faq2-text20 {
  display: inline-block;
}
 
.faq2-fragment19 {
  display: contents;
}
 
.faq2-text21 {
  display: inline-block;
}
 
.faq2-fragment20 {
  display: contents;
}
 
.faq2-text22 {
  display: inline-block;
}
 
.faq2-fragment21 {
  display: contents;
}
 
.faq2-text23 {
  display: inline-block;
}
 
.faq2-fragment22 {
  display: contents;
}
 
.faq2-text24 {
  display: inline-block;
}
 
@media(max-width: 991px) {
  .faq2-container {
    flex-direction: column;
  }
}
 
@media(max-width: 767px) {
  .faq2faq8 {
    padding: var(--dl-layout-space-threeunits);
  }
}
 
@media(max-width: 479px) {
  .faq2faq8 {
    padding: var(--dl-layout-space-oneandhalfunits);
  }
  .faq2-button {
    align-self: center;
  }
}
</style>
