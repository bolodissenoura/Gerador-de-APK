<template>
  <web-view
    class="cont"
    :source="{
      uri: 'https://crossdocking.homologacao.boostech.com.br/mobile/',
    }"
  />
</template>

<script>
import { WebView } from "react-native-webview";

export default {
  name: "myComponent",
  components: {
    "web-view": WebView,
  },
};
</script>
<style>
</style>

