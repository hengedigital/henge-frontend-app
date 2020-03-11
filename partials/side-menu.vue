<template>

  <div class="side-menu">
    <!-- Side menu to the spec of the project settings (can set boilerplates within the project setup/onboarding - pages / general elements -->

    <!--

      Pages
        -> Blog
          -> Content
          -> Posts

        -> Homepage
          -> Content
          -> Posts

        -> Contact Page
          -> Content (general elements can also be referenced - new element or reference element with auto suggest)
          -> Inquiries

     -->

    <ul>
      <li>Pages</li>
      <li>
        Homepage
        <ul>
          <li>
            Content
          </li>
          <li>
            Carousel
          </li>
        </ul>
      </li>
      <li>
        Contact
        <ul>
          <li>
            Content
          </li>
          <li>
            View Inquiries
          </li>
        </ul>
      </li>
      <li>
        Blog
        <ul>
          <li>
            (sub item) Content
          </li>
          <li>
            (sub item) Posts
          </li>
        </ul>
      </li>
    </ul>

  </div>

</template>

<script>

export default {

  name: 'Header'

}

</script>

<style scoped>
  .header {

  }
</style>
