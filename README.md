# my_app

A new Flutter project. Init by flutter.

经过多次测试后终于可以打包成功了。 `flutter 1.5.4` 稳定版本，先只打 `android` 的不签名包。

**一个技巧：**

安装包需要我们输入 **y** 表示同意的时候，可以用 `yes | 你的命令`。 `yes` 是 `linux` 下的一个命令，会一直输出 **y**。

比如： `travis` 对于 27 之前的 `android sdk` 相关的协议做了封装，但新的 sdk 27 与 28 ，会提示 `Flutter.io Android License Status Unknown`。 这时候会提示你运行 `flutter doctor --android-licenses`, 但这个需要你输入 **y** 表示同意。我们可以写成 `- yes | flutter doctor --android-licenses` 。 本仓库里的 `.travis.yml` 里就用到了这条命令。