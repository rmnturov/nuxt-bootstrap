<template>
  <section>
    <div>
      <b-button>I am a Button</b-button>
      <b-button href="#">I am a Link</b-button>
    </div>
    <b-dropdown 
      id="ddown1" 
      text="Dropdown Button" 
      class="m-md-2">
      <b-dropdown-item>First Action</b-dropdown-item>
      <b-dropdown-item>Second Action</b-dropdown-item>
      <b-dropdown-item>Third Action</b-dropdown-item>
      <b-dropdown-divider/>
      <b-dropdown-item>Something else here...</b-dropdown-item>
      <b-dropdown-item disabled>Disabled action</b-dropdown-item>
    </b-dropdown>
  </section>
</template>

<script>

</script>