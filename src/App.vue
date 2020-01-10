<template>
  <div id="app">
    <ul>
      <NavItem tooltip="The start of this web page" tooltip-trigger="focus">Start</NavItem>
      <NavItem tooltip="My personal projects" tooltip-trigger="hover">Projects</NavItem>
    </ul>
  </div>
</template>

<script>
import NavItem from './components/NavItem'

export default {
  name: 'app',
  components: {
    NavItem
  }
}
</script>
