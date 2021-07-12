<template>
  <div class="container mx-auto">
    <div class="h-64 grid grid-rows-none grid-flow-col gap-4">
      <table class="table-auto border">
        <thead class="border">
          <th>name</th>
          <th>age</th>
        </thead>
        <tbody>
          <tr class="border" v-for="item in friends" :key="item.id">
            <Profile :name="item.name" :age="item.age" />
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script>
import Profile from "./components/Profile.vue";

export default {
  name: "App",
  components: {
    Profile,
  },
  data() {
    return {
      friends: [
        { id: 1, name: "Kong", age: 21 },
        { id: 2, name: "Oat", age: 20 },
        { id: 3, name: "Pun", age: 22 },
        { id: 4, name: "Fax", age: 21 },
        { id: 5, name: "DJ", age: 20 },
        { id: 6, name: "Teem", age: 20 },
        { id: 7, name: "Tar", age: 20 },
        { id: 8, name: "Tle", age: 21 },
        { id: 9, name: "Pluk", age: 20 },
        { id: 10, name: "Michael", age: 20 },
      ],
    };
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
