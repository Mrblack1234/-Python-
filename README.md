# Python库的常用命令
'查看已安装的库'

#ico文件转化为py文件的命令
<RCC>
       <qresource  prefix="">
               <file alias="fyp.ico">fyp.ico</file>
       </qresource>
</RCC>

#打包的程序
pyinstaller -F -w -i fyp.ico FYP.py

