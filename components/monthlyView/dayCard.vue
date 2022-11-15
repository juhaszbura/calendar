<template>
    <div class="bg-white relative flex flex-col group">
        <span class="mx-2 mt-1 mb-3 text-xs font-bold">{{ day.name }}</span>
        <div class="flex flex-col px-1 py-1 overflow-auto">
            <ItemOfDay v-for="(item, index) in day.items" :key="index"/>
        </div>
    </div>
</template>

<script>
import ItemOfDay from "~/components/monthlyView/itemOfDay.vue";

export default {
    name: "dayCard",
    components: {ItemOfDay},
    props: {
        day: {
            type: Object,
            require:true,
        },
    },
}
</script>

<style scoped>

</style>