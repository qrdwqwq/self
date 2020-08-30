<template>
  <div>
    <b-table striped hover :items="items"></b-table>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        items: [
          { age: 40, first_name: 'Dickerson', last_name: 'Macdonald' },
          { age: 21, first_name: 'Larsen', last_name: 'Shaw' },
          { age: 89, first_name: 'Geneva', last_name: 'Wilson' },
          { age: 38, first_name: 'Jami', last_name: 'Carney' },
          { age: 40, first_name: '志远', last_name: '张' },
          { age: 24, first_name: '守约', last_name: '百里' },
          { age: 22, first_name: '玄策', last_name: '百里' },
          { age: 18, first_name: '婉儿', last_name: '上官' }
        ]
      }
    }
  }
</script>