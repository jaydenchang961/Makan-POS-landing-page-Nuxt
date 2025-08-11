<template>
  <div class="faq6faq7 thq-section-padding">
    <div class="thq-flex-column thq-section-max-width faq6-max-width">
      <div class="faq6-section-title thq-flex-column">
        <h2 class="faq6-text10 thq-heading-2">
          <slot name="faqTitle">
            <!--Default content for faqTitle-->
            <div class="faq6-fragment26">
              <span class="faq6-text30">Frequently Asked Questions</span>
            </div>
          </slot>
        </h2>
        <p class="faq6-text11 thq-body-large">
          <slot name="facqDetails">
            <!--Default content for facqDetails-->
            <div class="faq6-fragment10">
              <span class="faq6-text14">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Suspendisse varius enim in eros elementum tristique.
              </span>
            </div>
          </slot>
        </p>
      </div>
      <div class="thq-flex-column">
        <div class="faq6-list-item1">
          <p class="faq6-faq1-question thq-body-large">
            <slot name="faq1Question">
              <!--Default content for faq1Question-->
              <div class="faq6-fragment12">
                <span class="faq6-text16">
                  How can I sign up for a free trial?
                </span>
              </div>
            </slot>
          </p>
          <span class="faq6-faq1-answer thq-body-small">
            <slot name="faq1Answer">
              <!--Default content for faq1Answer-->
              <div class="faq6-fragment17">
                <span class="faq6-text21">
                  You can sign up for a free trial by visiting our website and
                  filling out the registration form.
                </span>
              </div>
            </slot>
          </span>
        </div>
        <div class="faq6-list-item2">
          <p class="faq6-faq2-question thq-body-large">
            <slot name="faq2Question">
              <!--Default content for faq2Question-->
              <div class="faq6-fragment24">
                <span class="faq6-text28">
                  What features are included in the admin portal?
                </span>
              </div>
            </slot>
          </p>
          <span class="faq6-faq2-answer thq-body-small">
            <slot name="faq2Answer">
              <!--Default content for faq2Answer-->
              <div class="faq6-fragment23">
                <span class="faq6-text27">
                  The admin portal includes features such as sales reporting,
                  inventory management, and user access control.
                </span>
              </div>
            </slot>
          </span>
        </div>
        <div class="faq6-list-item3">
          <p class="faq6-faq3-question thq-body-large">
            <slot name="faq3Question">
              <!--Default content for faq3Question-->
              <div class="faq6-fragment18">
                <span class="faq6-text22">
                  How does the efficient cashiering feature work?
                </span>
              </div>
            </slot>
          </p>
          <span class="faq6-faq3-answer thq-body-small">
            <slot name="faq3Answer">
              <!--Default content for faq3Answer-->
              <div class="faq6-fragment16">
                <span class="faq6-text20">
                  The efficient cashiering feature allows for quick and accurate
                  processing of transactions, including multiple payment methods.
                </span>
              </div>
            </slot>
          </span>
        </div>
        <div class="faq6-list-item4">
          <p class="faq6-faq4-question thq-body-large">
            <slot name="faq4Question">
              <!--Default content for faq4Question-->
              <div class="faq6-fragment15">
                <span class="faq6-text19">
                  Can customers place orders through QR scan?
                </span>
              </div>
            </slot>
          </p>
          <span class="faq6-faq4-answer thq-body-small">
            <slot name="faq4Answer">
              <!--Default content for faq4Answer-->
              <div class="faq6-fragment13">
                <span class="faq6-text17">
                  Yes, customers can easily place orders by scanning QR codes
                  displayed at the tables or counters.
                </span>
              </div>
            </slot>
          </span>
        </div>
        <div class="faq6-list-item51">
          <p class="faq6-faq5-question1 thq-body-large">
            <slot name="faq5Question">
              <!--Default content for faq5Question-->
              <div class="faq6-fragment11">
                <span class="faq6-text15">
                  Is customer support available for inquiries?
                </span>
              </div>
            </slot>
          </p>
          <span class="faq6-faq5-answer1 thq-body-small">
            <slot name="faq5Answer">
              <!--Default content for faq5Answer-->
              <div class="faq6-fragment22">
                <span class="faq6-text26">
                  Yes, we provide customer support to assist with any questions or
                  issues you may have.
                </span>
              </div>
            </slot>
          </span>
        </div>
        <div class="faq6-list-item52">
          <p class="faq6-faq5-question2 thq-body-large">
            <slot name="faq6Question">
              <!--Default content for faq6Question-->
              <div class="faq6-fragment19">
                <span class="faq6-text23">
                  Can I customize the POS system to suit my business needs?
                </span>
              </div>
            </slot>
          </p>
          <span class="faq6-faq5-answer2 thq-body-small">
            <slot name="faq6Answer">
              <!--Default content for faq6Answer-->
              <div class="faq6-fragment20">
                <span class="faq6-text24">
                  Yes, our POS system is customizable to adapt to various types of
                  businesses and their specific requirements.
                </span>
              </div>
            </slot>
          </span>
        </div>
      </div>
      <div class="thq-flex-column">
        <div class="faq6-content2">
          <h2 class="faq6-text12 thq-heading-2">
            <slot name="faqSubtitle">
              <!--Default content for faqSubtitle-->
              <div class="faq6-fragment21">
                <span class="faq6-text25">
                  Find answers to common queries about our POS system
                </span>
              </div>
            </slot>
          </h2>
          <p class="faq6-text13 thq-body-large">
            <slot name="faqDetailsSubtitle">
              <!--Default content for faqDetailsSubtitle-->
              <div class="faq6-fragment14">
                <span class="faq6-text18">
                  Learn more about our user-friendly POS system
                </span>
              </div>
            </slot>
          </p>
        </div>
        <button class="thq-button-outline">
          <span class="thq-body-small">
            <slot name="contactAction">
              <!--Default content for contactAction-->
              <div class="faq6-fragment25">
                <span class="faq6-text29">
                  Have more questions? Contact us for further assistance.
                </span>
              </div>
            </slot>
          </span>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FAQ6',
  props: {},
}
</script>

