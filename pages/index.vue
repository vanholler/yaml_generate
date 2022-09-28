<template>
  <div class="center grid">
    <vs-row>
      <vs-col vs-type="flex" vs-justify="center" vs-align="center" w="12">
        header
      </vs-col>
    </vs-row>
    <vs-row>
      <vs-col :key="index" vs-type="flex" vs-justify="center" vs-align="center" w="6">
        interface
      </vs-col>
      <vs-col :key="index" vs-type="flex" vs-justify="center" vs-align="center" w="6">
        code swagger!
      </vs-col>
    </vs-row>

  </div>
</template>


<script>
export default {
  name: 'IndexPage',
  data:() => ({
    active: 0
  })
}
</script>
