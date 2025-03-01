### s-lint是什么
s-lint是**一个全面、通用的前端Lint规范解决方案**，
与其他规范方案不同的是，业内流行的方案通常解决某一(JS或Style等)规范，如[eslint-config-airbnb](https://github.com/airbnb/javascript)、[eslint-config-standard](https://github.com/standard/eslint-config-standard)等，而selling-lint是一个规范集合，基本覆盖目前前端技术栈，另一方面，提供轻量的脚手架工具，使用简单。

### 特点
- 覆盖全面

    包括前端开发基础规范**ESLint(Vue、React、Taro、Next、Nuxt)、StyleLint(Less、CSS)、CommitLint**
- 使用简单

    提供三大基础包，安装即用；且提供轻量级命令行，一键为项目添加规范、升级规范
- 易于扩展

    Lerna统一版本模式发包，便于基础包升级、扩展自定义paser、plugin等
- 与时俱进

    第一时间跟进最新的规则

### 架构图
![image.png](https://storage.360buyimg.com/hawley-common/lint.jpg)
### 基础包
| 包名 | 功能 | npm
|  ----  |  ----  | ---
| eslint-config-selling | 提供eslint规范   | https://www.npmjs.com/package/eslint-config-selling 
| stylelint-config-selling | 提供stylelint规范 | https://www.npmjs.com/package/stylelint-config-selling
| commitlint-config-selling | 提供commitlint规范 | https://www.npmjs.com/package/commitlint-config-selling
| selling-lint-cli | 命令行工具 | https://www.npmjs.com/package/selling-lint-cli

### 使用
> 提供两种使用方式，1、利用脚手架 2、在工程中安装相对的包。推荐方式1


#### 1、使用脚手架
见[CLI介绍](packages/@jd/selling-lint-cli/README.md)

#### 2、直接使用
- **ESLint**

    见[ESLint介绍](packages/@jd/eslint-config-selling/README.md)

- **StyleLint**

    见[StyleLint介绍](packages/@jd/stylelint-config-selling/README.md)

- **CommitLint**

    见[CommitLint介绍](packages/@jd/commitlint-config-selling/README.md)

### 参与贡献
遇到任何问题，欢迎提交[issue](https://github.com/jd-antelope/s-lint/issues)
