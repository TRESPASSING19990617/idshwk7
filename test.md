Debian和Ubuntu系统：使用sudo apt install steghide命令安装Stephide工具

隐藏文件：
steghide embed -ef secret.txt -cf test.jpg
输入口令：57117229
secret.txt被隐藏到test.jpg中

提取文件：
steghide extract -sf test.jpg
输入密码：57117229
得到隐藏文件secret.txt
