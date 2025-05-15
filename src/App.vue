<script setup lang="ts">
console.log('Hello world')
</script>

<template>
  <div>
    <h1>RNLI - Technical Task</h1>

    <table>
      <thead>
        <tr>
          <th>ID</th>
          <th>Title</th>
          <th>Completed</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>To do</td>
          <td>false</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<style scoped>
table {
  border-collapse: collapse;
  border-spacing: 0;
}

table th,
table td {
  padding: 8px;
  border: 1px solid orange;
}
</style>
