<template>
  <div class="home">
    <img class="profilePic" alt="Vue logo" src="../assets/sree_photo.jpg" />
    <!--<HelloWorld msg="Welcome to Your Vue.js App" />-->
    <p>
      I'm a developer working on some passion projects.<br />This is my first
      Portfolio website. And thats's it :). Cya, when I make a more elaborate
      protfolio website.
    </p>
    <ul>
      <li>
        <a href="https://github.com/SreeChandan" target="_blank">
          <img alt="Github" src="../assets/github-logo.svg" />
        </a>
      </li>
      <li>
        <a href="https://twitter.com/sreechandan98" target="_blank">
          <img
            alt="Github"
            src="../assets/Twitter_Social_Icon_Circle_Color.svg"
          />
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    //HelloWorld
  }
};
</script>

<style lang="scss" scoped>
/*@media only screen and (min-width: ;{
  
}*/
div.home {
  width: 350px;
  margin: 0px auto;
  margin-top: 25px;
}

img.profilePic {
  border-radius: 24%;
  width: 200px;
  box-shadow: #f35d12 0px 1px 0px 4px; /** color should be theme-able */
}

p {
  font-family: "Times New Roman", Times, serif;
  font-size: 25px;
  text-align: left;
}

ul {
  list-style-type: none;
  height: 100px;
}

li { 
  display: inline-block;
  margin: 10px 5px;
}

li a {
  display: block;
}

/*img.contactIcons */
</style>
