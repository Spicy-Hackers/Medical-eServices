<template>
  <div class="pharmacy">
    <ul>
      <li v-for="pharmacy in docs" :key="pharmacy">{{ pharmacy }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Pharmacy",
  data: () => {
    return {
      docs: [
        "Pharmacy :",
        "Phone Number :",
        "Email :",
        "Adresse :",
        "Disponibility",
      ],
    };
  },
};
</script>

}
