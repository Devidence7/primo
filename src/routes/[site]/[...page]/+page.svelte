<script>
  import { PrimoPage } from 'primo-builder'

  export let data
</script>

<PrimoPage
  page={{
    ...data.page,
    sections: data.sections,
  }}
/>
