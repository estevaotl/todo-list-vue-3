<template>
    <div class="space-y-2">
        <TodoItem />
    </div>
</template>

<script>
import TodoItem from './TodoItem.vue';

export default {
    name: 'TodoItens',
    components: {
        TodoItem
    }
}
</script>