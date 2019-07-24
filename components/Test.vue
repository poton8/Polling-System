<template>
  <section class="container">
      <div>
        <a-button >Primary</a-button>
      </div>
  </section>
</template>

<script lang="ts">
import Vue from 'vue'
import { Component } from 'vue-property-decorator'
import { Tag } from 'ant-design-vue'

@Component
export default class Test extends Vue {
    'a-button' : Tag
}
</script>