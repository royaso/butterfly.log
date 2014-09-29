butterfly.log
=============

>Everyone is like a butterfly, they start out ugly and awkward and then morph into beautiful graceful butterflies that everyone loves. 

>蝴蝶很美，但起于丑陋，代码虽简，但始于行下

[示例博客](http://gowithwind.github.io/blog/)

#初心

简单但是可靠

#实现原理

github pages + ajax + markdowm

#部署

- 克隆本项目
- 有些需要自定义的部分请修改
- 将代码复制到你的github pages 下的指定目录即可

#优点

- 不依赖本地repo
- 智能一级标题导航
- 所有文章都用markdown编写
- ui完全可以自主定制
- 简单可靠

#缺陷

可能不支持seo

#支持评论
你可以添加第三方评论，例如disqus

  <div id="disqus_thread"></div>
  <script type="text/javascript">
      /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
      var disqus_shortname = 'gowithwind'; // required: replace example with your forum shortname
      /* * * DON'T EDIT BELOW THIS LINE * * */
      (function() {
          var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
          dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
          (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
      })();
  </script>  

#协议

遵循MIT协议
