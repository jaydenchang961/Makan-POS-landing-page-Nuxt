<template>
  <div class="contact-form1-contact1 thq-section-padding">
    <div class="contact-form1-max-width thq-section-max-width">
      <div class="contact-form1-container1">
        <div class="contact-form1-section-title thq-card">
          <span class="thq-body-small">
            <slot name="content2">
              <!--Default content for content2-->
              <div class="contact-form1-fragment4">
                <span class="contact-form1-text19">
                  Get in touch with us today!
                </span>
              </div>
            </slot>
          </span>
          <h2 class="thq-heading-2">
            <slot name="heading1">
              <!--Default content for heading1-->
              <div class="contact-form1-fragment3">
                <span class="contact-form1-text18">Contact us</span>
              </div>
            </slot>
          </h2>
          <span class="thq-body-small">
            <slot name="content1">
              <!--Default content for content1-->
              <div class="contact-form1-fragment1">
                <span class="contact-form1-text16">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  <span v-html="raw7moq"></span>
                </span>
              </div>
            </slot>
          </span>
        </div>
        <form class="thq-card">
          <div class="contact-form1-container2">
            <div class="contact-form1-input1 thq-flex-row">
              <label for="contact-form-1-name" class="thq-body-small">Name</label>
              <input
                type="text"
                id="contact-form-1-name"
                placeholder="Name"
                class="contact-form1-text-input1 thq-input"
              />
            </div>
            <div class="contact-form1-input2 thq-flex-row">
              <label for="contact-form-1-email" class="thq-body-small">
                Email
              </label>
              <input
                type="email"
                id="contact-form-1-email"
                required="true"
                placeholder="Email"
                class="contact-form1-text-input2 thq-input"
              />
            </div>
          </div>
          <div class="contact-form1-checkbox1 thq-flex-row">
            <input
              type="checkbox"
              id="contact-form-1-check"
              checked="true"
              required="true"
              class="thq-checkbox"
            />
            <label for="contact-form-1-check" class="thq-body-small">
              I accept the Terms
            </label>
          </div>
          <button type="submit" class="contact-form1-button thq-button-filled">
            <span class="thq-body-small">
              <slot name="action">
                <!--Default content for action-->
                <div class="contact-form1-fragment2">
                  <span class="contact-form1-text17">Submit</span>
                </div>
              </slot>
            </span>
          </button>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContactForm1',
  props: {},
  data() {
    return {
      rawpfio: ' ',
      raw7moq: ' ',
    }
  },
}
</script>

<style scoped>
.contact-form1-contact1 {
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
}
 
.contact-form1-max-width {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact-form1-container1 {
  display: flex;
  align-items: stretch;
  flex-direction: column;
}
 
.contact-form1-section-title {
  align-self: flex-start;
}
 
.contact-form1-container2 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: stretch;
  flex-direction: column;
  justify-content: center;
}
 
.contact-form1-input1 {
  width: 100%;
  align-self: flex-start;
  justify-content: space-between;
}
 
.contact-form1-text-input1 {
  flex: 1;
}
 
.contact-form1-input2 {
  width: 100%;
  align-self: flex-start;
  justify-content: space-between;
}
 
.contact-form1-text-input2 {
  flex: 1;
}
 
.contact-form1-checkbox1 {
  align-self: flex-start;
}
 
.contact-form1-button {
  align-self: flex-start;
}
 
.contact-form1-fragment1 {
  display: contents;
}
 
.contact-form1-text16 {
  display: inline-block;
}
 
.contact-form1-fragment2 {
  display: contents;
}
 
.contact-form1-text17 {
  display: inline-block;
}
 
.contact-form1-fragment3 {
  display: contents;
}
 
.contact-form1-text18 {
  display: inline-block;
}
 
.contact-form1-fragment4 {
  display: contents;
}
 
.contact-form1-text19 {
  display: inline-block;
}
 
@media(max-width: 991px) {
  .contact-form1-input1 {
    align-items: center;
    flex-direction: row;
  }
  .contact-form1-input2 {
    align-items: center;
    flex-direction: row;
  }
  .contact-form1-checkbox1 {
    width: 100%;
    align-items: center;
    flex-direction: row;
  }
}
</style>
