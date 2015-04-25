
书写 Blog 
*********************
我们鼓励工程师将日常工作的笔记以Blog的形式发表。
公开发表工作笔记，首先，便于客户了解我们的工作内容，增加与客户的交流。
第二，有利于工程师自己整理思路。
Blog不需要写的非常详细，不必写成文档的形式；
只需要将最核心的思想描述清晰就很好了。

因为我们的Blog系统是给程序员使用的，
所以将过去的wordpress迁移到jekyll系统。
Jekyll没有很好的图形界面，但是完全可以用git管理，
这是我们更喜欢的方式。

下载源码
==========
Blog的内容托管在github.com。
简单的 ``git clone https://github.com/EMSYM/octopress.git`` 即可实现
如果增加笔记、修改内容，请先在github fork https://github.com/EMSYM/octopress/fork ，
再按照 :ref:`github的提交流程 <github-patch>` 发起pull request。

编译
=====
生成网站需要安装octopress，具体参考 `octopress 的文档 <http://octopress.org/docs>`_ 

因为 Jekyll 基于 ruby 开发，所以需要先安装 ruby，要求版本≥1.9.3

.. code-block:: console

   git clone https://github.com/EMSYM/octopress.git emsym
   cd emsym
   gem install bundler
   bundle install
   rake install
   rake preview

打开 http://localhost:4000 即可

新建页面
=====================
仍然参考octopress的官方文档。

当一个页面写好后，按照 :ref:`github的提交流程 <github-patch>` ，
将新建的页面合并至主干。

格式
====================================
文字的格式参考 `Jekyll官方文档 <http://jekyllrb.com/docs/home/>`_



