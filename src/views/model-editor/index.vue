<template>
  <page-wrapper title="Model Editor" :content="description">
  </page-wrapper>  
</template>

<script lang="ts" setup>
import { SmileOutlined, DownOutlined } from '@ant-design/icons-vue';

const { pkg } = __APP_INFO__
const { description } = pkg

</script>
