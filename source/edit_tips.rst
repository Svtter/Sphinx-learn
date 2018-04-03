编写技巧
=========

.. contents::

``:source:`` 链接源代码。

不知道

语法
----

语法可以参考:

+ 首先参考：https://github.com/ralsina/rst-cheatsheet/blob/master/rst-cheatsheet.rst
+ https://zh-sphinx-doc.readthedocs.io/en/latest/rest.html
+ http://www.cnblogs.com/seayxu/p/5603876.html

插入代码
^^^^^^^

1. 插入代码是通过在第一行末尾加上 :: ，然后第二行开始缩进。
2. 使用 ``.. code:: python`` ，第二行缩进


反双引号使用的时候，要注意不要在反双引号两边留下空格。

.. 不知道为什么我的反双引号总是不好用。。

引用文件
-------

使用如下格式::

 需要引用的文件 `need_to`_
 
 .. _`need_to`: need_to.rst

由上所述。


Sphinx自动构建
-------------

通过 ``sphinx-autobuild`` 可以自动构建文档，实时浏览。

https://nbsphinx.readthedocs.io/en/0.3.2/usage.html#Watching-for-Changes-with-sphinx-autobuild


Sphinx使用ipython-notebook
----------

https://ipython.org/ipython-doc/rel-0.13.2/development/ipython_directive.html
