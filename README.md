# YY
myCode

# GitHub 上传操作
  1.github新建仓库
  2.本地新建文件
    1.git init （在git bash here 窗口里输入，会在所创建的本地文件夹里生成一个.git的文件夹 有些可能会隐藏这个文件，只需在查看里勾选隐藏项目这个选项即可）
    2.在本地创建的文件中和.git同级的文件夹里添加要上传的文件
    3.git add *  （ 也可将*换成要上传的文件的名字）
    4.git commit -m "说明"  （第一次可能会输入邮箱和用户名，按照提示操作即可）
    5.git remote add origin https://github.com/yang1633/YY.git  （如果出错可用：git remote rm origin）
    6.git push -u origin master  (如果出错可用：git push -u origin master -f) (第一次可能会输入用户名和密码)
  
第二次

1. git add *
2.git commit -m "说明"
3. git push  
