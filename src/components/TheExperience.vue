
<script setup lang="ts">
import { TresCanvas, useRenderLoop } from '@tresjs/core'
import { reactive, shallowRef } from 'vue'
import { BasicShadowMap, SRGBColorSpace, NoToneMapping } from 'three'
import { OrbitControls } from '@tresjs/cientos'

const gl = reactive({
  clearColor: '#82DBC5',
  shadows: true,
  alpha: false,
  //shadowMapType: BasicShadowMap,
  //outputColorSpace: SRGBColorSpace,
  //toneMapping: NoToneMapping,
})

</script>
<template>


</template>