<template>
  <button class="button">
    <slot/>
  </button>
</template>

<script>
  export default { 
    props: {
      lbl: String
  },
  }
</script>

<style scoped>
  .button {
    display: inline-block;
    margin: 0.25em 0.25em;
    padding: .5em .5emm;
    background: #bdb76b;
    border: 2px solid black;
    border-radius: 3px;
    color: black;
    font-family: "Quicksand", sans-serif;
    font-size: 0.75em;
    font-weight: 400;
    letter-spacing: 0.02em;
    line-height: 1;
    text-decoration: none;
    text-transform: uppercase;
    cursor: pointer;
    transition: 0.1s;
  }

  .button:hover {
    background: BlanchedAlmond ;  
    color: sienna;
  }
</style>