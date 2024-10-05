### 最终页面
	% 在codespace左边的目录栏找到 `“content/authors/admin/_index.md”`这个文件
	% 它就是你最终要展示在网站上的文本内容，根据自己的需要替换相应板块的个人简介，教育经历等信息。
	% 然后，在同样的主目录下修改 `avatar.jpg` 文件，这个文件将是你网站上展示的头像。


### 发布
    % 回到你的github repo页面，点击setting->page，将deployment方式改成“GitHub Actions”，这是GitHub page最新的自动化deploer，可以避免手动git push。接下来就可以愉快地找到最上方一行Actions 菜单，选择“run workflow”来更新/发布你的网站。这个过程可能需要等待半分钟，如果出现小绿标，说明网站已经被成功更新/发布啦，可以点击网址链接查看！
    
    
### 修改细节：
	% header: `config/_default` --> `params.yaml` --> `Site header`
	% 导航界面工具栏：`config/_default` --> `menus.yaml` --> `Main`
	%