<script setup>
  import {ref} from 'vue'

  const name =ref('')


</script>

<template>

  <main class="app">

    <selection class="greeting">
      <h2 class="title">
        Welcome back, <input tyep="text" placeholder="Enter Name" v-model="name">
      </input>
      </h2>
    </selection>

    <section class="create-todo">


    </section>

    <section class="todo-list">

    </section>

  </main>

</template>
