<template>
  <web-view
    :source="{ uri: 'https://crossdocking.homologacao.boostech.com.br/' }"
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
.container {
  background-color: pink;
  align-items: center;
  justify-content: center;
  flex: 1;
}
.text-color-primary {
  color: black;
}
</style>