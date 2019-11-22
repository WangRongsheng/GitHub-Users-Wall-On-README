# GitHub-Users-Wall-On-README
:bowtie: 自动将GitHub用户批量渲染生成为README中的用户名&amp;&amp;头像墙

# 预览

<a href="https://imgchr.com/i/MTDAQs"><img src="https://s2.ax1x.com/2019/11/22/MTDAQs.md.png" alt="MTDAQs.png" border="0" /></a>

# 使用

Clone本项目，提取`release`目录下的`GitHubUsersWallOnREADME.jar`，使用下方命令运行：

```
java -jar GitHubUsersWallOnREADME.jar
```

程序刚开始运行会询问列数，到达列数后会自动换行。  
由于GitHub API接口的限制，一小时内只能生成`60`个用户。  
在你输入`q!`以后，程序会自动生成并且保存到`github-wall-result.txt`文件当中。  
你可以将生成后的Markdown，直接复制到你的`README.md`当中：
