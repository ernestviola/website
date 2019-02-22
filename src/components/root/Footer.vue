<template>
  <footer class="bg-light py-5">
      <div class="container">
        <div class="small text-center text-muted">Copyright &copy; {{ currentYear }} - Start Bootstrap</div>
      </div>
    </footer>
</template>

<script>
const date = new Date()
export default {
  data: () => ({
    currentYear: date.getFullYear()
  })
}
</script>
