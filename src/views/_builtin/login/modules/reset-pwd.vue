<script setup lang="ts">
import { useRouterPush } from '@/hooks/common/router';
import { $t } from '@/locales';

defineOptions({
  name: 'ResetPwd'
});

const { routerBack } = useRouterPush();
</script>

<template>
  <div class="reset-pwd">
    <NButton size="large" round block @click="routerBack">
      {{ $t('page.login.common.back') }}
    </NButton>
  </div>
</template>

<style scoped></style>
