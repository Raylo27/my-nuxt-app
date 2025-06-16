<script setup>
useHead({
  title: 'Raylen Williams | Software Developer',
  meta: [
    { name: 'description', content: 'Software developer from Fort Worth. Lover of all things programming.' }
  ]
})
</script>

<template>
  <div class="container mx-auto flex h-full min-h-screen flex-col px-8 py-4">
    <nav class="mb-8">
      <a href="/" class="text-3xl text-black-primary dark:text-white-primary">Raylen Williams</a>
    </nav>
    <div class="flex w-full flex-col gap-12 pb-8">
      <section id="about" class="grid grid-cols-1 items-center gap-4 lg:grid-cols-2">
        <div class="flex flex-col gap-4">
          <h1 class="text-5xl font-bold text-black-primary lg:text-6xl dark:text-white-primary">
            <span class="text-[color:var(--highlight)] duration-300">Hi,</span> I'm Raylen
          </h1>
          <p class="text-xl text-black-primary dark:text-white-primary">
            I am a software developer from Fort Worth. Lover of all things programming. Lately I have been...
          </p>
          <p class="text-dark-primary text-xl dark:text-white-primary">
            I am a Junior Computer Science major at the University Of PVAMU.
          </p>
          <div class="flex gap-4">
            <!-- Social links here -->
            <a aria-label="Link to my Github" href="https://github.com/Raylo27" rel="noreferrer noopener" target="_blank">
              <svg fill="none" viewBox="0 0 61 65" xmlns="http://www.w3.org/2000/svg" class="aspect-square size-12 rounded-sm bg-black-primary p-2 text-white-primary duration-300 hover:text-[color:var(--highlight)] dark:bg-white-primary dark:text-black-primary"><path d="M60.258 23.833A17.781 17.781 0 0 0 56.3 12.715a17.932 17.932 0 0 0-.772-10.813 2.385 2.385 0 0 0-1.503-1.38c-.966-.33-4.621-.951-12.07 3.876a35.975 35.975 0 0 0-9.82-1.185c-3.317-.06-6.627.34-9.835 1.186C14.66-.54 10.686.26 9.886.495a2.414 2.414 0 0 0-1.504 1.407 17.93 17.93 0 0 0-.8 10.786 16.849 16.849 0 0 0-3.944 11.2c0 15.255 8.73 19.862 16.73 21.49a12.89 12.89 0 0 0-.84 3.13 1.336 1.336 0 0 0 0 .346v4.22c-7.283.607-8.841-3.655-8.993-4.138a3.208 3.208 0 0 0-.126-.331 12.207 12.207 0 0 0-6.896-6.138 2.414 2.414 0 1 0-1.53 4.58 7.295 7.295 0 0 1 3.917 3.35c.966 3.131 4.911 8.083 13.6 7.531v3.973a2.414 2.414 0 0 0 4.828 0V49.032a6.899 6.899 0 0 1 1.75-3.766A2.4 2.4 0 0 0 24.7 41.13c-8.414-.98-16.192-3.752-16.192-17.338h-.001a11.867 11.867 0 0 1 3.53-8.855 2.564 2.564 0 0 0 .553-2.565 11.955 11.955 0 0 1-.152-7.31 20.979 20.979 0 0 1 8.151 3.82 2.47 2.47 0 0 0 2.124.29 29.81 29.81 0 0 1 9.463-1.283c3.198-.084 6.388.35 9.448 1.283a2.457 2.457 0 0 0 2.124-.29 21.672 21.672 0 0 1 7.807-3.794 12.21 12.21 0 0 1-.18 7.38 2.388 2.388 0 0 0 .47 2.345 13.437 13.437 0 0 1 3.627 8.979c0 13.558-8.18 16.372-16.193 17.338a2.401 2.401 0 0 0-1.158 4.318c.855.648 1.848 2.468 1.848 5.516v10.924a2.413 2.413 0 1 0 4.827 0V50.964a14.707 14.707 0 0 0-1.034-5.614c6.482-1.378 16.496-5.64 16.496-21.517Z" fill="currentColor"></path></svg>
            </a>
            <a aria-label="Link to my LinkedIn" href="https://www.linkedin.com/in/raylen-williams" rel="noreferrer noopener" target="_blank">
              <svg viewBox="0 0 448 448" xmlns="http://www.w3.org/2000/svg" class="aspect-square size-12 rounded-sm bg-black-primary p-2 text-white-primary duration-300 hover:text-[color:var(--highlight)] dark:bg-white-primary dark:text-black-primary"><path d="M100.28 448H7.4V148.9h92.88V448ZM53.79 108.1C24.09 108.1 0 83.5 0 53.8a53.79 53.79 0 0 1 107.58 0c0 29.7-24.1 54.3-53.79 54.3ZM447.9 448h-92.68V302.4c0-34.7-.7-79.2-48.29-79.2-48.29 0-55.69 37.7-55.69 76.7V448h-92.78V148.9h89.08v40.8h1.3c12.4-23.5 42.69-48.3 87.88-48.3 94 0 111.28 61.9 111.28 142.3V448h-.1Z" fill="currentColor"></path></svg>
            </a>
          </div>
        </div>

       <picture class="order-first mx-auto w-9/12 lg:order-1 lg:mr-0 lg:w-fit lg:text-right max-w-xs xl:max-w-full"><!--[--><source type="image/webp" sizes="(max-width: 640px) 320px, (max-width: 768px) 640px, (max-width: 1024px) 768px, (max-width: 1280px) 1024px, (max-width: 1536px) 1280px, 1536px" srcset="/public/RaylenHomepic.png 320w, /public/RaylenHomepic.png 640w, /public/RaylenHomepic.png 768w, /public/RaylenHomepic.png 1024w, /public/RaylenHomepic.png 1280w, /public/RaylenHomepic.png 1536w, /public/RaylenHomepic.png 2048w, /public/RaylenHomepic.png 2560w, /public/RaylenHomepic.png 3072w"><!--]--><img alt="Image of Mads Hougesen" onerror="this.setAttribute('data-error', 1)" class="mr-auto lg:mr-0 ml-auto lg:text-right" data-nuxt-pic="" src="/public/RaylenHomepic.png" sizes="(max-width: 640px) 320px, (max-width: 768px) 640px, (max-width: 1024px) 768px, (max-width: 1280px) 1024px, (max-width: 1536px) 1280px, 1536px" srcset="/public/RaylenHomepic.png 320w, /public/RaylenHomepic.png 640w, /public/RaylenHomepic.png 768w, /public/RaylenHomepic.png 1024w, /public/RaylenHomepic.png 1280w, /public/RaylenHomepic.png 1536w, /public/RaylenHomepic.png 2048w, /public/RaylenHomepic.png 2560w, /public/RaylenHomepic.png 3072w"></picture>
      </section>

      <!-- Projects Section -->
      <section id="projects" class="flex flex-col gap-8">
        <h2 class="text-4xl font-bold text-black-primary lg:text-5xl dark:text-white-primary">Projects</h2>
        <div class="grid grid-cols-1 gap-8 lg:grid-cols-3">
          <!-- Repeat this block for each project -->
          <div class="flex flex-col gap-1 rounded-sm bg-white-secondary p-4 dark:bg-black-secondary border border-[#ffffff2e]">
            <a class="text-dark-primary text-xl font-semibold dark:text-white-primary" href="https://trimbletech-attendance.netlify.app" rel="noreferrer noopener" target="_blank">Attendance Recovery (Senior Project)</a>
            <p class="mb-5 text-dark-secondary dark:text-white-primary">During my senior year of high school, I noticed that many students were unaware they needed attendance recovery—a requirement that could prevent them from graduating on time. There was no system in place to notify students of their attendance status, which led to confusion and last-minute surprises.

