<template>
  <div id="app">
    <div>
      <h1>SMS</h1>
      <qrcode value="SMSTO:28577:palavra-chave" :options="{ width: 200 }"></qrcode>
    </div>
    <div>
      <h1>WhatsApp</h1>
      <qrcode value="https://wa.me/551148377404?text=palavra-chave" :options="{ width: 200 }"></qrcode>
    </div>
  </div>
</template>

<script>
import VueQrcode from '@chenfengyuan/vue-qrcode'

export default {
  name: 'App',
  components: {
    'qrcode': VueQrcode
  }
}
</script>

