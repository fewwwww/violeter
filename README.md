1. 安装依赖

    `yarn`

2. 运行页面

    `"dev:h5": "npm run build:h5 -- --watch",`

3. 编写样式

    项目使用windicss作为样式框架, 类似tailwindcss.

    语法为:
    `<Text className='p-10'>Violeter!</Text>`

    等价于:
    `<Text style={{padding: '10'}}>Violeter</Text>`

    更多语法:
    `参照 https://windicss.org/utilities/`

    在vscode中可以使用: WindiCSS IntelliSense插件自动补全

4. 组件规范

    使用Functional组件与React Hooks

........