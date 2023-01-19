<script>
  import { page } from '$app/stores'
</script>

<h1> In locale: {$page.params.locale} </h1>

<slot/>