To solve this problem, I designed and built a simple web application that allows seniors to enter their student ID number and instantly see whether they need attendance recovery, along with details about the assigned room and time. This tool helped ensure that all seniors had clear, accessible information about their attendance requirements, making it easier for them to take action and avoid graduation delays.</p>
            <div class="mt-auto flex gap-2">
              <div class="rounded-sm px-2 py-1" style="background-color:#dea584;">
                <p class="text-sm font-medium brightness-50" style="color:#dea584;">Nuxt.js</p>
              </div>
              <div class="rounded-sm px-2 py-1" style="background-color:#f1e05a;">
                <p class="text-sm font-medium brightness-50" style="color:#f1e05a;">JavaScript</p>
              </div>
              <div class="rounded-sm px-2 py-1" style="background-color:#3178c6;">
                <p class="text-sm font-medium brightness-50" style="color:#3178c6;">Vue</p>
              </div>
            </div>
          </div>
          <!-- ...add more project cards here... -->
        </div>
      </section>

      <!-- Interest Section -->
      <section class="flex flex-col gap-4">
        <h2 class="text-4xl font-bold text-black-primary lg:text-5xl dark:text-white-primary mb-4">Interest</h2>
        <a href="https://www.foodconnectgroup.org/news/tech-led-solutions-to-address-food-insecurity-during-a-global-pandemic" class="transition-300 text-xl underline">Tech Led Solutions to Address Food Insecurity during a Global Pandemicy</a>
        <a href="https://medium.com/@ZaraSyed_GoodIntentions/bridging-the-gap-tech-solutions-for-food-insecurity-and-waste-reduction-61202c661d33" class="transition-300 text-xl underline">Bridging the Gap: Tech Solutions for Food Insecurity and Waste Reduction</a>
        <a href="https://www.ama.org/2025/03/11/why-low-income-consumers-avoid-healthy-foods-and-how-to-change-their-minds/" class="transition-300 text-xl underline">Why Low-Income Consumers Avoid Healthy Foods—and How to Change Their Minds</a>
      </section>

      <!-- Contact Section -->
      <section id="contact" class="flex flex-col gap-2">
        <h2 class="text-4xl font-bold text-black-primary lg:text-5xl dark:text-white-primary">Wanna get in touch?</h2>
        <p class="text-xl text-black-primary dark:text-white-primary">I am always available for exciting discussions</p>
        <div>
          <div class="my-2 flex items-center gap-2">
            <!-- Email SVG icon here -->
            <a class="text-xl text-black-primary underline dark:text-white-primary" href="mailto:jabari22004@gmail.com">jabari22004@gmail.com</a>
          </div>
          <div class="mb-4 flex items-center gap-2">
            <!-- Location SVG icon here -->
            <p class="text-xl text-black-primary dark:text-white-primary">Fort Worth, TX</p>
          </div>
        </div>
        <div class="flex gap-4">
          <!-- Social links again if needed -->
        </div>
      </section>
    </div>
  </div>
