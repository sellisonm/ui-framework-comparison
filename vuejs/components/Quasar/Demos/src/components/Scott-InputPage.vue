<template>
  <q-layout
    ref="layout"
    view="lHh Lpr fff"
    :left-class="{'bg-grey-2': true}"
  >
    <q-toolbar slot="header" class="glossy">
      <q-toolbar-title>Input Page Example
      </q-toolbar-title>
    </q-toolbar>


    <q-layout ref='layout'>


  <div style=" margin: 20px">
      <q-tabs color="brown" align="justify">
        <q-tab default name="mails" slot="title" icon="monetization on" label="Assets" />
        <q-tab name="alarms" slot="title" icon="show chart" label="Performance" />
        <q-tab name="movies" slot="title" icon="short text" label="Characteristics" />

        <q-tab-pane name="mails">
         <q-input v-model="number" stack-label="Total Assets" prefix="$" />
         <q-input v-model="number" stack-label="Total Accounts" max-decimals=0 />
         <q-input v-model="text" stack-label="Total Assets" />
         
        </q-tab-pane>
        <q-tab-pane name="alarms">Alarms tab</q-tab-pane>
        <q-tab-pane name="movies">Movies tab</q-tab-pane>
      </q-tabs>
  </div>


      <q-toolbar slot='footer'>
        <q-icon name='save' />
      </q-toolbar>

    </q-layout>
  </q-layout>
</template>

<script>
import {
  QLayout,
  QToolbar,
  QToolbarTitle,
  QBtn,
  QIcon,
  QList,
  QListHeader,
  QItem,
  QItemSide,
  QItemMain,
  QTab,
  QTabPane,
  QTabs,
  QOptionGroup,
  QInput,
  QField
} from 'quasar'
export default {
  name: 'index',
  components: {
    QLayout,
    QToolbar,
    QToolbarTitle,
    QBtn,
    QIcon,
    QList,
    QListHeader,
    QItem,
    QItemSide,
    QItemMain,
    QTab,
    QTabs,
    QTabPane,
    QOptionGroup,
    QInput,
    QField
  }
}
 </script>

<style lang="stylus">
.logo-container
  width 255px
  height 242px
  perspective 800px
  position absolute
  top 50%
  left 50%
  transform translateX(-50%) translateY(-50%)
.logo
  position absolute
  transform-style preserve-3d
</style>
