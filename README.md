# iohook-rebuild

[构建所需的依赖项](https://wilix-team.github.io/iohook/manual-build.html)

编译命令：根据当前平台进行指定版本构建
runtime：electron/node 构建electron版本或者node版本
version: electron或node版本号
abi：构建的Electron/node的[ABI](https://nodejs.org/en/docs/guides/abi-stability)版本


build.js：144行

```json
# node版本：16.17.0，npm版本：8.15.0，node-gyp版本：10.2.0，msvs_version版本：2017，python：3.11.3
# 支持到electron@26.6.10
>>
npm run build:abi99
or
node build.js --runtime electron --version 16.2.8 --abi 99 --upload=false

npm run build:abi116
or
node build.js --runtime electron --version 26.6.10 --abi 116 --upload=false
```



## iohook

手动构建参考[iohook官网](https://wilix-team.github.io/iohook/manual-build.html)

## License

All changes that I made are released under the MIT license.

> The MIT License (MIT)
>
> Copyright (c) 2023 Libaizhu
>
> Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
> 
> The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
> 
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

The license of the iohook module itself can be found in the `LICENSE` file in this repository.
