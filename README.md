
### Summary
it wrappers comment macros and let it use as grunt plugin.
so we can config it by gruntfile, makes it support specific marcos clean up and make a connect middleware which deliver the processed version js file etc

### Config

``` js
{
     “comment-macros”: {
          target: {},
          macros: {
               ‘log’: {
                    // identify, plugin handler
               },
               ‘var’: {
                    // 替换变量值
               },
               ‘break’: {

               }
          },
          clean: {‘var’, ‘break’}
     }
}
```

### Misc
// 通过在connect中间件分发的时候，替换掉process后的





