spa单页应用。仅仅在Web页面初始化的时候加载JavaScript、CSS、HTML。一旦页面加载完成，SPA不会因为用户的操作去进行页面的重新加载和跳转。取而代之的是利用路由机制实现HTML内容的变化，UI的变化，和响应用户的操作。避免页面的重新加载。

**优点**

- 一旦页面加载完毕，用户的页面跳转操作体验是良好的。不需要重新加载页面。避免了重新渲染。
- 基于第一点，所以，对服务器来说，压力相对较小。

**缺点**

- 初次加载的时候，耗时较多。
- 会阻碍浏览器本身的前进和后退。所有的页面需要自己建立堆栈管理。
- SEO的难度较大。