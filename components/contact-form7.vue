<template>
  <div
    class="contact-form7-contact1 thq-section-padding"
    v-bind:class="rootClassName"
  >
    <div class="contact-form7-max-width thq-section-max-width thq-flex-row">
      <div class="contact-form7-section-title thq-flex-column">
        <span class="thq-body-small">
          <slot name="content2">
            <!--Default content for content2-->
            <div class="contact-form7-fragment5">
              <span class="contact-form7-text22">
                Our team is here to help you with any inquiries you may have. Feel
                free to reach out to us.
              </span>
            </div>
          </slot>
        </span>
        <div class="contact-form7-content1">
          <h2 class="thq-heading-2">
            <slot name="heading1">
              <!--Default content for heading1-->
              <div class="contact-form7-fragment2">
                <span class="contact-form7-text19">Contact Information</span>
              </div>
            </slot>
          </h2>
          <span class="thq-body-small contact-form7-text12">
            <slot name="content1">
              <!--Default content for content1-->
              <div class="contact-form7-fragment6">
                <span class="contact-form7-text23">
                  Have a question or need support?
                </span>
              </div>
            </slot>
          </span>
        </div>
        <div class="contact-form7-content2">
          <div class="contact-form7-row1"></div>
          <div class="contact-form7-row2">
            <svg viewBox="0 0 1024 1024" class="thq-icon-small">
              <path
                d="M282 460q96 186 282 282l94-94q20-20 44-10 72 24 152 24 18 0 30 12t12 30v150q0 18-12 30t-30 12q-300 0-513-213t-213-513q0-18 12-30t30-12h150q18 0 30 12t12 30q0 80 24 152 8 26-10 44z"
              ></path>
            </svg>
            <span class="thq-body-small">
              <slot name="phone">
                <!--Default content for phone-->
                <div class="contact-form7-fragment3">
                  <span class="contact-form7-text20">Phone</span>
                </div>
              </slot>
            </span>
          </div>
          <div class="contact-form7-row3">
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              class="contact-form7-icon3"
            >
              <g fill="currentColor">
                <path
                  d="M12 4a8 8 0 0 0-6.895 12.06l.569.718l-.697 2.359l2.32-.648l.379.243A8 8 0 1 0 12 4M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10a9.96 9.96 0 0 1-5.016-1.347l-4.948 1.382l1.426-4.829l-.006-.007l-.033-.055A9.96 9.96 0 0 1 2 12"
                  clip-rule="evenodd"
                  fill-rule="evenodd"
                ></path>
                <path
                  d="M16.735 13.492c-.038-.018-1.497-.736-1.756-.83a1 1 0 0 0-.34-.075c-.196 0-.362.098-.49.291c-.146.217-.587.732-.723.886c-.018.02-.042.045-.057.045c-.013 0-.239-.093-.307-.123c-1.564-.68-2.751-2.313-2.914-2.589c-.023-.04-.024-.057-.024-.057c.005-.021.058-.074.085-.101c.08-.079.166-.182.249-.283l.117-.14c.121-.14.175-.25.237-.375l.033-.066a.68.68 0 0 0-.02-.64c-.034-.069-.65-1.555-.715-1.711c-.158-.377-.366-.552-.655-.552c-.027 0 0 0-.112.005c-.137.005-.883.104-1.213.311c-.35.22-.94.924-.94 2.16c0 1.112.705 2.162 1.008 2.561l.041.06c1.161 1.695 2.608 2.951 4.074 3.537c1.412.564 2.081.63 2.461.63c.16 0 .288-.013.4-.024l.072-.007c.488-.043 1.56-.599 1.804-1.276c.192-.534.243-1.117.115-1.329c-.088-.144-.239-.216-.43-.308"
                ></path>
              </g>
            </svg>
            <span class="contact-form7-address thq-body-small">
              <slot name="address">
                <!--Default content for address-->
                <div class="contact-form7-fragment1">
                  <span class="contact-form7-text18">Message us on WhatsApp</span>
                </div>
              </slot>
            </span>
          </div>
        </div>
      </div>
      <form class="contact-form7-form thq-flex-column">
        <div class="contact-form7-container1">
          <div class="contact-form7-input1">
            <label for="contact-form-7-first-name" class="thq-body-small">
              First name
            </label>
            <input
              type="text"
              id="contact-form-7-first-name"
              placeholder="First Name"
              class="thq-input"
            />
          </div>
          <div class="contact-form7-input2">
            <label for="contact-form-7-last-name" class="thq-body-small">
              Last name
            </label>
            <input
              type="text"
              id="contact-form-7-last-name"
              placeholder="Last Name"
              class="thq-input"
            />
          </div>
        </div>
        <div class="contact-form7-container2">
          <div class="contact-form7-input3">
            <label for="contact-form-7-email" class="thq-body-small">Email</label>
            <input
              type="email"
              id="contact-form-7-email"
              required="true"
              placeholder="Email"
              class="thq-input"
            />
          </div>
          <div class="contact-form7-input4">
            <label for="contact-form-7-phone" class="thq-body-small">
              Phone Number
            </label>
            <input
              type="tel"
              id="contact-form-7-phone"
              placeholder="Phone Number"
              class="thq-input"
            />
          </div>
        </div>
        <div class="contact-form7-container3">
          <div class="contact-form7-input5">
            <label for="contact-form-7-message" class="thq-body-small">
              Message
            </label>
            <textarea
              id="contact-form-7-message"
              rows="3"
              placeholder="Enter your message"
              class="thq-input"
            ></textarea>
          </div>
        </div>
        <div class="contact-form7-checkbox"></div>
        <button type="submit" class="contact-form7-button thq-button-filled">
          <span class="thq-body-small">
            <slot name="action">
              <!--Default content for action-->
              <div class="contact-form7-fragment4">
                <span class="contact-form7-text21">Contact Us</span>
              </div>
            </slot>
          </span>
        </button>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContactForm7',
  props: {
    rootClassName: String,
  },
}
</script>

