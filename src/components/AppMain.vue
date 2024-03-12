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

  <div class="avaliable">
    <ul>
      <li>ebay</li>
      <li>audible</li>
      <li>barnes</li>
      <li>kindle</li>
    </ul>
  </div>

  <div class="newAudiobook">
    <img src="../assets/images/audible-app-2x-400x418.png" alt="Audible">
    <div class="new">
      <h2>
        New AudioBook
      </h2>
      <h4>
        no time to read? no problem. listen to it
      </h4>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
      </p>
      <ul>
        <li>audible</li>
        <li>barnes</li>
        <li>kindle</li>
      </ul>
    </div>
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

  .avaliable {
    background-color: #fef7e9;

    ul {
      display: flex;
      flex-direction: row;
      justify-content: center;
      gap: 74px;
      list-style-type: none;
      padding-top: 63px;
      padding-bottom: 50px;

      li {
        font-size: 20px;
      }
    }
  }

  .newAudiobook * {
    color: white;
  }

  .newAudiobook {
    max-height: 404px;
    background-image: url("../assets/images/banner.jpg");
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    gap: 71px;

    img {
      margin-top: 48px;
      width: 304px;
      height: auto;
    }

    .new {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      margin-top: 136px;
      margin-bottom: 109px;

      h4 {
        color: #f4b429;
        text-transform: uppercase;
        margin-top: 21px;
        margin-bottom: 28px;
      }

      p {
        color: #c6c4c4;
        margin-bottom: 40px;
      }

      ul {
        display: flex;
        flex-direction: row;
        gap: 32px;
        list-style-type: none;
        
      }
    }
  }

  

</style>