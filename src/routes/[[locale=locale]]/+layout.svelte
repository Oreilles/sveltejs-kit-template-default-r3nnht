<script>
  import { page } from '$app/stores'
</script>

<h1> In locale: {$page.params.locale} </h1>
<h1> In category: {$page.params.category} </h1>
<h1> In page: {$page.params.slug} </h1>

<slot/>