<style scoped>
.contact-form7-contact1 {
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
}
 
.contact-form7-max-width {
  align-items: flex-start;
}
 
.contact-form7-section-title {
  gap: var(--dl-layout-space-unit);
  width: 40%;
  align-items: flex-start;
}
 
.contact-form7-content1 {
  gap: var(--dl-layout-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  flex-direction: column;
}
 
.contact-form7-content2 {
  gap: 16px;
  display: flex;
  padding: 8px 0;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact-form7-row1 {
  gap: 16px;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: flex-start;
}
 
.contact-form7-row2 {
  gap: 16px;
  display: flex;
  align-items: flex-start;
}
 
.contact-form7-row3 {
  gap: 16px;
  display: flex;
  align-items: flex-start;
}
 
.contact-form7-icon3 {
  fill: var(--dl-color-theme-neutral-dark);
  color: #25a730;
}
 
.contact-form7-address {
  color: #15a015;
}
 
.contact-form7-form {
  gap: var(--dl-layout-space-oneandhalfunits);
  width: 60%;
}
 
.contact-form7-container1 {
  gap: var(--dl-layout-space-unit);
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
 
.contact-form7-input1 {
  gap: var(--dl-layout-space-halfunit);
  width: 50%;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact-form7-input2 {
  gap: var(--dl-layout-space-halfunit);
  width: 50%;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact-form7-container2 {
  gap: var(--dl-layout-space-unit);
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
 
.contact-form7-input3 {
  gap: var(--dl-layout-space-halfunit);
  width: 50%;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact-form7-input4 {
  gap: var(--dl-layout-space-halfunit);
  width: 50%;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact-form7-container3 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-self: flex-start;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact-form7-input5 {
  gap: var(--dl-layout-space-halfunit);
  width: 100%;
  display: flex;
  align-self: flex-start;
  align-items: flex-start;
  flex-direction: column;
}
 
.contact-form7-checkbox {
  gap: var(--dl-layout-space-unit);
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-self: flex-start;
  align-items: center;
}
 
.contact-form7-button {
  align-self: flex-start;
}
 
.contact-form7-fragment1 {
  display: contents;
}
 
.contact-form7-text18 {
  display: inline-block;
}
 
.contact-form7-fragment2 {
  display: contents;
}
 
.contact-form7-text19 {
  display: inline-block;
}
 
.contact-form7-fragment3 {
  display: contents;
}
 
.contact-form7-text20 {
  display: inline-block;
}
 
.contact-form7-fragment4 {
  display: contents;
}
 
.contact-form7-text21 {
  display: inline-block;
}
 
.contact-form7-fragment5 {
  display: contents;
}
 
.contact-form7-text22 {
  display: inline-block;
}
 
.contact-form7-fragment6 {
  display: contents;
}
 
.contact-form7-text23 {
  display: inline-block;
}
 
.contact-form7root-class-name {
  background-color: #f9c270;
}
 
@media(max-width: 1200px) {
  .contact-form7root-class-name {
    background-color: #f9c270;
  }
}
 
@media(max-width: 991px) {
  .contact-form7-max-width {
    align-items: flex-start;
    flex-direction: column;
  }
  .contact-form7-section-title {
    width: 100%;
  }
  .contact-form7-form {
    width: 100%;
  }
  .contact-form7-container1 {
    gap: var(--dl-layout-space-twounits);
    width: 100%;
    flex-direction: row;
  }
  .contact-form7-input1 {
    width: 50%;
  }
  .contact-form7-input2 {
    width: 50%;
    flex-direction: column;
  }
  .contact-form7-container2 {
    gap: var(--dl-layout-space-twounits);
    width: 100%;
    flex-direction: row;
  }
  .contact-form7-input3 {
    width: 50%;
  }
  .contact-form7-input4 {
    width: 50%;
  }
  .contact-form7-container3 {
    gap: var(--dl-layout-space-twounits);
    width: 100%;
    flex-direction: row;
  }
  .contact-form7-checkbox {
    align-self: flex-start;
  }
}
 
@media(max-width: 479px) {
  .contact-form7-text12 {
    text-align: center;
  }
  .contact-form7-form {
    padding: var(--dl-layout-space-unit);
  }
  .contact-form7-container1 {
    align-items: stretch;
    flex-direction: column;
  }
  .contact-form7-input1 {
    width: 100%;
  }
  .contact-form7-input2 {
    width: 100%;
  }
  .contact-form7-container2 {
    align-items: stretch;
    flex-direction: column;
  }
  .contact-form7-input3 {
    width: 100%;
  }
  .contact-form7-input4 {
    width: 100%;
  }
}
</style>
