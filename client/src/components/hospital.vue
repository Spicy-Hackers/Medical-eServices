<template>
  <div class="hospital">
    <ul>
      <li v-for="hospital in docs" :key="hospital">{{ hospital }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Hospital",
  data: () => {
    return {
      docs: [
        "hospital :",
        "phone number :",
        "email :",
        "adresse :",
        "disponibility",
      ],
    };
  },
};
</script>
