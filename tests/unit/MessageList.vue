<template>
  <ul>
    <li v-for="message in messages">
      {{ message }}
    </li>
  </ul>
</template>

<script>
export default {
   name: 'List',
   props: ['messages']
};
</script>