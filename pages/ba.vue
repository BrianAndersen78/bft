// Midlertidige tests af moduler og eksempler på brug af indbyggede moduler
<template>
  <div>
    <h1>Moments</h1>
    <p>Eksempel med Date object {{ $moment(Date.now()).format('dddd') }}</p>
    <p>Eksempel med relativ tid {{ $moment().startOf('day').fromNow() }}</p>
    <p>Fuld dokumentation https://momentjs.com/</p>
  </div>
</template>

<script>
export default {}
</script>
<style scoped></style>
