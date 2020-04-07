# trackray-resources
TrackRay 的资源文件项目



将该项目下载重命名为 “resources”文件夹，并移动到trackray主程序目录下。


国内从 GitHub 下载速度会比较慢，可前往码云下载资源文件。


https://gitee.com/b1u3r/resources


# 使用方法

1. clone 项目或直接下载 zip 文件，将下载好的项目目录命名为“resources”
```
git clone --depth=1 https://gitee.com/b1u3r/resources.git resources
```
2. 在 trackray 源码目录执行编译命令
```
mvn clean package
```
3. 编译成功后会生成“release”目录，里面存放着溯光主程序文件，将“resources”目录移动到“release”目录，必须和溯光主程序文件在同级目录

4. 运行溯光
