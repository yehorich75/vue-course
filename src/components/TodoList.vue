<template>
    <div>
        <ul>
            <li>todo 1</li>
            <TodoItem />
        </ul>
    </div>
</template>

<script>
import TodoItem from '@/components/TodoItem'
export default {
  components: {
    TodoItem
  }
}
</script>