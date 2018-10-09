1、下载安装文件
wget -c --no-check-certificate https://github.com/SeagullGR/Hello-China/raw/master/l2-2015.tar.gz
2、加压文件
tar zxvfp l2-2015.tar.gz
3、运行文件
./l2.sh 2>&1 | tee install.log
4、运行选项：
（1）1为安装
（2）2为修复
（3）3为添加账户
