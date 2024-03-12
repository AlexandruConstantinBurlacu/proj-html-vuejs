<script>
    export default {
        name: 'AppMain',
    }
</script>

<template>
  <div class="moreAbout">
    <h1>More About Damon Vaughn</h1>
    <p>
      Damon Vaughn is a professor of psychology at the University of Toronto,
      a clinical psychologist and the author of the multi-million copy
      best seller "The story of my life".
    </p>
    <button type="button">
      Meet The Author
    </button>
  </div>
</template>

<style lang="scss">

  .moreAbout * {
      color: black;
  }

  .moreAbout {
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: white;
    margin: 84px 206px;

    h1 {
      color: #f4b429;
      font-size: 38px;
    }

    p {
      text-align: center;
      margin-top: 35px;
      margin-bottom: 39px;
    }

    button {
      color: white;
      background-color: #49a987;
      padding: 11px 19px;
      border: 0px;
      border-radius: 6px;
      cursor: pointer;
    }
  }

  

</style>