<template>
  <div class="" id="app">
    <FunctionalCalendar />
    <!-- <h4 style="text-align: center">Calendar</h4>
    <vue-hm-calendar
      mode="year"
      cellSize="15px"
      :eventsDays="{
        '2022-03-01': 10,
        '2022-03-02': 2,
        '2022-03-23': 1,
        '2022-03-24': 1,
        '2022-03-25': 2,
        '2022-03-26': 1000,
        '2022-01-05': 2,
        '2022-08-05': 1,
        '2022-08-06': 2,
        '2022-08-07': 3,
      }"
      :futureEventsColors="['#42A5F5', '#1976D2', '#0D47A1']"
    />
    <vue-hm-calendar
      mode="month"
      cellSize="30px"
      :eventsDays="{
        '2022-04-03': 1,
        '2022-04-02': 2,
        '2022-04-01': 1000,
        '2022-01-05': 2,
        '2022-04-26': 1,
        '2022-04-28': 3,
        '2022-04-27': 2,
      }"
    /> -->
  </div>
</template>

<script>
import FunctionalCalendar from '@/components/MyCalendar.vue'
export default {
  name: 'App',
  components: {
    FunctionalCalendar
  }
}
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
