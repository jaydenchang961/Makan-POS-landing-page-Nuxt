<template>
  <div class="home-container">
    <app-navbar1 logoSrc="/column.svg" rootClassName="navbar1root-class-name">
      <template v-slot:link1>
        <div class="home-fragment10"><span class="home-text10">Home</span></div>
      </template>
      <template v-slot:link2>
        <div class="home-fragment11">
          <span class="home-text11">Features</span>
        </div>
      </template>
      <template v-slot:link3>
        <div class="home-fragment12">
          <span class="home-text12">About Us</span>
        </div>
      </template>
      <template v-slot:link4>
        <div class="home-fragment13">
          <span class="home-text13">Contact Us</span>
        </div>
      </template>
      <template v-slot:link5>
        <div class="home-fragment14"><span class="home-text14">Link5</span></div>
      </template>
      <template v-slot:action1>
        <div class="home-fragment15">
          <span class="home-text15">Sign Up</span>
        </div>
      </template>
      <template v-slot:action2>
        <div class="home-fragment16">
          <span class="home-text16">Action 2</span>
        </div>
      </template>
    </app-navbar1>
    <app-hero17
      image1Src="https://images.unsplash.com/photo-1590846406792-0adc7f938f1d?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDEzfHxyZXN0YXVyYW50fGVufDB8fHx8MTc1MjY3ODYxM3ww&amp;ixlib=rb-4.1.0&amp;w=1500"
      image2Src="https://images.unsplash.com/photo-1636405188904-bc706f07aa37?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDQzfHxyZXN0YXVyYW50fGVufDB8fHx8MTc1MjY3ODYyNnww&amp;ixlib=rb-4.1.0&amp;w=1500"
      image3Src="https://images.unsplash.com/photo-1647427017067-8f33ccbae493?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDN8fFBPU3xlbnwwfHx8fDE3NTI2Nzg2MzV8MA&amp;ixlib=rb-4.1.0&amp;w=1500"
      image4Src="https://images.unsplash.com/photo-1556742044-3c52d6e88c62?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDR8fFBPU3xlbnwwfHx8fDE3NTI2Nzg2MzV8MA&amp;ixlib=rb-4.1.0&amp;w=1500"
      image6Src="https://images.unsplash.com/photo-1648824572347-6edd9a108e28?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDQ5fHxQT1N8ZW58MHx8fHwxNzUyNjc4Njg0fDA&amp;ixlib=rb-4.1.0&amp;w=1500"
      image7Src="https://images.unsplash.com/photo-1556742208-999815fca738?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDE2fHxQT1N8ZW58MHx8fHwxNzUyNjc4NjM1fDA&amp;ixlib=rb-4.1.0&amp;w=1500"
      image8Src="https://images.unsplash.com/photo-1586864030223-a918b07d357d?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDd8fFBPU3xlbnwwfHx8fDE3NTI2Nzg2MzV8MA&amp;ixlib=rb-4.1.0&amp;w=1500"
      image9Src="https://images.unsplash.com/photo-1718010571964-bac048b9ded0?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDExfHxQT1N8ZW58MHx8fHwxNzUyNjc4NjM1fDA&amp;ixlib=rb-4.1.0&amp;w=1500"
      image10Src="https://images.unsplash.com/photo-1726137570707-0c03e2867b16?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDM5fHxQT1N8ZW58MHx8fHwxNzUyNjc4NjM3fDA&amp;ixlib=rb-4.1.0&amp;w=1500"
      image11Src="https://images.unsplash.com/photo-1706827183359-6b015aaad56c?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDMyfHxQT1N8ZW58MHx8fHwxNzUyNjc4NjM3fDA&amp;ixlib=rb-4.1.0&amp;w=1500"
      image12Src="https://images.unsplash.com/photo-1693632376342-96ccd26632f1?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDgxfHxQT1N8ZW58MHx8fHwxNzUyNjc4Njk2fDA&amp;ixlib=rb-4.1.0&amp;w=1500"
      rootClassName="hero17root-class-name"
    >
      <template v-slot:action1>
        <div class="home-fragment17">
          <span class="home-text17">Sign Up</span>
        </div>
      </template>
      <template v-slot:action2>
        <div class="home-fragment18">
          <span class="home-text18">View Our Interface</span>
        </div>
      </template>
      <template v-slot:content1>
        <div class="home-fragment19">
          <span class="home-text19">
            <span>FAST. SIMPLE. TRUSTED.</span>
            <br />
            <span>BUILT FOR SMART. SWIFT. STRESS-FREE.</span>
            <br />
            <br />
          </span>
        </div>
      </template>
      <template v-slot:heading1>
        <div class="home-fragment20">
          <span class="home-text25">
            <span>SIMPLE POS </span>
            <span>SYSTEM FOR </span>
            <span>SMARTER SALES</span>
          </span>
        </div>
      </template>
    </app-hero17>
    <app-features24>
      <template v-slot:feature1Title>
        <div class="home-fragment21">
          <span class="home-text29">Admin Dashboard</span>
        </div>
      </template>
      <template v-slot:feature2Title>
        <div class="home-fragment22">
          <span class="home-text30">Cashier Interface</span>
        </div>
      </template>
      <template v-slot:feature3Title>
        <div class="home-fragment23">
          <span class="home-text31">QR Scan Ordering</span>
        </div>
      </template>
      <template v-slot:feature1Description>
        <div class="home-fragment24">
          <span class="home-text32">
            Comprehensive management and analytics platform
          </span>
        </div>
      </template>
      <template v-slot:feature2Description>
        <div class="home-fragment25">
          <span class="home-text33">
            Complete point of sale system for efficient transaction management
          </span>
        </div>
      </template>
      <template v-slot:feature3Description>
        <div class="home-fragment26">
          <span class="home-text34">
            Seamless self-service ordering system for customers
          </span>
        </div>
      </template>
    </app-features24>
    <app-cta26>
      <template v-slot:action1>
        <div class="home-fragment27">
          <span class="home-text35">Sign Up Now</span>
        </div>
      </template>
      <template v-slot:content1>
        <div class="home-fragment28">
          <span class="home-text36">
            Sign up for a 30-day free trial and experience the power of our POS
            system.
          </span>
        </div>
      </template>
      <template v-slot:heading1>
        <div class="home-fragment29">
          <span class="home-text37">Ready to streamline your business?</span>
        </div>
      </template>
    </app-cta26>
    <app-features2 rootClassName="features2root-class-name">
      <template v-slot:slogan>
        <div class="home-fragment30">
          <span class="home-text38">About Us</span>
        </div>
      </template>
      <template v-slot:sectionTitle>
        <div class="home-fragment31">
          <span class="home-text39">
            Built on Experience, Designed for Simplicity
          </span>
        </div>
      </template>
      <template v-slot:feature1Title>
        <div class="home-fragment32">
          <span class="home-text40">Easy to Use Interface</span>
        </div>
      </template>
      <template v-slot:feature2Title>
        <div class="home-fragment33">
          <span class="home-text41">Sales Reports</span>
        </div>
      </template>
      <template v-slot:feature3Title>
        <div class="home-fragment34">
          <span class="home-text42">Inventory Tracking</span>
        </div>
      </template>
      <template v-slot:feature4Title>
        <div class="home-fragment35">
          <span class="home-text43">Cloud-Based</span>
        </div>
      </template>
      <template v-slot:feature5Title>
        <div class="home-fragment36">
          <span class="home-text44">Secure System</span>
        </div>
      </template>
      <template v-slot:sectionDescription>
        <div class="home-fragment37">
          <span class="home-text45">
            Makan Smart POS isn&apos;t just another POS system. It&apos;s the
            result of ten years of listening to users like you. We&apos;ve
            meticulously refined our system based on real-world feedback, focusing
            relentlessly on making it powerful yet incredibly simple to operate.
            Our mission is to provide SMEs with tool that enhances efficiency, not
            complicates it.
          </span>
        </div>
      </template>
      <template v-slot:feature1Description>
        <div class="home-fragment38">
          <span class="home-text46">
            Intuitive design that requires minimal training, allowing your staff
            to start processing sales immediately.
          </span>
        </div>
      </template>
      <template v-slot:feature2Description>
        <div class="home-fragment39">
          <span class="home-text47">
            Comprehensive analytics and reporting tools to track your business
            performance in real-time.
          </span>
        </div>
      </template>
      <template v-slot:feature3Description>
        <div class="home-fragment40">
          <span class="home-text48">
            Know what&apos;s in stock with real-time updates.
          </span>
        </div>
      </template>
      <template v-slot:feature4Description>
        <div class="home-fragment41">
          <span class="home-text49">
            Access your business data anywhere, anytime with secure cloud storage
            and automatic backups.
          </span>
        </div>
      </template>
      <template v-slot:feature5Description>
        <div class="home-fragment42">
          <span class="home-text50">
            Enterprise-level security measures to protect your business and
            customer data.
          </span>
        </div>
      </template>
    </app-features2>
    <app-steps2>
      <template v-slot:step1Title>
        <div class="home-fragment43">
          <span class="home-text51">Sign Up for a 30-Day Free Trial</span>
        </div>
      </template>
      <template v-slot:step2Title>
        <div class="home-fragment44">
          <span class="home-text52">Consultation</span>
        </div>
      </template>
      <template v-slot:step3Title>
        <div class="home-fragment45"><span class="home-text53">Setup</span></div>
      </template>
      <template v-slot:step4Title>
        <div class="home-fragment46">
          <span class="home-text54">Go Live</span>
        </div>
      </template>
      <template v-slot:step1Description>
        <div class="home-fragment47">
          <span class="home-text55">
            Fill out the form with your details to get started with our POS
            system. No credit card required.
          </span>
        </div>
      </template>
      <template v-slot:step2Description>
        <div class="home-fragment48">
          <span class="home-text56">
            Our team will contact you for a detailed discussion
          </span>
        </div>
      </template>
      <template v-slot:step3Description>
        <div class="home-fragment49">
          <span class="home-text57">
            We&apos;ll help set up and configure your POS system
          </span>
        </div>
      </template>
      <template v-slot:step4Description>
        <div class="home-fragment50">
          <span class="home-text58">
            Start using your new POS system with full support
          </span>
        </div>
      </template>
    </app-steps2>
    <blog-post-header1
      rootClassName="blog-post-header1root-class-name"
      blogPostImageSrc="/satisfied%20customers.svg"
    >
      <template v-slot:blogPostTitle>
        <div class="home-fragment51">
          <span class="home-text59">
            <span>
              Our
              <span v-html="rawr3fi"></span>
            </span>
            <span class="home-text61">Sastisfied</span>
            <span>Customers</span>
          </span>
        </div>
      </template>
    </blog-post-header1>
    <app-faq2>
      <template v-slot:action>
        <div class="home-fragment52">
          <span class="home-text63">Contact us for more information</span>
        </div>
      </template>
      <template v-slot:content1>
        <div class="home-fragment53">
          <span class="home-text64">
            Find answers to common queries about our POS system below.
          </span>
        </div>
      </template>
      <template v-slot:heading1>
        <div class="home-fragment54">
          <span class="home-text65">Frequently Asked Questions</span>
        </div>
      </template>
      <template v-slot:faq1Answer>
        <div class="home-fragment55">
          <span class="home-text66">
            To sign up for a free trial, simply click on the &apos;Sign Up&apos;
            button on the homepage and submit the contact information, we will
            reach out to you for more information.
          </span>
        </div>
      </template>
      <template v-slot:faq2Answer>
        <div class="home-fragment56">
          <span class="home-text67">
            The POS system includes features such as admin portal access,
            efficient cashiering tools, and seamless QR scan ordering
            capabilities.
          </span>
        </div>
      </template>
      <template v-slot:faq3Answer>
        <div class="home-fragment57">
          <span class="home-text68">
            Yes, we offer customer support for any inquiries or issues you may
            have. You can reach out to our support team via phone.
          </span>
        </div>
      </template>
      <template v-slot:faq4Answer>
        <div class="home-fragment58">
          <span class="home-text69">
            Our standard package includes a tablet, cash drawer, receipt printer,
            and card reader. Custom configurations are available.
          </span>
        </div>
      </template>
      <template v-slot:faq5Answer>
        <div class="home-fragment59">
          <span class="home-text70">
            Our POS system prioritizes security and data protection. We use
            encryption technology to safeguard your information and ensure safe
            transactions.
          </span>
        </div>
      </template>
      <template v-slot:faq1Question>
        <div class="home-fragment60">
          <span class="home-text71">How can I sign up for a free trial?</span>
        </div>
      </template>
      <template v-slot:faq2Question>
        <div class="home-fragment61">
          <span class="home-text72">
            What features are included in the POS system?
          </span>
        </div>
      </template>
      <template v-slot:faq3Question>
        <div class="home-fragment62">
          <span class="home-text73">Is customer support available?</span>
        </div>
      </template>
      <template v-slot:faq4Question>
        <div class="home-fragment63">
          <span class="home-text74">What hardware is included?</span>
        </div>
      </template>
      <template v-slot:faq5Question>
        <div class="home-fragment64">
          <span class="home-text75">How secure is the POS system?</span>
        </div>
      </template>
    </app-faq2>
    <contact-form7 rootClassName="contact-form7root-class-name">
      <template v-slot:phone>
        <div class="home-fragment65">
          <span class="home-text76">+601156579073</span>
        </div>
      </template>
      <template v-slot:action>
        <div class="home-fragment66">
          <span class="home-text77">Contact Us</span>
        </div>
      </template>
      <template v-slot:address>
        <div class="home-fragment67">
          <span class="home-text78">Message us on WhatsApp</span>
        </div>
      </template>
      <template v-slot:content1>
        <div class="home-fragment68">
          <span class="home-text79">Have a question or need support?</span>
        </div>
      </template>
      <template v-slot:content2>
        <div class="home-fragment69">
          <span class="home-text80">
            Our team is here to help you with any inquiries you may have. Feel
            free to reach out to us.
          </span>
        </div>
      </template>
      <template v-slot:heading1>
        <div class="home-fragment70">
          <span class="home-text81">Contact Information</span>
        </div>
      </template>
    </contact-form7>
    <app-footer4 logoSrc="/group%2062.svg">
      <template v-slot:link1>
        <div class="home-fragment71">
          <span class="home-text82">About Us</span>
        </div>
      </template>
      <template v-slot:link2>
        <div class="home-fragment72">
          <span class="home-text83">Contact Us</span>
        </div>
      </template>
      <template v-slot:link3>
        <div class="home-fragment73"><span class="home-text84">FAQs</span></div>
      </template>
      <template v-slot:link4>
        <div class="home-fragment74">
          <span class="home-text85">Features</span>
        </div>
      </template>
      <template v-slot:link5>
        <div class="home-fragment75">
          <span class="home-text86">Sign Up for Free Trial</span>
        </div>
      </template>
      <template v-slot:termsLink>
        <div class="home-fragment76">
          <span class="home-text87">Terms of Services</span>
        </div>
      </template>
      <template v-slot:privacyLink>
        <div class="home-fragment77">
          <span class="home-text88">Privacy Policy</span>
        </div>
      </template>
    </app-footer4>
    <div
      data-thq="slider"
      data-autoplay="true"
      data-navigation="false"
      data-pagination="false"
      class="home-slider swiper"
    >
      <div data-thq="slider-wrapper" class="swiper-wrapper">
        <div
          data-thq="slider-slide"
          class="home-slider-slide1 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="home-slider-slide2 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="home-slider-slide3 swiper-slide"
        ></div>
        <div
          data-thq="slider-slide"
          class="home-slider-slide4 swiper-slide"
        ></div>
      </div>
      <div
        data-thq="slider-pagination"
        class="home-slider-pagination swiper-pagination swiper-pagination-bullets swiper-pagination-horizontal"
      >
        <div
          data-thq="slider-pagination-bullet"
          class="swiper-pagination-bullet"
        ></div>
        <div
          data-thq="slider-pagination-bullet"
          class="swiper-pagination-bullet"
        ></div>
        <div
          data-thq="slider-pagination-bullet"
          class="swiper-pagination-bullet"
        ></div>
        <div
          data-thq="slider-pagination-bullet"
          class="swiper-pagination-bullet"
        ></div>
      </div>
      <div
        data-thq="slider-button-prev"
        class="home-slider-button-prev swiper-button-prev"
      ></div>
      <div
        data-thq="slider-button-next"
        class="home-slider-button-next swiper-button-next"
      ></div>
    </div>
    <div data-thq="thq-dropdown" class="home-thq-dropdown list-item">
      <ul data-thq="thq-dropdown-list" class="home-dropdown-list">
        <li data-thq="thq-dropdown" class="home-dropdown1 list-item">
          <div data-thq="thq-dropdown-toggle" class="home-dropdown-toggle1">
            <span class="home-text89">Sub-menu Item</span>
          </div>
        </li>
        <li data-thq="thq-dropdown" class="home-dropdown2 list-item">
          <div data-thq="thq-dropdown-toggle" class="home-dropdown-toggle2">
            <span class="home-text90">Sub-menu Item</span>
          </div>
        </li>
        <li data-thq="thq-dropdown" class="home-dropdown3 list-item">
          <div data-thq="thq-dropdown-toggle" class="home-dropdown-toggle3">
            <span class="home-text91">Sub-menu Item</span>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import AppNavbar1 from '../components/navbar1'
