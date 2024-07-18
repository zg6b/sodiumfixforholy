# sodiumfixforholy
Fixed the issue that the Sodium renderer was not available in Holy
修复了sodium在holy渲染器不可用的情况
其实只需要删除sudium.mixins.json文件中的：
core.render.world.WorldRendererMixin
workarounds.event_loop.RenderSystemMixin
core.render.world.BufferBuilderStorageMixin
三行文字即可
