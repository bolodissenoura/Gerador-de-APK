<template>
  <web-view
    class="cont"
    :source="{
      uri: 'AQUI VAI SUA URL',
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

