<script lang="ts">
  const currentTime = new Date()
  const currentHour = currentTime.getHours()

  let greeting = ""

  if (currentHour >= 6 && currentHour < 12) {
    greeting = "Good morning"
  } else if (currentHour >= 12 && currentHour < 18) {
    greeting = "Good afternoon"
  } else {
    greeting = "Good evening"
  }
</script>

<h1 class="text-3xl font-bold text-white">{greeting}</h1>