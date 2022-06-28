- 把我们的项目交给github托管可以直接访
    1. 这项服务 github pages
    2. 免费的二级域名
        存静态资源

- 问题 
    相对地址有问题
    做如下配置修改
```
    export default defineConfig({
    base:'./',
    plugins: [react()]
    })
```
    工程化vite 配置 将index.html 与assets 联系 配置成 ./
    github  中  / 根目录 有好多文件