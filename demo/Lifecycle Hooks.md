
Vue2	Vue3
beforeCreate	setup(替代)
created	setup(替代)
beforeMount	onBeforeMount
mounted	onMounted
beforeUpdate	onBeforeUpdate
updated	onUpdated
beforeDestroy	onBeforeUnmount
destroyed	onUnmounted
errorCaptured	onErrorCaptured
空	onRenderTracked
空	onRenderTriggered

export default {
  onRenderTriggered(e) {
    debugger
    // inspect which dependency is causing the component to re-render
  }
}