<template>
    <div class="text-gray-700">
        <!-- Component Start -->
        <div class="flex flex-grow w-full h-screen overflow-auto">
            <div class="flex flex-col flex-grow">
                <!-- Name of week days -->
                <div class="grid grid-cols-7 mt-4">
                    <div class="pl-1 text-sm text-center">hétfő</div>
                    <div class="pl-1 text-sm text-center">kedd</div>
                    <div class="pl-1 text-sm text-center">szerda</div>
                    <div class="pl-1 text-sm text-center">csütrötök</div>
                    <div class="pl-1 text-sm text-center">péntek</div>
                    <div class="pl-1 text-sm text-center">szombat</div>
                    <div class="pl-1 text-sm text-center">vasárnap</div>
                </div>
                <!-- Grid -->
                <div class="grid flex-grow w-full h-auto grid-cols-7 grid-rows-5 gap-px pt-px mt-1 bg-gray-100">
                    <DayCard v-for="day in days" :key="day.name" :day="day"/>
                </div>
            </div>
        </div>
        <!-- Component End  -->
    </div>
</template>

<script>
import DayCard from "~/components/monthlyView/dayCard.vue";

export default {
    name: "monthlyView",
    components: {DayCard},
    setup(){
        const days = [
            {
                'name': 'November 1',
                'items': [
                    {},
                    {},
                    {},
                ]
            },
            {
                'name': '2',
                'items': [
                ]
            },
            {
                'name': '3',
                'items': [
                    {},
                ]
            },
            {
                'name': '4',
                'items': [
                    {},
                ]
            },
            {
                'name': '5',
                'items': [
                ]
            },
            {
                'name': '6',
                'items': [

                ]
            },
            {
                'name': '7',
                'items': [
                    {},
                    {},
                    {},
                ]
            },
            {
                'name': 'November 1',
                'items': [
                    {},
                    {},
                    {},
                ]
            },
            {
                'name': '2',
                'items': [
                ]
            },
            {
                'name': '3',
                'items': [
                    {},
                ]
            },
            {
                'name': '4',
                'items': [
                    {},
                ]
            },
            {
                'name': '5',
                'items': [
                ]
            },
            {
                'name': '6',
                'items': [

                ]
            },
            {
                'name': '7',
                'items': [
                    {},
                    {},
                    {},
                ]
            },
            {
                'name': 'November 1',
                'items': [
                    {},
                    {},
                    {},
                ]
            },
            {
                'name': '2',
                'items': [
                ]
            },
            {
                'name': '3',
                'items': [
                    {},
                ]
            },
            {
                'name': '4',
                'items': [
                    {},
                ]
            },
            {
                'name': '5',
                'items': [
                ]
            },
            {
                'name': '6',
                'items': [

                ]
            },
            {
                'name': '7',
                'items': [
                    {},
                    {},
                    {},
                ]
            },
            {
                'name': 'November 1',
                'items': [
                    {},
                    {},
                    {},
                ]
            },
            {
                'name': '2',
                'items': [
                ]
            },
            {
                'name': '3',
                'items': [
                    {},
                ]
            },
            {
                'name': '4',
                'items': [
                    {},
                ]
            },
            {
                'name': '5',
                'items': [
                ]
            },
            {
                'name': '6',
                'items': [

                ]
            },
            {
                'name': '7',
                'items': [
                    {},
                    {},
                    {},
                ]
            },
            {
                'name': 'November 1',
                'items': [
                    {},
                    {},
                    {},
                ]
            },
            {
                'name': '2',
                'items': [
                ]
            },
            {
                'name': '3',
                'items': [
                    {},
                ]
            },
            {
                'name': '4',
                'items': [
                    {},
                ]
            },
            {
                'name': '5',
                'items': [
                ]
            },
            {
                'name': '6',
                'items': [

                ]
            },
            {
                'name': '7',
                'items': [
                    {},
                    {},
                    {},
                ]
            },
        ];
        return {days}
    }
}
</script>