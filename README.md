# electron3d
名称：electron3d
作者：宅家呗
网址：https://zjbcool.com

本程序可以实现快速将web3D应用程序打包为windows桌面程序，方便Web3D开发者用于桌面演示，仅需以下3步：

1 下载解压后，首先执行electron3d.exe，确保能打开窗口，看到提示信息：“Web3D应用程序正常运行!”

2 关闭窗口。将你的Web3D应用程序的所有文件（html/css/js/等文件）拷贝到C:\electron3d\resources\app\web3d\，如果提示有同名文件，选择覆盖。

3 如果你的启动文件是是默认的index.html，直接跳到第4步，运行桌面程序即可；如果你的启动文件不是默认的，比如是app.html，则需要在app目录下打开main.js，修改入口文件，将index.html，替换成你的app.html
mainWindow.loadFile('web3d/index.html')

4 重新打开electron3d，成功。

如有问题请到web3d技术交流群850626045咨询。
