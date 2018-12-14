# Young77
1.编辑器使用 VSCode
2.前端项目，引入PingFang SC字体---对应页面：font-pf.html
2-1.步骤：a,下载想要引入的字体
         b,在CSS文件中使用@font-face属性进行设置
         c,使用方法见页面内容所示
2-2.超级nice的插件推荐：1、Autoprefixer---这个可以解决浏览器兼容，自动添加前缀，安装方法：
                a.打开扩展程序，输入  autoprefixer  查找插件
                b.安装好后运行：npm  i  -g autoprefixer
                c.在菜单里设置：File -> Preferences -> Keyboard Shortcuts:
                  {
                    "key": "ctrl+shift+c",
                    "command": "autoprefixer.execute"
                  }
                d.然后写了样式保存后，按 ctrl+shift+c 就可以格式化了。当然，是一键格式当前文件所有，不用每次都格式化。(快捷键可自定义)
              2、scss-to-css---最简单易用的SCSS编译器, 可自动编译scss文件及补全前缀,可用于对scss文件进行简单的编译/压缩, 而不用安装各种前端工程                 化工具(webpack等)。写好保存后会自动生成对应的css文件
              
3.截取屏幕，保存图片并下载---对应页面：html2canvas.html
3-1.超级nice的插件推荐：html2canvas---详情见官网及本例页面详情
