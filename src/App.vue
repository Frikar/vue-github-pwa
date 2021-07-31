<template>
  <div>
    <h1>Github App</h1>
    <GithubToken></GithubToken>
    <User></User>
    <Repos></Repos>
  </div>
</template>

<script>
import GithubToken from "./components/GithubToken";
import User from "@/components/User";
import Repos from "@/components/Repos";

export default {
  name: "App",
  components: {
    Repos,
    User,
    GithubToken
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