</template>


 <style>
     /*! tailwindcss v4.1.8 | MIT License | https://tailwindcss.com */

     @layer properties {
         @supports ((-webkit-hyphens:none) and (not (margin-trim:inline))) or ((-moz-orient:inline) and (not (color:rgb(from red r g b)))) {
             *, ::backdrop, :after, :before {
                 --tw-border-style: solid;
                 --tw-font-weight: initial;
                 --tw-blur: initial;
                 --tw-brightness: initial;
                 --tw-contrast: initial;
                 --tw-grayscale: initial;
                 --tw-hue-rotate: initial;
                 --tw-invert: initial;
                 --tw-opacity: initial;
                 --tw-saturate: initial;
                 --tw-sepia: initial;
                 --tw-drop-shadow: initial;
                 --tw-drop-shadow-color: initial;
                 --tw-drop-shadow-alpha: 100%;
                 --tw-drop-shadow-size: initial;
                 --tw-duration: initial
             }
         }
     }

     @layer theme {
         :host, :root {
             --font-sans: Inter,ui-sans-serif,system-ui,sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
             --font-mono: ui-monospace,SFMono-Regular,Menlo,Monaco,Consolas,"Liberation Mono","Courier New",monospace;
             --color-gray-200: oklch(92.8% .006 264.531);
             --spacing: .25rem;
             --container-xs: 20rem;
             --text-sm: .875rem;
             --text-sm--line-height: 1.42857;
             --text-base: 1rem;
             --text-base--line-height: 1.5;
             --text-lg: 1.125rem;
             --text-lg--line-height: 1.55556;
             --text-xl: 1.25rem;
             --text-xl--line-height: 1.4;
             --text-3xl: 1.875rem;
             --text-3xl--line-height: 1.2;
             --text-4xl: 2.25rem;
             --text-4xl--line-height: 1.11111;
             --text-5xl: 3rem;
             --text-5xl--line-height: 1;
             --text-6xl: 3.75rem;
             --text-6xl--line-height: 1;
             --font-weight-medium: 500;
             --font-weight-semibold: 600;
             --font-weight-bold: 700;
             --radius-sm: .25rem;
             --radius-lg: .5rem;
             --default-transition-duration: .15s;
             --default-transition-timing-function: cubic-bezier(.4,0,.2,1);
             --default-font-family: var(--font-sans);
             --default-mono-font-family: var(--font-mono);
             --color-black-primary: #101010;
             --color-black-secondary: #151515;
             --color-white-primary: #f7f7f7;
             --color-white-secondary: #eee
         }
     }

     @layer base {
         *, ::backdrop, :after, :before {
             border: 0 solid;
             box-sizing: border-box;
             margin: 0;
             padding: 0
         }

         ::file-selector-button {
             border: 0 solid;
             box-sizing: border-box;
             margin: 0;
             padding: 0
         }

         :host, html {
             -webkit-text-size-adjust: 100%;
             font-family: var(--default-font-family,ui-sans-serif,system-ui,sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji");
             font-feature-settings: var(--default-font-feature-settings,normal);
             font-variation-settings: var(--default-font-variation-settings,normal);
             line-height: 1.5;
             -moz-tab-size: 4;
             -o-tab-size: 4;
             tab-size: 4;
             -webkit-tap-highlight-color: transparent
         }

         hr {
             border-top-width: 1px;
             color: inherit;
             height: 0
         }

         abbr:where([title]) {
             -webkit-text-decoration: underline dotted;
             text-decoration: underline dotted
         }

         h1, h2, h3, h4, h5, h6 {
             font-size: inherit;
             font-weight: inherit
         }

         a {
             color: inherit;
             -webkit-text-decoration: inherit;
             text-decoration: inherit
         }

         b, strong {
             font-weight: bolder
         }

         code, kbd, pre, samp {
             font-family: var(--default-mono-font-family,ui-monospace,SFMono-Regular,Menlo,Monaco,Consolas,"Liberation Mono","Courier New",monospace);
             font-feature-settings: var(--default-mono-font-feature-settings,normal);
             font-size: 1em;
             font-variation-settings: var(--default-mono-font-variation-settings,normal)
         }

         small {
             font-size: 80%
         }

         sub, sup {
             font-size: 75%;
             line-height: 0;
             position: relative;
             vertical-align: baseline
         }

         sub {
             bottom: -.25em
         }

         sup {
             top: -.5em
         }

         table {
             border-collapse: collapse;
             border-color: inherit;
             text-indent: 0
         }

         :-moz-focusring {
             outline: auto
         }

         progress {
             vertical-align: baseline
         }

         summary {
             display: list-item
         }

         menu, ol, ul {
             list-style: none
         }

         audio, canvas, embed, iframe, img, object, svg, video {
             display: block;
             vertical-align: middle
         }

         img, video {
             height: auto;
             max-width: 100%
         }

         button, input, optgroup, select, textarea {
             background-color: #0000;
             border-radius: 0;
             color: inherit;
             font: inherit;
             font-feature-settings: inherit;
             font-variation-settings: inherit;
             letter-spacing: inherit;
             opacity: 1
         }

         ::file-selector-button {
             background-color: #0000;
             border-radius: 0;
             color: inherit;
             font: inherit;
             font-feature-settings: inherit;
             font-variation-settings: inherit;
             letter-spacing: inherit;
             opacity: 1
         }

         :where(select:is([multiple],[size])) optgroup {
             font-weight: bolder
         }

             :where(select:is([multiple],[size])) optgroup option {
                 padding-inline-start: 20px
             }

         ::file-selector-button {
             margin-inline-end: 4px
         }

         ::-moz-placeholder {
             opacity: 1
         }

         ::placeholder {
             opacity: 1
         }

         @supports (not (-webkit-appearance:-apple-pay-button)) or (contain-intrinsic-size:1px) {
             ::-moz-placeholder {
                 color: currentColor
             }

             ::placeholder {
                 color: currentColor
             }

             @supports (color:color-mix(in lab,red,red)) {
                 ::-moz-placeholder {
                     color: color-mix(in oklab,currentcolor 50%,transparent)
                 }

                 ::placeholder {
                     color: color-mix(in oklab,currentcolor 50%,transparent)
                 }
             }
         }

         textarea {
             resize: vertical
         }

         ::-webkit-search-decoration {
             -webkit-appearance: none
         }

         ::-webkit-date-and-time-value {
             min-height: 1lh;
             text-align: inherit
         }

         ::-webkit-datetime-edit {
             display: inline-flex
         }

         ::-webkit-datetime-edit-fields-wrapper {
             padding: 0
         }

         ::-webkit-datetime-edit, ::-webkit-datetime-edit-year-field {
             padding-block: 0
         }

         ::-webkit-datetime-edit-day-field, ::-webkit-datetime-edit-month-field {
             padding-block: 0
         }

         ::-webkit-datetime-edit-hour-field, ::-webkit-datetime-edit-minute-field {
             padding-block: 0
         }

         ::-webkit-datetime-edit-millisecond-field, ::-webkit-datetime-edit-second-field {
             padding-block: 0
         }

         ::-webkit-datetime-edit-meridiem-field {
             padding-block: 0
         }

         :-moz-ui-invalid {
             box-shadow: none
         }

         button, input:where([type=button],[type=reset],[type=submit]) {
             -webkit-appearance: button;
             -moz-appearance: button;
             appearance: button
         }

         ::file-selector-button {
             -webkit-appearance: button;
             -moz-appearance: button;
             appearance: button
         }

         ::-webkit-inner-spin-button, ::-webkit-outer-spin-button {
             height: auto
         }

         [hidden]:where(:not([hidden=until-found])) {
             display: none !important
         }

         *, ::backdrop, :after, :before {
             border-color: var(--color-gray-200,currentColor)
         }

         ::file-selector-button {
             border-color: var(--color-gray-200,currentColor)
         }
     }

     @layer components;

     @layer utilities {
         .static {
             position: static
         }

         .order-first {
             order: -9999
         }

         .container {
             width: 100%
         }

         @media (min-width:40rem) {
             .container {
                 max-width: 40rem
             }
         }

         @media (min-width:48rem) {
             .container {
                 max-width: 48rem
             }
         }

         @media (min-width:64rem) {
             .container {
                 max-width: 64rem
             }
         }

         @media (min-width:80rem) {
             .container {
                 max-width: 80rem
             }
         }

         @media (min-width:96rem) {
             .container {
                 max-width: 96rem
             }
         }

         .m-auto\! {
             margin: auto !important
         }

         .mx-auto {
             margin-inline: auto
         }

         .my-2 {
             margin-block: calc(var(--spacing)*2)
         }

         .prose {
             color: var(--tw-prose-body);
             max-width: 65ch
         }

             .prose :where(p):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-bottom: 1.25em;
                 margin-top: 1.25em
             }

             .prose :where([class~=lead]):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: var(--tw-prose-lead);
                 font-size: 1.25em;
                 line-height: 1.6;
                 margin-bottom: 1.2em;
                 margin-top: 1.2em
             }

             .prose :where(a):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: var(--tw-prose-links);
                 font-weight: 500;
                 text-decoration: underline
             }

             .prose :where(strong):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: var(--tw-prose-bold);
                 font-weight: 600
             }

             .prose :where(a strong):not(:where([class~=not-prose],[class~=not-prose] *)), .prose :where(blockquote strong):not(:where([class~=not-prose],[class~=not-prose] *)), .prose :where(thead th strong):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: inherit
             }

             .prose :where(ol):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 list-style-type: decimal;
                 margin-bottom: 1.25em;
                 margin-top: 1.25em;
                 padding-inline-start: 1.625em
             }

             .prose :where(ol[type=A]):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 list-style-type: upper-alpha
             }

             .prose :where(ol[type=a]):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 list-style-type: lower-alpha
             }

             .prose :where(ol[type=A s]):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 list-style-type: upper-alpha
             }

             .prose :where(ol[type=a s]):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 list-style-type: lower-alpha
             }

             .prose :where(ol[type=I]):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 list-style-type: upper-roman
             }

             .prose :where(ol[type=i]):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 list-style-type: lower-roman
             }

             .prose :where(ol[type=I s]):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 list-style-type: upper-roman
             }

             .prose :where(ol[type=i s]):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 list-style-type: lower-roman
             }

             .prose :where(ol[type="1"]):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 list-style-type: decimal
             }

             .prose :where(ul):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 list-style-type: disc;
                 margin-bottom: 1.25em;
                 margin-top: 1.25em;
                 padding-inline-start: 1.625em
             }

             .prose :where(ol>li):not(:where([class~=not-prose],[class~=not-prose] *))::marker {
                 color: var(--tw-prose-counters);
                 font-weight: 400
             }

             .prose :where(ul>li):not(:where([class~=not-prose],[class~=not-prose] *))::marker {
                 color: var(--tw-prose-bullets)
             }

             .prose :where(dt):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: var(--tw-prose-headings);
                 font-weight: 600;
                 margin-top: 1.25em
             }

             .prose :where(hr):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 border-color: var(--tw-prose-hr);
                 border-top-width: 1px;
                 margin-bottom: 3em;
                 margin-top: 3em
             }

             .prose :where(blockquote):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 border-inline-start-color: var(--tw-prose-quote-borders);
                 border-inline-start-width: .25rem;
                 color: var(--tw-prose-quotes);
                 font-style: italic;
                 font-weight: 500;
                 margin-bottom: 1.6em;
                 margin-top: 1.6em;
                 padding-inline-start: 1em;
                 quotes: "“""”""‘""’"
             }

             .prose :where(blockquote p:first-of-type):not(:where([class~=not-prose],[class~=not-prose] *)):before {
                 content: open-quote
             }

             .prose :where(blockquote p:last-of-type):not(:where([class~=not-prose],[class~=not-prose] *)):after {
                 content: close-quote
             }

             .prose :where(h1):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: var(--tw-prose-headings);
                 font-size: 2.25em;
                 font-weight: 800;
                 line-height: 1.11111;
                 margin-bottom: .888889em;
                 margin-top: 0
             }

             .prose :where(h1 strong):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: inherit;
                 font-weight: 900
             }

             .prose :where(h2):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: var(--tw-prose-headings);
                 font-size: 1.5em;
                 font-weight: 700;
                 line-height: 1.33333;
                 margin-bottom: 1em;
                 margin-top: 2em
             }

             .prose :where(h2 strong):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: inherit;
                 font-weight: 800
             }

             .prose :where(h3):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: var(--tw-prose-headings);
                 font-size: 1.25em;
                 font-weight: 600;
                 line-height: 1.6;
                 margin-bottom: .6em;
                 margin-top: 1.6em
             }

             .prose :where(h3 strong):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: inherit;
                 font-weight: 700
             }

             .prose :where(h4):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: var(--tw-prose-headings);
                 font-weight: 600;
                 line-height: 1.5;
                 margin-bottom: .5em;
                 margin-top: 1.5em
             }

             .prose :where(h4 strong):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: inherit;
                 font-weight: 700
             }

             .prose :where(img):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-bottom: 2em;
                 margin-top: 2em
             }

             .prose :where(picture):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 display: block;
                 margin-bottom: 2em;
                 margin-top: 2em
             }

             .prose :where(video):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-bottom: 2em;
                 margin-top: 2em
             }

             .prose :where(kbd):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 border-radius: .3125rem;
                 box-shadow: 0 0 0 1px rgb(var(--tw-prose-kbd-shadows)/10%),0 3px rgb(var(--tw-prose-kbd-shadows)/10%);
                 color: var(--tw-prose-kbd);
                 font-family: inherit;
                 font-size: .875em;
                 font-weight: 500;
                 padding-inline-end: .375em;
                 padding-bottom: .1875em;
                 padding-top: .1875em;
                 padding-inline-start: .375em
             }

             .prose :where(code):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: var(--tw-prose-code);
                 font-size: .875em;
                 font-weight: 600
             }

                 .prose :where(code):not(:where([class~=not-prose],[class~=not-prose] *)):after, .prose :where(code):not(:where([class~=not-prose],[class~=not-prose] *)):before {
                     content: "`"
                 }

             .prose :where(a code):not(:where([class~=not-prose],[class~=not-prose] *)), .prose :where(h1 code):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: inherit
             }

             .prose :where(h2 code):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: inherit;
                 font-size: .875em
             }

             .prose :where(h3 code):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: inherit;
                 font-size: .9em
             }

             .prose :where(blockquote code):not(:where([class~=not-prose],[class~=not-prose] *)), .prose :where(h4 code):not(:where([class~=not-prose],[class~=not-prose] *)), .prose :where(thead th code):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: inherit
             }

             .prose :where(pre):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 background-color: var(--tw-prose-pre-bg);
                 border-radius: .375rem;
                 color: var(--tw-prose-pre-code);
                 font-size: .875em;
                 font-weight: 400;
                 line-height: 1.71429;
                 margin-bottom: 1.71429em;
                 margin-top: 1.71429em;
                 overflow-x: auto;
                 padding-inline-end: 1.14286em;
                 padding-bottom: .857143em;
                 padding-top: .857143em;
                 padding-inline-start: 1.14286em
             }

             .prose :where(pre code):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 background-color: #0000;
                 border-radius: 0;
                 border-width: 0;
                 color: inherit;
                 font-family: inherit;
                 font-size: inherit;
                 font-weight: inherit;
                 line-height: inherit;
                 padding: 0
             }

                 .prose :where(pre code):not(:where([class~=not-prose],[class~=not-prose] *)):after, .prose :where(pre code):not(:where([class~=not-prose],[class~=not-prose] *)):before {
                     content: none
                 }

             .prose :where(table):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 font-size: .875em;
                 line-height: 1.71429;
                 margin-bottom: 2em;
                 margin-top: 2em;
                 table-layout: auto;
                 width: 100%
             }

             .prose :where(thead):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 border-bottom-color: var(--tw-prose-th-borders);
                 border-bottom-width: 1px
             }

             .prose :where(thead th):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: var(--tw-prose-headings);
                 font-weight: 600;
                 padding-inline-end: .571429em;
                 padding-bottom: .571429em;
                 padding-inline-start: .571429em;
                 vertical-align: bottom
             }

             .prose :where(tbody tr):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 border-bottom-color: var(--tw-prose-td-borders);
                 border-bottom-width: 1px
             }

             .prose :where(tbody tr:last-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 border-bottom-width: 0
             }

             .prose :where(tbody td):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 vertical-align: baseline
             }

             .prose :where(tfoot):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 border-top-color: var(--tw-prose-th-borders);
                 border-top-width: 1px
             }

             .prose :where(tfoot td):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 vertical-align: top
             }

             .prose :where(th,td):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 text-align: start
             }

             .prose :where(figure>*):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-bottom: 0;
                 margin-top: 0
             }

             .prose :where(figcaption):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 color: var(--tw-prose-captions);
                 font-size: .875em;
                 line-height: 1.42857;
                 margin-top: .857143em
             }

         .prose {
             --tw-prose-body: oklch(37.3% .034 259.733);
             --tw-prose-headings: oklch(21% .034 264.665);
             --tw-prose-lead: oklch(44.6% .03 256.802);
             --tw-prose-links: oklch(21% .034 264.665);
             --tw-prose-bold: oklch(21% .034 264.665);
             --tw-prose-counters: oklch(55.1% .027 264.364);
             --tw-prose-bullets: oklch(87.2% .01 258.338);
             --tw-prose-hr: oklch(92.8% .006 264.531);
             --tw-prose-quotes: oklch(21% .034 264.665);
             --tw-prose-quote-borders: oklch(92.8% .006 264.531);
             --tw-prose-captions: oklch(55.1% .027 264.364);
             --tw-prose-kbd: oklch(21% .034 264.665);
             --tw-prose-kbd-shadows: NaN NaN NaN;
             --tw-prose-code: oklch(21% .034 264.665);
             --tw-prose-pre-code: oklch(92.8% .006 264.531);
             --tw-prose-pre-bg: oklch(27.8% .033 256.848);
             --tw-prose-th-borders: oklch(87.2% .01 258.338);
             --tw-prose-td-borders: oklch(92.8% .006 264.531);
             --tw-prose-invert-body: oklch(87.2% .01 258.338);
             --tw-prose-invert-headings: #fff;
             --tw-prose-invert-lead: oklch(70.7% .022 261.325);
             --tw-prose-invert-links: #fff;
             --tw-prose-invert-bold: #fff;
             --tw-prose-invert-counters: oklch(70.7% .022 261.325);
             --tw-prose-invert-bullets: oklch(44.6% .03 256.802);
             --tw-prose-invert-hr: oklch(37.3% .034 259.733);
             --tw-prose-invert-quotes: oklch(96.7% .003 264.542);
             --tw-prose-invert-quote-borders: oklch(37.3% .034 259.733);
             --tw-prose-invert-captions: oklch(70.7% .022 261.325);
             --tw-prose-invert-kbd: #fff;
             --tw-prose-invert-kbd-shadows: 255 255 255;
             --tw-prose-invert-code: #fff;
             --tw-prose-invert-pre-code: oklch(87.2% .01 258.338);
             --tw-prose-invert-pre-bg: #00000080;
             --tw-prose-invert-th-borders: oklch(44.6% .03 256.802);
             --tw-prose-invert-td-borders: oklch(37.3% .034 259.733);
             font-size: 1rem;
             line-height: 1.75
         }

             .prose :where(picture>img):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-bottom: 0;
                 margin-top: 0
             }

             .prose :where(li):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-bottom: .5em;
                 margin-top: .5em
             }

             .prose :where(ol>li):not(:where([class~=not-prose],[class~=not-prose] *)), .prose :where(ul>li):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 padding-inline-start: .375em
             }

             .prose :where(.prose>ul>li p):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-bottom: .75em;
                 margin-top: .75em
             }

             .prose :where(.prose>ul>li>p:first-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-top: 1.25em
             }

             .prose :where(.prose>ul>li>p:last-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-bottom: 1.25em
             }

             .prose :where(.prose>ol>li>p:first-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-top: 1.25em
             }

             .prose :where(.prose>ol>li>p:last-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-bottom: 1.25em
             }

             .prose :where(ul ul,ul ol,ol ul,ol ol):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-bottom: .75em;
                 margin-top: .75em
             }

             .prose :where(dl):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-bottom: 1.25em;
                 margin-top: 1.25em
             }

             .prose :where(dd):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-top: .5em;
                 padding-inline-start: 1.625em
             }

             .prose :where(h2+*):not(:where([class~=not-prose],[class~=not-prose] *)), .prose :where(h3+*):not(:where([class~=not-prose],[class~=not-prose] *)), .prose :where(h4+*):not(:where([class~=not-prose],[class~=not-prose] *)), .prose :where(hr+*):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-top: 0
             }

             .prose :where(thead th:first-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 padding-inline-start: 0
             }

             .prose :where(thead th:last-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 padding-inline-end: 0
             }

             .prose :where(tbody td,tfoot td):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 padding-inline-end: .571429em;
                 padding-bottom: .571429em;
                 padding-top: .571429em;
                 padding-inline-start: .571429em
             }

             .prose :where(tbody td:first-child,tfoot td:first-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 padding-inline-start: 0
             }

             .prose :where(tbody td:last-child,tfoot td:last-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 padding-inline-end: 0
             }

             .prose :where(figure):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-bottom: 2em;
                 margin-top: 2em
             }

             .prose :where(.prose>:first-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-top: 0
             }

             .prose :where(.prose>:last-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                 margin-bottom: 0
             }

         .mt-4 {
             margin-top: calc(var(--spacing)*4)
         }

         .mt-8 {
             margin-top: calc(var(--spacing)*8)
         }

         .mt-auto {
             margin-top: auto
         }

         .mr-auto {
             margin-right: auto
         }

         .mb-4 {
             margin-bottom: calc(var(--spacing)*4)
         }

         .mb-5 {
             margin-bottom: calc(var(--spacing)*5)
         }

         .mb-8 {
             margin-bottom: calc(var(--spacing)*8)
         }

         .mb-auto {
             margin-bottom: auto
         }

         .ml-8 {
             margin-left: calc(var(--spacing)*8)
         }

         .ml-auto {
             margin-left: auto
         }

         .block {
             display: block
         }

         .flex {
             display: flex
         }

         .grid {
             display: grid
         }

         .hidden {
             display: none
         }

         .aspect-square {
             aspect-ratio: 1
         }

         .size-6 {
             height: calc(var(--spacing)*6);
             width: calc(var(--spacing)*6)
         }

         .size-12 {
             height: calc(var(--spacing)*12);
             width: calc(var(--spacing)*12)
         }

         .size-full {
             height: 100%;
             width: 100%
         }

         .h-5 {
             height: calc(var(--spacing)*5)
         }

         .h-full {
             height: 100%
         }

         .min-h-screen {
             min-height: 100vh
         }

         .w-9\/12 {
             width: 75%
         }

         .w-fit {
             width: -moz-fit-content;
             width: fit-content
         }

         .w-full {
             width: 100%
         }

         .max-w-xs {
             max-width: var(--container-xs)
         }

         .min-w-\[11\.25rem\] {
             min-width: 11.25rem
         }

         .list-disc {
             list-style-type: disc
         }

         .grid-cols-1 {
             grid-template-columns: repeat(1,minmax(0,1fr))
         }

         .flex-col {
             flex-direction: column
         }

         .items-center {
             align-items: center
         }

         .gap-1 {
             gap: calc(var(--spacing)*1)
         }

         .gap-2 {
             gap: calc(var(--spacing)*2)
         }

         .gap-4 {
             gap: calc(var(--spacing)*4)
         }

         .gap-8 {
             gap: calc(var(--spacing)*8)
         }

         .gap-12 {
             gap: calc(var(--spacing)*12)
         }

         .rounded-lg {
             border-radius: var(--radius-lg)
         }

         .rounded-sm {
             border-radius: var(--radius-sm)
         }

         .border {
             border-style: var(--tw-border-style);
             border-width: 1px
         }

         .border-\[\#ffffff2e\] {
             border-color: #ffffff2e
         }

         .border-black-secondary {
             border-color: var(--color-black-secondary)
         }

         .bg-\[color\:var\(--highlight\)\] {
             background-color: var(--highlight)
         }

         .bg-black-primary {
             background-color: var(--color-black-primary)
         }

         .bg-white-secondary {
             background-color: var(--color-white-secondary)
         }

         .p-1 {
             padding: calc(var(--spacing)*1)
         }

         .p-2 {
             padding: calc(var(--spacing)*2)
         }

         .p-4 {
             padding: calc(var(--spacing)*4)
         }

         .p-8 {
             padding: calc(var(--spacing)*8)
         }

         .px-2 {
             padding-inline: calc(var(--spacing)*2)
         }

         .px-8 {
             padding-inline: calc(var(--spacing)*8)
         }

         .py-1 {
             padding-block: calc(var(--spacing)*1)
         }

         .py-4 {
             padding-block: calc(var(--spacing)*4)
         }

         .pt-8 {
             padding-top: calc(var(--spacing)*8)
         }

         .pb-8 {
             padding-bottom: calc(var(--spacing)*8)
         }

         .text-center {
             text-align: center
         }

         .text-right {
             text-align: right
         }

         .text-3xl {
             font-size: var(--text-3xl);
             line-height: var(--tw-leading,var(--text-3xl--line-height))
         }

         .text-4xl {
             font-size: var(--text-4xl);
             line-height: var(--tw-leading,var(--text-4xl--line-height))
         }

         .text-5xl {
             font-size: var(--text-5xl);
             line-height: var(--tw-leading,var(--text-5xl--line-height))
         }

         .text-base\! {
             font-size: var(--text-base) !important;
             line-height: var(--tw-leading,var(--text-base--line-height)) !important
         }

         .text-lg {
             font-size: var(--text-lg);
             line-height: var(--tw-leading,var(--text-lg--line-height))
         }

         .text-sm {
             font-size: var(--text-sm);
             line-height: var(--tw-leading,var(--text-sm--line-height))
         }

         .text-xl {
             font-size: var(--text-xl);
             line-height: var(--tw-leading,var(--text-xl--line-height))
         }

         .font-bold {
             --tw-font-weight: var(--font-weight-bold);
             font-weight: var(--font-weight-bold)
         }

         .font-medium {
             --tw-font-weight: var(--font-weight-medium);
             font-weight: var(--font-weight-medium)
         }

         .font-semibold {
             --tw-font-weight: var(--font-weight-semibold);
             font-weight: var(--font-weight-semibold)
         }

         .whitespace-pre {
             white-space: pre
         }

         .text-\[color\:var\(--highlight\)\] {
             color: var(--highlight)
         }

         .text-black-primary {
             color: var(--color-black-primary)
         }

         .text-black-secondary {
             color: var(--color-black-secondary)
         }

         .text-white-primary {
             color: var(--color-white-primary)
         }

         .capitalize {
             text-transform: capitalize
         }

         .lowercase {
             text-transform: lowercase
         }

         .underline {
             text-decoration-line: underline
         }

         .brightness-50 {
             --tw-brightness: brightness(50%)
         }

         .brightness-50, .filter {
             filter: var(--tw-blur,)var(--tw-brightness,)var(--tw-contrast,)var(--tw-grayscale,)var(--tw-hue-rotate,)var(--tw-invert,)var(--tw-saturate,)var(--tw-sepia,)var(--tw-drop-shadow,)
         }

         .transition {
             transition-duration: var(--tw-duration,var(--default-transition-duration));
             transition-property: color,background-color,border-color,outline-color,text-decoration-color,fill,stroke,--tw-gradient-from,--tw-gradient-via,--tw-gradient-to,opacity,box-shadow,transform,translate,scale,rotate,filter,-webkit-backdrop-filter,backdrop-filter,display,visibility,content-visibility,overlay,pointer-events;
             transition-timing-function: var(--tw-ease,var(--default-transition-timing-function))
         }

         .transition-all {
             transition-duration: var(--tw-duration,var(--default-transition-duration));
             transition-property: all;
             transition-timing-function: var(--tw-ease,var(--default-transition-timing-function))
         }

         .duration-200 {
             --tw-duration: .2s;
             transition-duration: .2s
         }

         .duration-300 {
             --tw-duration: .3s;
             transition-duration: .3s
         }

         .duration-1000 {
             --tw-duration: 1s;
             transition-duration: 1s
         }

         @media (hover:hover) {
             .hover\:text-\[color\:var\(--highlight\)\]:hover {
                 color: var(--highlight)
             }
         }

         @media (min-width:40rem) {
             .sm\:grid-cols-2 {
                 grid-template-columns: repeat(2,minmax(0,1fr))
             }
         }

         @media (min-width:48rem) {
             .md\:hidden {
                 display: none
             }

             .md\:table-cell {
                 display: table-cell
             }

             .md\:pr-4 {
                 padding-right: calc(var(--spacing)*4)
             }
         }

         @media (min-width:64rem) {
             .lg\:order-1 {
                 order: 1
             }

             .lg\:prose-xl {
                 font-size: 1.25rem;
                 line-height: 1.8
             }

                 .lg\:prose-xl :where(p):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: 1.2em;
                     margin-top: 1.2em
                 }

                 .lg\:prose-xl :where([class~=lead]):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     font-size: 1.2em;
                     line-height: 1.5;
                     margin-bottom: 1em;
                     margin-top: 1em
                 }

                 .lg\:prose-xl :where(blockquote):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: 1.6em;
                     margin-top: 1.6em;
                     padding-inline-start: 1.06667em
                 }

                 .lg\:prose-xl :where(h1):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     font-size: 2.8em;
                     line-height: 1;
                     margin-bottom: .857143em;
                     margin-top: 0
                 }

                 .lg\:prose-xl :where(h2):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     font-size: 1.8em;
                     line-height: 1.11111;
                     margin-bottom: .888889em;
                     margin-top: 1.55556em
                 }

                 .lg\:prose-xl :where(h3):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     font-size: 1.5em;
                     line-height: 1.33333;
                     margin-bottom: .666667em;
                     margin-top: 1.6em
                 }

                 .lg\:prose-xl :where(h4):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     line-height: 1.6;
                     margin-bottom: .6em;
                     margin-top: 1.8em
                 }

                 .lg\:prose-xl :where(img):not(:where([class~=not-prose],[class~=not-prose] *)), .lg\:prose-xl :where(picture):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: 2em;
                     margin-top: 2em
                 }

                 .lg\:prose-xl :where(picture>img):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: 0;
                     margin-top: 0
                 }

                 .lg\:prose-xl :where(video):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: 2em;
                     margin-top: 2em
                 }

                 .lg\:prose-xl :where(kbd):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     border-radius: .3125rem;
                     font-size: .9em;
                     padding-inline-end: .4em;
                     padding-bottom: .25em;
                     padding-top: .25em;
                     padding-inline-start: .4em
                 }

                 .lg\:prose-xl :where(code):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     font-size: .9em
                 }

                 .lg\:prose-xl :where(h2 code):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     font-size: .861111em
                 }

                 .lg\:prose-xl :where(h3 code):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     font-size: .9em
                 }

                 .lg\:prose-xl :where(pre):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     border-radius: .5rem;
                     font-size: .9em;
                     line-height: 1.77778;
                     margin-bottom: 2em;
                     margin-top: 2em;
                     padding-inline-end: 1.33333em;
                     padding-bottom: 1.11111em;
                     padding-top: 1.11111em;
                     padding-inline-start: 1.33333em
                 }

                 .lg\:prose-xl :where(ol):not(:where([class~=not-prose],[class~=not-prose] *)), .lg\:prose-xl :where(ul):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: 1.2em;
                     margin-top: 1.2em;
                     padding-inline-start: 1.6em
                 }

                 .lg\:prose-xl :where(li):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: .6em;
                     margin-top: .6em
                 }

                 .lg\:prose-xl :where(ol>li):not(:where([class~=not-prose],[class~=not-prose] *)), .lg\:prose-xl :where(ul>li):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     padding-inline-start: .4em
                 }

                 .lg\:prose-xl :where(.lg\:prose-xl>ul>li p):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: .8em;
                     margin-top: .8em
                 }

                 .lg\:prose-xl :where(.lg\:prose-xl>ul>li>p:first-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-top: 1.2em
                 }

                 .lg\:prose-xl :where(.lg\:prose-xl>ul>li>p:last-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: 1.2em
                 }

                 .lg\:prose-xl :where(.lg\:prose-xl>ol>li>p:first-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-top: 1.2em
                 }

                 .lg\:prose-xl :where(.lg\:prose-xl>ol>li>p:last-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: 1.2em
                 }

                 .lg\:prose-xl :where(ul ul,ul ol,ol ul,ol ol):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: .8em;
                     margin-top: .8em
                 }

                 .lg\:prose-xl :where(dl):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: 1.2em;
                     margin-top: 1.2em
                 }

                 .lg\:prose-xl :where(dt):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-top: 1.2em
                 }

                 .lg\:prose-xl :where(dd):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-top: .6em;
                     padding-inline-start: 1.6em
                 }

                 .lg\:prose-xl :where(hr):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: 2.8em;
                     margin-top: 2.8em
                 }

                 .lg\:prose-xl :where(h2+*):not(:where([class~=not-prose],[class~=not-prose] *)), .lg\:prose-xl :where(h3+*):not(:where([class~=not-prose],[class~=not-prose] *)), .lg\:prose-xl :where(h4+*):not(:where([class~=not-prose],[class~=not-prose] *)), .lg\:prose-xl :where(hr+*):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-top: 0
                 }

                 .lg\:prose-xl :where(table):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     font-size: .9em;
                     line-height: 1.55556
                 }

                 .lg\:prose-xl :where(thead th):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     padding-inline-end: .666667em;
                     padding-bottom: .888889em;
                     padding-inline-start: .666667em
                 }

                 .lg\:prose-xl :where(thead th:first-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     padding-inline-start: 0
                 }

                 .lg\:prose-xl :where(thead th:last-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     padding-inline-end: 0
                 }

                 .lg\:prose-xl :where(tbody td,tfoot td):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     padding-inline-end: .666667em;
                     padding-bottom: .888889em;
                     padding-top: .888889em;
                     padding-inline-start: .666667em
                 }

                 .lg\:prose-xl :where(tbody td:first-child,tfoot td:first-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     padding-inline-start: 0
                 }

                 .lg\:prose-xl :where(tbody td:last-child,tfoot td:last-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     padding-inline-end: 0
                 }

                 .lg\:prose-xl :where(figure):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: 2em;
                     margin-top: 2em
                 }

                 .lg\:prose-xl :where(figure>*):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: 0;
                     margin-top: 0
                 }

                 .lg\:prose-xl :where(figcaption):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     font-size: .9em;
                     line-height: 1.55556;
                     margin-top: 1em
                 }

                 .lg\:prose-xl :where(.lg\:prose-xl>:first-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-top: 0
                 }

                 .lg\:prose-xl :where(.lg\:prose-xl>:last-child):not(:where([class~=not-prose],[class~=not-prose] *)) {
                     margin-bottom: 0
                 }

             .lg\:mr-0 {
                 margin-right: calc(var(--spacing)*0)
             }

             .lg\:w-fit {
                 width: -moz-fit-content;
                 width: fit-content
             }

             .lg\:grid-cols-2 {
                 grid-template-columns: repeat(2,minmax(0,1fr))
             }

             .lg\:grid-cols-3 {
                 grid-template-columns: repeat(3,minmax(0,1fr))
             }

             .lg\:text-right {
                 text-align: right
             }

             .lg\:text-5xl {
                 font-size: var(--text-5xl);
                 line-height: var(--tw-leading,var(--text-5xl--line-height))
             }

             .lg\:text-6xl {
                 font-size: var(--text-6xl);
                 line-height: var(--tw-leading,var(--text-6xl--line-height))
             }
         }

         @media (min-width:80rem) {
             .xl\:max-w-full {
                 max-width: 100%
             }

             .xl\:min-w-fit {
                 min-width: -moz-fit-content;
                 min-width: fit-content
             }

             .xl\:grid-cols-3 {
                 grid-template-columns: repeat(3,minmax(0,1fr))
             }
         }

         @media (min-width:96rem) {
             .\32xl\:grid-cols-4 {
                 grid-template-columns: repeat(4,minmax(0,1fr))
             }
         }

         @media (prefers-color-scheme:dark) {
             .dark\:border {
                 border-style: var(--tw-border-style);
                 border-width: 1px
             }

             .dark\:border-\[\#444\] {
                 border-color: #444
             }

             .dark\:border-white-secondary {
                 border-color: var(--color-white-secondary)
             }

             .dark\:bg-black-secondary {
                 background-color: var(--color-black-secondary)
             }

             .dark\:bg-white-primary {
                 background-color: var(--color-white-primary)
             }

             .dark\:text-black-primary {
                 color: var(--color-black-primary)
             }

             .dark\:text-white-primary {
                 color: var(--color-white-primary)
             }

             .dark\:text-white-secondary {
                 color: var(--color-white-secondary)
             }

             .dark\:prose-invert {
                 --tw-prose-body: var(--tw-prose-invert-body);
                 --tw-prose-headings: var(--tw-prose-invert-headings);
                 --tw-prose-lead: var(--tw-prose-invert-lead);
                 --tw-prose-links: var(--tw-prose-invert-links);
                 --tw-prose-bold: var(--tw-prose-invert-bold);
                 --tw-prose-counters: var(--tw-prose-invert-counters);
                 --tw-prose-bullets: var(--tw-prose-invert-bullets);
                 --tw-prose-hr: var(--tw-prose-invert-hr);
                 --tw-prose-quotes: var(--tw-prose-invert-quotes);
                 --tw-prose-quote-borders: var(--tw-prose-invert-quote-borders);
                 --tw-prose-captions: var(--tw-prose-invert-captions);
                 --tw-prose-kbd: var(--tw-prose-invert-kbd);
                 --tw-prose-kbd-shadows: var(--tw-prose-invert-kbd-shadows);
                 --tw-prose-code: var(--tw-prose-invert-code);
                 --tw-prose-pre-code: var(--tw-prose-invert-pre-code);
                 --tw-prose-pre-bg: var(--tw-prose-invert-pre-bg);
                 --tw-prose-th-borders: var(--tw-prose-invert-th-borders);
                 --tw-prose-td-borders: var(--tw-prose-invert-td-borders)
             }
         }
     }

     :root {
         --highlight: red
     }

     body {
         background-color: var(--color-white-primary)
     }

     @media (prefers-color-scheme:dark) {
         body {
             background-color: var(--color-black-primary)
         }
     }

     body {
         color: var(--color-black-primary)
     }

     @media (prefers-color-scheme:dark) {
         body {
             color: var(--color-white-primary)
         }
     }

     @property --tw-border-style {
         syntax: "*";
         inherits: false;
         initial-value: solid
     }

     @property --tw-font-weight {
         syntax: "*";
         inherits: false
     }

     @property --tw-blur {
         syntax: "*";
         inherits: false
     }

     @property --tw-brightness {
         syntax: "*";
         inherits: false
     }

     @property --tw-contrast {
         syntax: "*";
         inherits: false
     }

     @property --tw-grayscale {
         syntax: "*";
         inherits: false
     }

     @property --tw-hue-rotate {
         syntax: "*";
         inherits: false
     }

     @property --tw-invert {
         syntax: "*";
         inherits: false
     }

     @property --tw-opacity {
         syntax: "*";
         inherits: false
     }

     @property --tw-saturate {
         syntax: "*";
         inherits: false
     }

     @property --tw-sepia {
         syntax: "*";
         inherits: false
     }

     @property --tw-drop-shadow {
         syntax: "*";
         inherits: false
     }

     @property --tw-drop-shadow-color {
         syntax: "*";
         inherits: false
     }

     @property --tw-drop-shadow-alpha {
         syntax: "<percentage>";
         inherits: false;
         initial-value: 100%
     }

     @property --tw-drop-shadow-size {
         syntax: "*";
         inherits: false
     }

     @property --tw-duration {
         syntax: "*";
         inherits: false
     }
 </style>
  <link rel="preload" as="fetch" crossorigin="anonymous" href="/_payload.json?8e0407ae-a1bb-48d8-9746-a8bc613c47de">
 <link rel="modulepreload" as="script" crossorigin href="/_nuxt/PY4qTGxL.js">
 <link rel="modulepreload" as="script" crossorigin href="/_nuxt/BNrcFqLl.js">
 <link rel="modulepreload" as="script" crossorigin href="/_nuxt/FoiUSYcx.js">
 <link rel="modulepreload" as="script" crossorigin href="/_nuxt/lgRIcNzB.js">
 <link rel="modulepreload" as="script" crossorigin href="/_nuxt/DhOdXL36.js">
 <link rel="modulepreload" as="script" crossorigin href="/_nuxt/DcW6P7H9.js">
 <link rel="modulepreload" as="script" crossorigin href="/_nuxt/DZVq1o3J.js">
 <link rel="modulepreload" as="script" crossorigin href="/_nuxt/IOYS-v5J.js">
 <link rel="preload" as="fetch" fetchpriority="low" crossorigin="anonymous" href="/_nuxt/builds/meta/8e0407ae-a1bb-48d8-9746-a8bc613c47de.json">
 <link href="/apple-touch-icon.png" rel="apple-touch-icon" sizes="180x180">
 <link href="/favicon-32x32.png" rel="icon" sizes="32x32" type="image/png">
 <link href="/favicon-16x16.png" rel="icon" sizes="16x16" type="image/png">
 <link href="/site.webmanifest" rel="manifest">
 <link color="#5bbad5" href="/safari-pinned-tab.svg" rel="mask-icon">
 <meta content="#da532c" name="msapplication-TileColor">
 <meta content="#ffffff" name="theme-color">
 <meta property="og:image" content="http://localhost:3013//public/RaylenHomepic.png">
 <meta property="og:image:type" content="image/png">
 <meta property="og:image:width" content="1200">
 <meta property="og:image:height" content="630">
 <meta name="twitter:image" content="http://localhost:3013//public/RaylenHomepic.png">
 <meta name="twitter:image:type" content="image/png">
 <meta name="twitter:image:width" content="1200">
 <meta name="twitter:image:height" content="630">
 <meta property="og:type" content="website">
 <meta name="robots" content="index, follow, max-image-preview:large, max-snippet:-1, max-video-preview:-1">
 <meta name="author" content="Raylen Williams">
 <meta name="description" content="Software developer from Denmark. Lover of all things programming - but  always learning new stuff.">
 <meta property="og:description" content="Software developer from Denmark. Lover of all things programming - but  always learning new stuff.">
 <meta property="og:site_name" content="Raylen Wiliiams">
 <meta property="og:title" content="Raylen Williams | Software Developer">
 <meta name="twitter:card" content="summary_large_image">
 <meta name="twitter:creator" content="mads_hougesen">
 <meta name="twitter:site" content="@mads_hougesen">
 <script type="module" src="/_nuxt/PY4qTGxL.js" crossorigin></script>
 <link rel="canonical" href="https://mhouge.dk/">
 <meta property="og:url" content="https://mhouge.dk/">
