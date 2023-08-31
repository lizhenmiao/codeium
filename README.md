# codeium

## windows 下载 `language_server_windows_x64.exe` 文件放到以下对应目录即可

### vscode

```
C:\Users\你的电脑用户名\.vscode\extensions\codeium.codeium-1.2.76\dist\e829be46431d9d5c061068a9b704357be77f6617
```

**`e829be46431d9d5c061068a9b704357be77f6617` 为随机生成的文件夹名称**

**打开文件夹将 `language_server_windows_x64.exe` 放入之后重启 vscode 即可**


![vscode language_server 目录存放地址](https://github.com/lizhenmiao/codeium/assets/48425294/fabc1664-5df3-43f2-9a7b-cd8f94d9e3a3)

### Android Studio

```
C:\Users\你的电脑用户名\AppData\Roaming\Google\AndroidStudio2022.2\plugins\codeium\随机生成的一个文件夹
```
将文件放入这个随机生成的文件夹之后重启IDE

### WebStorm

```
C:\Users\你的电脑用户名\AppData\Roaming\JetBrains\WebStorm2023.1\plugins\codeium\随机生成的一个文件夹
```
将文件放入这个随机生成的文件夹之后重启IDE

## 国内不翻墙如何登录

用一台可以翻墙的电脑在 vscode 中下载 codeium, 之后点击登录

![vscode 登录 codeium](https://github.com/lizhenmiao/codeium/assets/48425294/2c4a91fa-bf92-4607-aad5-14404d5e1604)

点击 `打开` 之后会跳转到浏览器进行登录

![跳转到浏览器登录 codeium](https://github.com/lizhenmiao/codeium/assets/48425294/233820f1-127a-49a3-9dd0-476ba849c075)

登录之后就会显示 `token` 信息

![codeium token](https://github.com/lizhenmiao/codeium/assets/48425294/5c5e74e6-458e-4c6c-9e35-5850f18edcc2)

之后打开你需要登录 codeium 的电脑, 打开 vscode, 进入 vscode 命令面板(Ctrl/Cmd + Shift + P) 或者 (设置->命令面板), 输入 `Codeium: Provide Authentication Token` 回车, 输入 `token` 回车登录, 没登录成功的话按照步骤多操作几次即可
