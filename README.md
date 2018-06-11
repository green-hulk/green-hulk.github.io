## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/green-hulk/green-hulk.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/green-hulk/green-hulk.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

## Jenkins
### 什么是Jenkins？
一个工具。</br>
一个一键式工具。</br>
一个一键式持续部署项目的工具。</br>
除此之外，还有......</br>
官方详解[Jenkins](https://jenkins.io/).

### 为什么会用到Jenkins？
convenient!</br>
回想之前没有jenkins的日子：sad!</br>
Jenkins易于安装，易于配置，各种插件基本满足你们所有的需求。

### Jenkins的心路历程
Jenkins的前身叫做Hudson。2004年Sun公司创作了Hudson，2015年2月Hudson首次发布。2009年Sun公司被Oracle收购，2011年1月投票决定将Hudson重命名为Jenkins，成为一个open source。2011年2月Oracle决定继续开发Hudson，并认为Jenkins不是Hudson的重命名项目，而是Hudson的一个分支。所以Jenkins和Hudson并不是父子关系，而是兄弟关系。

### 手把手教你安装Jenkins
Jenkins的本质就是一个普通的Java编写的项目，只要将其war包放在tomcat的webapp下，启动tomcat即可。
1. 下载jenkins.war
Jenkins有两个发行版本，LTS和Weekly。LTS比较稳定，每隔12周发行一版。Weekly每周发行一版，为用户和插件开发人员提供错误修复和功能。根据自己需要选择。两个发行版本均适用与各个不同的领域，例如：Java，Docker，FreeBSD等等。这里选择的是：LTS下的Generic Java package(.war)。
2. 安装JDK</br>
略。
3. 安装Maven</br>
略。
4. 安装git</br>
略。
5. 安装tomcat</br>
略。
6. 启动Jenkins</br>
将jenkins.war mv tomcat/webapp 中，启动tomcat。
访问路径：<tomcat:ip>/jenkins
7. 解锁Jenkins</br>
第一次访问Jenkins实例，需要Unlock Jenkins。Administrator password:获取路径 <home>\.jenkins\secrets\initialAdminPassword（该路径有提示）。
8. Jenkins 离线</br>
![parameters](http://souche.oss-cn-hangzhou.aliyuncs.com/20180509/png/ef5fff65a3002b4177b849a480304a0d.png)

### 手把手教你部署一个普通项目





