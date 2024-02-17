<script lang="ts" setup>
import ListItem from './ListItem.vue'
</script>

<template>
    <ul>
        <ListItem :is-checked="false">This is the slotted content</ListItem>
    </ul>
</template>