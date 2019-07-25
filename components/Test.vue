<template>
  <section>
      <div>
        <a-button>Primary</a-button>
      </div>
  </section>
</template>

<script lang="ts">
import Vue from 'vue'
import { Component } from 'vue-property-decorator'
import { Button } from 'ant-design-vue'

@Component({
  components:{
    'a-button' : Button
  }

})
export default class Test extends Vue {
}
</script>