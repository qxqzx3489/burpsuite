# burpsuite_pro 开心版
# 测试环境 Archlinux windows11 ubuntu20.10
## 理论全平台通用
## 作者:
    Loader: https://github.com/x-Ai/BurpSuiteLoader
    Keygen: BurpSuite Keygen
    Loader&Keygen: https://forum.exetools.com/showpost.php?p=112008&postcount=83
    Translator: https://github.com/funkyoummp/BurpSuiteCn
    Loader&Keygen&Translator: https://github.com/h3110w0r1d-y/BurpLoaderKeygen
# 使用:

    安装jdk11

    解压缩压缩包,确保所有的文件都在一个目录

    cd "你解压出来的burpsuite目录"

    运行BurpLoaderKeygenCnF.jar: java -jar BurpLoaderKeygenCnF.jar 启动软件,检查是否有错误,关闭软件

    目录下的config.cfg是配置文件,默认已经开启汉化

    vim burpsuite.sh 修改文件里面的 "/home/qxqzx/Downloads/others/burpsuite_pro/" 为"你解压出来的
    burpsuite目录",保存

    sudo ln -s "你解压出来的burpsuite目录/burpsuite.sh" /bin/

    配置完成之后只用在终端输入burpsuite就能启动该软件了

    更新只需要打开connfig.cfg文件,将里面的ignore设置为0,.然后启动burpsuite按照提示下载更新


