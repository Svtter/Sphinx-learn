构建readthedocs文档
==================

使用sphinx构建这个文档，主要需要注意几个方面。

1. 按照官方的文档，使用 ``sphinx-quickstart`` ，创建好github-repo。

2. 根据 /source/conf.py 中的 ``html_conf`` 进行修改，修改为自己的github-username和github-repo-name。

3. 打开repo的settings，复制readthedocs中的webhook-url到webhook选项中。

4. 进行推送并且测试。
