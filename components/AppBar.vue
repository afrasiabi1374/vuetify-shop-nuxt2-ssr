<template>
    <div
      class="d-flex justify-center align-center"
      style="height: 80px;"
    >
        <div class="d-flex align-center align-center justify-space-between" style="width: 98%">
            <div class="d-flex align-center align-center justify-center">
            <v-icon class="pointer rounded-circle"  x-large style="cursor: pointer;">mdi-menu</v-icon>
            <v-toolbar-title  class="display-2 ml-6 font-weight-bold blue--text" style="cursor: pointer;">SHOPY!!!</v-toolbar-title>
            </div>

            <div class="d-flex align-center align-center justify-center">

            <v-btn icon x-large>
                <v-icon x-large>mdi-cart</v-icon>
            </v-btn>
            <v-btn icon large>
                <v-icon large>mdi-account</v-icon>
            </v-btn>
            </div>
        </div>

    </div>


</template>

<script>
export default {
  name: 'INDEX'
}
</script>

<style lang="scss">

</style>
