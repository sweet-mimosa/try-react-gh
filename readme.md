- 把项目上线 交给github托管 可以直接访问
    1. 这项服务的名字叫 github pages
    2. 给我们一个免费的二级域名
        纯静态资源

1. 打包完之后 相对地址有问题
    ```js
    export default defineConfig({
        plugins: [react()],
        base: './'
    })
    ```
    修改vite配置添加base
    工程化vite配置 将index.html 与 assets 的关系配置成 ./
    github 中可能有好多个项目
    / 根路径