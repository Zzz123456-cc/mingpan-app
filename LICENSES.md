# 许可与来源说明

本应用为纯前端网页，全部代码与数据均在用户设备本地运行。以下第三方代码按其 MIT 许可要求附上著作权声明。

## 1. 紫微排盘模块（js/ziwei-bundle.js）

来源：~/workspace/ziwei-doushu/lib/ziwei/ 的 TypeScript 源码（algorithm.ts、constants.ts、wenmo-data.ts、wenmo-tables.generated.ts、wenmo-config.ts、sihua.ts、true-solar-time.ts、patterns.ts、yunxian-context.ts），经 TypeScript 编译器转译为浏览器可用的 JS，仅去除类型标注与一行 server-only 导入，排盘逻辑未改动。原仓库文件未被修改。

其中文墨亮度表与安星表数据按原仓库源码注释，来自文墨天机 v2.5.8 的反编译数据（原仓库已注明来源与口径）；本应用沿用该数据，不另作古籍出处宣称。

MIT License

Copyright (c) 2026 紫微研究

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## 2. 历法库 lunar-javascript（js/vendor/lunar.js，v1.7.7）

来源：6tail/lunar-javascript，用于公历↔农历换算、节气时刻与八字原局。原文件复制，未改动。

MIT License

Copyright (c) 2018 6tail

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
## 3. 紫微排盘库 iztro（js/vendor/iztro.min.js，v2.6.1）

来源：SylarLong/iztro 的浏览器发行版（UMD），紫微模块底层调用其 bySolar/byLunar 与亮度配置。原文件复制，未改动。

MIT License

Copyright (c) 2023 All Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## 4. 本应用自写部分

js/bazi.js（八字引擎）、js/interpret.js（模板化解读）、js/engine.js（输入归一化）、js/app.js（界面逻辑）、index.html、guide.html、manifest.json 与图标均为本应用新写。解读文案为模板化通用表述，不引用古籍原文；涉及星曜性情的关键词取自原仓库 constants.ts 的 STAR_DESCRIPTIONS。
