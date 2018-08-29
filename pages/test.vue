<template>
  <b-container>
    <section>
      <h1>Test form</h1>
      <a href="#">asasdads</a>
      <form>
        <div class="form-group">
          <label for="exampleFormControlInput1">Email address</label>
          <input 
            id="exampleFormControlInput1" 
            type="email" 
            class="form-control" 
            placeholder="name@example.com">
        </div>
        <div class="form-group">
          <label for="exampleFormControlSelect1">Example select</label>
          <select 
            id="exampleFormControlSelect1" 
            class="form-control" 
            required >
            <option>1</option>
            <option>2</option>
            <option>3</option>
            <option>4</option>
            <option>5</option>
          </select>
        </div>
        <div class="form-group">
          <label for="exampleFormControlSelect2">Example multiple select</label>
          <select 
            id="exampleFormControlSelect2" 
            multiple 
            class="form-control">
            <option>1</option>
            <option>2</option>
            <option>3</option>
            <option>4</option>
            <option>5</option>
          </select>
        </div>
        <div class="form-group">
          <label for="exampleFormControlTextarea1">Example textarea</label>
          <textarea 
            id="exampleFormControlTextarea1" 
            class="form-control" 
            rows="3"/>
        </div>
        <button 
          type="submit" 
          class="btn btn-primary">Submit</button>
      </form>
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
  </b-container>
</template>

<script>
</script>

<style lang="scss" scoped>
  h1 {
    margin-top: 1em;
  }
</style>