import AppHero17 from '../components/hero17'
import AppFeatures24 from '../components/features24'
import AppCta26 from '../components/cta26'
import AppFeatures2 from '../components/features2'
import AppSteps2 from '../components/steps2'
import BlogPostHeader1 from '../components/blog-post-header1'
import AppFaq2 from '../components/faq2'
import ContactForm7 from '../components/contact-form7'
import AppFooter4 from '../components/footer4'

export default {
  name: 'Home',
  props: {},
  components: {
    AppNavbar1,
    AppHero17,
    AppFeatures24,
    AppCta26,
    AppFeatures2,
    AppSteps2,
    BlogPostHeader1,
    AppFaq2,
    ContactForm7,
    AppFooter4,
  },
  data() {
    return {
      rawr3fi: ' ',
    }
  },
  head: {
    title: 'Makan POS landing page',
    meta: [
      {
        property: 'og:title',
        content: 'Makan POS landing page',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
 
.home-fragment10 {
  display: contents;
}
 
.home-text10 {
  display: inline-block;
}
 
.home-fragment11 {
  display: contents;
}
 
.home-text11 {
  display: inline-block;
}
 
.home-fragment12 {
  display: contents;
}
 
.home-text12 {
  display: inline-block;
}
 
.home-fragment13 {
  display: contents;
}
 
.home-text13 {
  display: inline-block;
}
 
.home-fragment14 {
  display: contents;
}
 
.home-text14 {
  display: inline-block;
}
 
.home-fragment15 {
  display: contents;
}
 
.home-text15 {
  display: inline-block;
}
 
.home-fragment16 {
  display: contents;
}
 
.home-text16 {
  display: inline-block;
}
 
.home-fragment17 {
  display: contents;
}
 
.home-text17 {
  display: inline-block;
}
 
.home-fragment18 {
  display: contents;
}
 
.home-text18 {
  display: inline-block;
}
 
.home-fragment19 {
  display: contents;
}
 
.home-text19 {
  display: inline-block;
}
 
.home-fragment20 {
  display: contents;
}
 
.home-text25 {
  color: #bf4407;
  display: inline-block;
}
 
.home-fragment21 {
  display: contents;
}
 
.home-text29 {
  display: inline-block;
}
 
.home-fragment22 {
  display: contents;
}
 
.home-text30 {
  display: inline-block;
}
 
.home-fragment23 {
  display: contents;
}
 
.home-text31 {
  display: inline-block;
}
 
.home-fragment24 {
  display: contents;
}
 
.home-text32 {
  display: inline-block;
}
 
.home-fragment25 {
  display: contents;
}
 
.home-text33 {
  display: inline-block;
}
 
.home-fragment26 {
  display: contents;
}
 
.home-text34 {
  display: inline-block;
}
 
.home-fragment27 {
  display: contents;
}
 
.home-text35 {
  display: inline-block;
}
 
.home-fragment28 {
  display: contents;
}
 
.home-text36 {
  display: inline-block;
}
 
.home-fragment29 {
  display: contents;
}
 
.home-text37 {
  display: inline-block;
}
 
.home-fragment30 {
  display: contents;
}
 
.home-text38 {
  display: inline-block;
}
 
.home-fragment31 {
  display: contents;
}
 
.home-text39 {
  color: #bf4407;
  display: inline-block;
}
 
.home-fragment32 {
  display: contents;
}
 
.home-text40 {
  display: inline-block;
  text-align: left;
}
 
.home-fragment33 {
  display: contents;
}
 
.home-text41 {
  display: inline-block;
}
 
.home-fragment34 {
  display: contents;
}
 
.home-text42 {
  display: inline-block;
}
 
.home-fragment35 {
  display: contents;
}
 
.home-text43 {
  display: inline-block;
}
 
.home-fragment36 {
  display: contents;
}
 
.home-text44 {
  display: inline-block;
}
 
.home-fragment37 {
  display: contents;
}
 
.home-text45 {
  display: inline-block;
}
 
.home-fragment38 {
  display: contents;
}
 
.home-text46 {
  display: inline-block;
}
 
.home-fragment39 {
  display: contents;
}
 
.home-text47 {
  display: inline-block;
}
 
.home-fragment40 {
  display: contents;
}
 
.home-text48 {
  display: inline-block;
}
 
.home-fragment41 {
  display: contents;
}
 
.home-text49 {
  display: inline-block;
}
 
.home-fragment42 {
  display: contents;
}
 
.home-text50 {
  display: inline-block;
}
 
.home-fragment43 {
  display: contents;
}
 
.home-text51 {
  display: inline-block;
}
 
.home-fragment44 {
  display: contents;
}
 
.home-text52 {
  display: inline-block;
}
 
.home-fragment45 {
  display: contents;
}
 
.home-text53 {
  display: inline-block;
}
 
.home-fragment46 {
  display: contents;
}
 
.home-text54 {
  display: inline-block;
}
 
.home-fragment47 {
  display: contents;
}
 
.home-text55 {
  display: inline-block;
}
 
.home-fragment48 {
  display: contents;
}
 
.home-text56 {
  display: inline-block;
}
 
.home-fragment49 {
  display: contents;
}
 
.home-text57 {
  display: inline-block;
}
 
.home-fragment50 {
  display: contents;
}
 
.home-text58 {
  display: inline-block;
}
 
.home-fragment51 {
  display: contents;
}
 
.home-text59 {
  display: inline-block;
}
 
.home-text61 {
  color: #e47709;
}
 
.home-fragment52 {
  display: contents;
}
 
.home-text63 {
  display: inline-block;
}
 
.home-fragment53 {
  display: contents;
}
 
.home-text64 {
  display: inline-block;
}
 
.home-fragment54 {
  display: contents;
}
 
.home-text65 {
  display: inline-block;
}
 
.home-fragment55 {
  display: contents;
}
 
.home-text66 {
  display: inline-block;
}
 
.home-fragment56 {
  display: contents;
}
 
.home-text67 {
  display: inline-block;
}
 
.home-fragment57 {
  display: contents;
}
 
.home-text68 {
  display: inline-block;
}
 
.home-fragment58 {
  display: contents;
}
 
.home-text69 {
  display: inline-block;
}
 
.home-fragment59 {
  display: contents;
}
 
.home-text70 {
  display: inline-block;
}
 
.home-fragment60 {
  display: contents;
}
 
.home-text71 {
  display: inline-block;
}
 
.home-fragment61 {
  display: contents;
}
 
.home-text72 {
  display: inline-block;
}
 
.home-fragment62 {
  display: contents;
}
 
.home-text73 {
  display: inline-block;
}
 
.home-fragment63 {
  display: contents;
}
 
.home-text74 {
  display: inline-block;
}
 
.home-fragment64 {
  display: contents;
}
 
.home-text75 {
  display: inline-block;
}
 
.home-fragment65 {
  display: contents;
}
 
.home-text76 {
  display: inline-block;
}
 
.home-fragment66 {
  display: contents;
}
 
.home-text77 {
  display: inline-block;
}
 
.home-fragment67 {
  display: contents;
}
 
.home-text78 {
  display: inline-block;
}
 
.home-fragment68 {
  display: contents;
}
 
.home-text79 {
  display: inline-block;
}
 
.home-fragment69 {
  display: contents;
}
 
.home-text80 {
  display: inline-block;
}
 
.home-fragment70 {
  display: contents;
}
 
.home-text81 {
  display: inline-block;
}
 
.home-fragment71 {
  display: contents;
}
 
.home-text82 {
  display: inline-block;
}
 
.home-fragment72 {
  display: contents;
}
 
.home-text83 {
  display: inline-block;
}
 
.home-fragment73 {
  display: contents;
}
 
.home-text84 {
  display: inline-block;
}
 
.home-fragment74 {
  display: contents;
}
 
.home-text85 {
  display: inline-block;
}
 
.home-fragment75 {
  display: contents;
}
 
.home-text86 {
  display: inline-block;
}
 
.home-fragment76 {
  display: contents;
}
 
.home-text87 {
  display: inline-block;
}
 
.home-fragment77 {
  display: contents;
}
 
.home-text88 {
  display: inline-block;
}
 
.home-slider {
  width: 500px;
  height: 300px;
  display: inline-block;
}
 
.home-slider-slide1 {
  display: flex ;
  background-size: 100%;
  background-image: url("https://images.unsplash.com/photo-1542273917363-3b1817f69a2d?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MzUyMzY3NXw&ixlib=rb-4.1.0&q=80&w=1080");
}
 
.home-slider-slide2 {
  display: flex ;
  background-size: 100%;
  background-image: url("https://images.unsplash.com/photo-1580133318324-f2f76d987dd8?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MzUyMzY4NHw&ixlib=rb-4.1.0&q=80&w=1080");
}
 
.home-slider-slide3 {
  display: flex ;
  background-size: 100%;
  background-image: url("https://images.unsplash.com/photo-1493246507139-91e8fad9978e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MzUyMzY4NHw&ixlib=rb-4.1.0&q=80&w=1080");
}
 
.home-slider-slide4 {
  display: flex ;
  background-size: 100%;
  background-image: url("https://images.unsplash.com/photo-1504608524841-42fe6f032b4b?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTc1MzUyMzY4NHw&ixlib=rb-4.1.0&q=80&w=1080");
}
 
.home-slider-pagination {
  display: none;
}
 
.home-slider-button-prev {
  display: none;
}
 
.home-slider-button-next {
  display: none;
}
 
.home-thq-dropdown {
  cursor: pointer;
  display: inline-block;
  position: relative;
  border-radius: var(--dl-layout-radius-radius2);
}
 
.home-dropdown-list {
  left: 0%;
  width: max-content;
  display: none;
  z-index: 100;
  position: absolute;
  min-width: 100%;
  transition: 0.3s;
  align-items: stretch;
  border-color: #D9D9D9;
  border-width: 1px;
  border-radius: var(--dl-layout-radius-radius4);
  flex-direction: column;
  list-style-type: none;
  list-style-position: inside;
}
 
.home-dropdown1 {
  cursor: pointer;
  display: inline-block;
  position: relative;
  border-radius: var(--dl-layout-radius-radius2);
}
 
.home-dropdown-toggle1 {
  fill: #595959;
  color: #595959;
  width: 100%;
  display: inline-flex;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  border-radius: var(--dl-layout-radius-radius4);
  padding-right: var(--dl-layout-space-unit);
  padding-bottom: var(--dl-layout-space-halfunit);
}
 
.home-dropdown-toggle1:hover {
  fill: #fff;
  color: #fff;
  background-color: #595959;
}
 
.home-text89 {
  width: 100%;
  cursor: pointer;
  display: flex;
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
}
 
.home-dropdown2 {
  cursor: pointer;
  display: inline-block;
  position: relative;
  border-radius: var(--dl-layout-radius-radius2);
}
 
.home-dropdown-toggle2 {
  fill: #595959;
  color: #595959;
  width: 100%;
  display: inline-flex;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  border-radius: var(--dl-layout-radius-radius4);
  padding-right: var(--dl-layout-space-unit);
  padding-bottom: var(--dl-layout-space-halfunit);
}
 
.home-dropdown-toggle2:hover {
  fill: #fff;
  color: #fff;
  background-color: #595959;
}
 
.home-text90 {
  width: 100%;
  cursor: pointer;
  display: flex;
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
}
 
.home-dropdown3 {
  cursor: pointer;
  display: inline-block;
  position: relative;
  border-radius: var(--dl-layout-radius-radius2);
}
 
.home-dropdown-toggle3 {
  fill: #595959;
  color: #595959;
  width: 100%;
  display: inline-flex;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-layout-space-halfunit);
  padding-left: var(--dl-layout-space-unit);
  border-radius: var(--dl-layout-radius-radius4);
  padding-right: var(--dl-layout-space-unit);
  padding-bottom: var(--dl-layout-space-halfunit);
}
 
.home-dropdown-toggle3:hover {
  fill: #fff;
  color: #fff;
  background-color: #595959;
}
 
.home-text91 {
  width: 100%;
  cursor: pointer;
  display: flex;
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
}
 
@media(max-width: 479px) {
  .home-text59 {
    font-size: 25px;
  }
  .home-text61 {
    color: #e47709;
  }
}
</style>
