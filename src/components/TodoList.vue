<template>
  <div>
    <ul>
      <!-- {{todos}} -->
      <TodoItem
        v-for="todo in todos"
        v-bind:todo="todo"
      />
    </ul>
  </div>
</template>

<script>
import TodoItem from "@/components/TodoItem";
export default {
  props: ["todos"],
  components: {
    TodoItem
  }
};
</script>

<style scoped>
  ul {
    list-style: none;
    margin: 0;
    padding: 0;
  }
</style>
