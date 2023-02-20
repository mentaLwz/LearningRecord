# 探索

- 参考的教程
  [neovim from scrath](https://www.youtube.com/watch?v=ctH-a-1eUME&list=PLhoH5vyxr6Qq41NFL4GvhFp-WLd5xzIzZ)

- 难点
  - 怎么装插件 packer, lua的基本语法，配置的基本概念

  - LSP
    - 一个要注意的点， 要生产`compile_commands.json`, 通过加`-DCMAKE_EXPORT_COMPILE_COMMANDS=1`来生成，不然有些语法解析会误报，[参考](https://stackoverflow.com/questions/66987008/how-to-configure-clangd-to-find-missing-external-header-file)

  - 在某些环境可能要用代理才能下载，导致会卡在`sudo make install`卡在download，一个措施是把`file(DOWNLOAD ...)` 改成`excute_process(COMMAND wget ...)`,但是还是要把一些status的判断去掉

  - 大型项目还在试验，'ninjia'也是可以可以输出`compile_commands.json`的，用`-t compdb `

- 要注意的点
  - 熟悉keymap，多用



