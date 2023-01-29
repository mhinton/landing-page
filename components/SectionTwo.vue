<script lang="ts" setup></script>

<template>
  <section class="">
    <p>
      Hello, my name is Matthew Hinton and this is my identity landing page.
      Most people use social media sites for this but I believe everyone should
      own their own identity on the Internet.
    </p>
    <p>
      This page contains links to my other accounts on the web and information
      on how to contact me.
    </p>
    <section
      class="flex flex-row flex-nowrap justify-around items-center content-center"
    >
      <div><Icon name="logos:mastodon-icon" size="32" color="#2791DA" /></div>
      <div><Icon name="fa6-brands:facebook" size="32" color="#0D8AF0" /></div>
      <div>
        <a href="https://www.linkedin.com/in/mohinton/">
          <Icon name="fa6-brands:linkedin" size="32" color="#0A66C2" />
        </a>
      </div>
    </section>
  </section>
</template>

<script lang="ts">
export default {
  name: "Fa6BrandsLinkedin",
};
</script>

<style lang="postcss" scoped></style>
