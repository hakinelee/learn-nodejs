# Node.js



## fs文件系统模块

> fs模块是Node.js官方提供的、用于操作文件的模块。



导入fs模块来操作文件：

```jsp
const fs = require('fs')
```



1. `fs.readFile()`方法，用于读取指定文件的内容；

   ```js
   fs.readFile(path[, options], callback)
   ```

   - 参数1：（必选）字符串，表示文件的路径
   - 参数2：（可选）表示什么编码格式来读取文件
   - 参数3：（必选）文件读取完成后，通过回调函数拿到读取的结果

2. `fs.writeFile()`方法，用于向指定文件写入内容；

3. ​