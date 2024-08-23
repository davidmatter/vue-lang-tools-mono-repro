<script setup lang="ts">
import { TestComp } from 'monorepo-lib'
import Hmm from './Hmm.vue'
import NewFile from './NewFile.vue'
import OkComp from './OkComp.vue'
import Test from './test.vue'
</script>

<template>
  <div>
    <Test></Test>
    <Hmm></Hmm>
    <TestComp :b="2" :a="1"></TestComp>
    <NewFile></NewFile>

    <OkComp :a="2" :b="2"></OkComp>
  </div>
</template>
