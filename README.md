# 秀米 + UEditor 对接

这个仓库放置UEditor 集成秀米的示例代码。



## 使用方式

直接下载代码，然后通过 Nginx 代理这里面的静态资源即可。



如果不想这么麻烦，全局安装一个：[serve](https://www.npmjs.com/package/serve) 工具：

```sh
npm install -g serve
```

然后：

```shell
serve ./abner-xiumi-ueditor
```

打开浏览器，即可看到效果！



注意：这个仓库只是把秀米集成进来，关于图片上传的配置还没有完成。

如果还有其他疑问可以参考 [这篇博客](https://blog.csdn.net/six_six_six_666/article/details/116231754)