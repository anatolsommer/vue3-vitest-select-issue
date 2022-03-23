# Problem with select elements in Vue3/vitest/happy-dom
## npm test
```
stderr | src/App.test.js > mount component
[Vue warn]: Unhandled error during execution of directive hook 
  at <App ref="VTU_COMPONENT" > 
  at <VTUROOT>

 ❯ src/App.test.js (1)
   × mount component

⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯ Failed Tests 1 ⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯

 FAIL  src/App.test.js > mount component
TypeError: Cannot read properties of undefined (reading 'length')
 ❯ setSelected node_modules/@vue/runtime-dom/dist/runtime-dom.cjs.js:1295:36
 ❯ mounted node_modules/@vue/runtime-dom/dist/runtime-dom.cjs.js:1279:9
 ❯ callWithErrorHandling node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:157:22
 ❯ callWithAsyncErrorHandling node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:166:21
 ❯ invokeDirectiveHook node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:3726:13
 ❯ Array.<anonymous> node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:4587:25
 ❯ flushPostFlushCbs node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:352:47
 ❯ render node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5576:9
 ❯ mount node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:3856:25
 ❯ Object.app.mount node_modules/@vue/runtime-dom/dist/runtime-dom.cjs.js:1539:23

⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯[1/1]⎯
```
