<template>
    <FunctionalCalendar
       v-model="calendarData"
      
       :sundayStart="true"
       :date-format="'dd/mm/yyyy'"
       :is-date-range="true"
      :is-date-picker="true"
      >
         <!-- v-on:changedMonth="changedMonth"
       v-on:changedYear="changedYear" -->
      </FunctionalCalendar>
</template>

<script>
import { FunctionalCalendar } from 'vue-functional-calendar';
    export default {
    components: {
        FunctionalCalendar
    },
    data() {
        return {
            calendarData: {}
        }
    }
}
</script>

<style scoped>

</style>