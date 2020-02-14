<template>
  <div>
    <ul>
      {{todos}}
      <li>todo 1</li>
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
