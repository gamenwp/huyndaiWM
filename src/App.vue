<template>
<HeaderSect />
<MainSect />
<Models />
<Service />
<About />
<Form />
<CopyRight />
</template>

<script>
import HeaderSect from './components/headerSection.vue'
import MainSect from './components/main.vue'
import Models from './components/models.vue'
import Service from './components/service.vue'
import About from './components/about.vue'
import Form from './components/formSection.vue'
import CopyRight from './components/copy.vue'

export default {
  name: 'App',
  components: {
HeaderSect,
MainSect,
Models,
Service,
About,
Form,
CopyRight
  }
}
</script>

<style lang="scss">
@import "./assets/styles/normilize.scss";
@import "./assets/styles/style.scss";
</style>
