<template>
    <div class="relative flex flex-col bg-white group">
        <span class="mx-2 my-1 text-xs font-bold">1 September</span>
        <div class=" overflow-hidden flex flex-col px-1 py-1 overflow-auto">
            <ItemOfDay />
            <ItemOfDay />
            <ItemOfDay />
            <ItemOfDay />
            <ItemOfDay />
        </div>
    </div>
</template>

<script>
import ItemOfDay from "~/components/monthlyView/itemOfDay.vue";

export default {
    name: "dayCard",
    components: {ItemOfDay}
}
</script>

<style scoped>

</style>