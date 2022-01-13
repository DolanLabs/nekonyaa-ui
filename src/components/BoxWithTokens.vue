<script>
import designtokens from '../../DolanLabs-Brand-Guideline/designtokens.json';

export default {
  name: 'BoxWithTokens',
  data() {
    return {
      colors: designtokens.global.DolanLabs.Colors.PrimaryColors.IceBlue.value,
    };
  },

  mounted() {
    console.log(this.colors);
  },
};
</script>

<template>
  <div class="box" :style="{background: colors}" />
</template>

<style>
.box {
  height: 100px;
  width: 200px;
}
</style>
