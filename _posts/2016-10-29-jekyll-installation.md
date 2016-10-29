---
title:        "安装Jekyll"
description:  "Jekyll安装及写静态博客"
image:        "http://placehold.it/400x200"
author:       "Vic"
---
&nbsp;   
安装步骤:  
1.下载、安装 ruby 和 DEVELOPMENT KIT  
&nbsp; &nbsp; 地址 [*http://rubyinstaller.org/downloads/*](http://rubyinstaller.org/downloads/)  
&nbsp; &nbsp; Ruby 2.3.1 对应 DevKit-mingw64-32-4.7.2-20130224-1151-sfx.exe   
&nbsp; &nbsp; ruby安装到 D:\Ruby23  	
&nbsp; &nbsp; DevKit安装到 D:\DevKit  
~~~  
cd D:\DevKit  
ruby dk.rb init  
ruby dk.rb install  
~~~  
2.更改gem镜像，可以改善国内Ruby安装的速度  
~~~
gem sources --remove https://rubygems.org/  
gem sources -a http://gems.ruby-china.org/  
gem sources -l         #查看是否只有国内镜像  
~~~  
3.安装jekyll  
~~~
gem install jekyll  
~~~  
4.安装rdiscount，这个是用来解析Markdown标记的解析包。
~~~
gem install rdiscount  
~~~  
5.编译md文件，启动博客
~~~
jekyll serve  
~~~  
6.浏览博客  
&nbsp; &nbsp; 浏览器中打开[*http://127.0.0.1:4000*](http://127.0.0.1:4000)  
&nbsp;  

7.如需卸载
~~~
gem uninstall jekyll  
~~~  
   

Reference：  
>安装：[*http://www.tuicool.com/articles/7Vz6BzJ*](http://www.tuicool.com/articles/7Vz6BzJ)  
>安装：[*http://blog.csdn.net/rainloving/article/details/45745491*](http://blog.csdn.net/rainloving/article/details/45745491)  
>出错处理：[*http://blog.csdn.net/springlustre/article/details/52728813*](http://blog.csdn.net/springlustre/article/details/52728813)  
>博客主题：[*http://jekyllthemes.org*](http://jekyllthemes.org)   

&nbsp;  
[[**Home**]  > > >](/)    

>Designed and developed by [@Vic Chen](http://blog.csdn.net/k_shmily) \|\| Contact <a href="mailto:vic_chen@hotmail.com" class="email" title="联系邮箱">vic_chen@hotmail.com</a>