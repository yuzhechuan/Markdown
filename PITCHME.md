* Github账户 新建一个工程，比如share
* 在该工程下新建一个名叫PITCHME.md<必须叫这个>的文件 这个文件里就是markdown语法写的你要分享啦，或着导出啦的文档
+++
* 拓展方面可以在创建一个PITCHME.yaml的文件 里面可以存储一些配置 比如
  
  ```yaml
    theme : black//主题
    autoslide : 5500//自动几毫秒后滑动
    mousewheel : true//可以滚轮控制
  ```
详见官网[GitPitch](https://link.jianshu.com/?t=https://github.com/gitpitch/gitpitch/wiki/Slide-Delimiters)

+++

* 还有一个要注意的点，如果想你的文案可以滑动 需要在 PITCHME.md中
进行模块分割，因为它一页只能显示么多
  
    ```markdown
    //分页方式：

    ---      //以这个分割上下 渲染后则是横向滑动切换页面

    +++      //以这个分割上下 渲染后则是竖向滑动切换页面

    ```

+++

* 最重要的是怎么访问，上面已经都准备好原材料了，就差煮了。其实访问很简单：

    ```html
    https://gitpitch.com/user/repo  //打开网站直接输入gitpitch.com/你的github用户名／你的工程名 Ok啦
    ```