<style scoped>
.faq6faq7 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.faq6-section-title {
  align-items: center;
}
 
.faq6-text10 {
  text-align: center;
}
 
.faq6-text11 {
  text-align: center;
}
 
.faq6-list-item1 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.faq6-faq1-question {
  align-self: center;
  font-style: normal;
  text-align: center;
  font-weight: 600;
}
 
.faq6-faq1-answer {
  text-align: center;
}
 
.faq6-list-item2 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.faq6-faq2-question {
  align-self: center;
  font-style: normal;
  text-align: center;
  font-weight: 600;
}
 
.faq6-faq2-answer {
  text-align: center;
}
 
.faq6-list-item3 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.faq6-faq3-question {
  align-self: center;
  font-style: normal;
  text-align: center;
  font-weight: 600;
}
 
.faq6-faq3-answer {
  text-align: center;
}
 
.faq6-list-item4 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.faq6-faq4-question {
  align-self: center;
  font-style: normal;
  text-align: center;
  font-weight: 600;
}
 
.faq6-faq4-answer {
  text-align: center;
}
 
.faq6-list-item51 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.faq6-faq5-question1 {
  align-self: center;
  font-style: normal;
  text-align: center;
  font-weight: 600;
}
 
.faq6-faq5-answer1 {
  text-align: center;
}
 
.faq6-list-item52 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.faq6-faq5-question2 {
  align-self: center;
  font-style: normal;
  text-align: center;
  font-weight: 600;
}
 
.faq6-faq5-answer2 {
  text-align: center;
}
 
.faq6-content2 {
  gap: var(--dl-layout-space-unit);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
 
.faq6-text12 {
  text-align: center;
}
 
.faq6-text13 {
  text-align: center;
}
 
.faq6-fragment10 {
  display: contents;
}
 
.faq6-text14 {
  display: inline-block;
}
 
.faq6-fragment11 {
  display: contents;
}
 
.faq6-text15 {
  display: inline-block;
}
 
.faq6-fragment12 {
  display: contents;
}
 
.faq6-text16 {
  display: inline-block;
}
 
.faq6-fragment13 {
  display: contents;
}
 
.faq6-text17 {
  display: inline-block;
}
 
.faq6-fragment14 {
  display: contents;
}
 
.faq6-text18 {
  display: inline-block;
}
 
.faq6-fragment15 {
  display: contents;
}
 
.faq6-text19 {
  display: inline-block;
}
 
.faq6-fragment16 {
  display: contents;
}
 
.faq6-text20 {
  display: inline-block;
}
 
.faq6-fragment17 {
  display: contents;
}
 
.faq6-text21 {
  display: inline-block;
}
 
.faq6-fragment18 {
  display: contents;
}
 
.faq6-text22 {
  display: inline-block;
}
 
.faq6-fragment19 {
  display: contents;
}
 
.faq6-text23 {
  display: inline-block;
}
 
.faq6-fragment20 {
  display: contents;
}
 
.faq6-text24 {
  display: inline-block;
}
 
.faq6-fragment21 {
  display: contents;
}
 
.faq6-text25 {
  display: inline-block;
}
 
.faq6-fragment22 {
  display: contents;
}
 
.faq6-text26 {
  display: inline-block;
}
 
.faq6-fragment23 {
  display: contents;
}
 
.faq6-text27 {
  display: inline-block;
}
 
.faq6-fragment24 {
  display: contents;
}
 
.faq6-text28 {
  display: inline-block;
}
 
.faq6-fragment25 {
  display: contents;
}
 
.faq6-text29 {
  display: inline-block;
}
 
.faq6-fragment26 {
  display: contents;
}
 
.faq6-text30 {
  display: inline-block;
}
 
@media(max-width: 767px) {
  .faq6-max-width {
    width: 100%;
  }
}
</style>
