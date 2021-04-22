<template>
  <div class="schema-types">
    <h3 class="schema-types__title">Pick a Schema Type</h3>
    <input list="schema-types__types" id="schema-choice" name="schema-choice" />
    <datalist id="schema-types__types">
      <option value="Blog Post" />
      <option value="Event" />
    </datalist>
  </div>
</template>

<script>
export default {
  name: 'Types',
}
</script>

<style scoped>

</style>
