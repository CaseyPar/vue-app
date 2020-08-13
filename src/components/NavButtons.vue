<template>
      <div id="nav">
    <div class="navContainer">
      <router-link to="/">
      <img class="icon" alt="home icon" src="../assets/door.png"/>
      </router-link> |
    </div>

    <div class="navContainer">
      <router-link to="/about">
      <img class="icon" alt="info icon" src="../assets/info.png"/>
      </router-link>
    </div>

    <div class="navContainer">
      <router-link to="/feature1">
      <img class="icon" alt="info icon" src="../assets/clock.png"/>
      </router-link>
    </div>

    <div class="navContainer">
      <router-link to="/feature2">
      <img class="icon" alt="info icon" src="../assets/ice-cream.png"/>
      </router-link>
    </div>
</div>
</template>

<script>
export default {
    name: 'NavButtons',
    data() {
        return {

        }
    },
    methods: {
        
    }
}
</script>

<style scoped> 

    #nav {
        position: fixed;
        bottom: 0;
        width: 100%;
        display: flex;
        justify-content: space-between;
        border: solid 2px yellow;
        padding: 0px;
    }

    .navContainer {
        background-color: pink;
    }

    .icon {
        width: 80px;
        height: 80px;
        margin: 5px;
    }
</style>