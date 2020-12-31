<template>
  <div class="doctor">
    <ul>
      <li v-for="doctor in docs" :key="doctor">{{ doctor }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Doctor",
  data: () => {
    return {
      docs: [
        "Doctor :",
        "Phone Number :",
        "Email :",
        "Adresse :",
        "Disponibility",
      ],
    };
  },
};
</script>
