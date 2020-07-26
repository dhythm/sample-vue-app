<template>
  <v-card class="mx-auto" max-width="400" tile>
    <v-list-item v-for="(value, idx) in object" :key="idx">
      <v-list-item-content>
        {{ value }}
      </v-list-item-content>
    </v-list-item>
  </v-card>
</template>

<script>
export default {
  data: () => ({
    object: {
      title: "How to do lists in Vue",
      author: "Jane Doe",
      publishedAt: "2016-04-10",
    },
  }),
};
</script>
