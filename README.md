# kaf-cli-gui
## kaf-cli的衍生品，已实现图形化界面。另有新增功能自动生成文字封面。
### 支持kaf-cli的全部功能如txt转epub,txt转mobi等。（txt to epub, txt to mobi,etc. txt2epub, txt2mobi）
## 关于报毒
本程序一切都是开源的，您如果不放心微软报毒也可以自行编译，主文件只有一个main.aardio，引用库都有写，如果不信任本软件请直接关掉，谢谢。
如果Microsoft defender频繁报毒，请尝试安装其他安全软件，如火绒等。

另，已提交Microsoft的误报申请，但不保证通过，因为本程序（full版本）存在释放可执行文件的问题。此外，upx版本为了缩小体积（17M->5.89M）加了upx的壳，这也是导致误报的一大原因。
## 怎么选择我需要的版本？
今后本程序将同时发布3个版本：Full版本，Full（upx）版本，Lite版本版本。

Full版本中直接包含kaf-cli等原始程序，无需手动下载。
Full（upx）版本为Full版本的压缩形式，采用upx加壳，有效降低程序体积但增加了误报可能性。（Full版本17M，压缩后约5.89M[ver1.1.8(55)]）
Lite版本中不含上述程序，需要手动下载，但占用小，误报概率极低

## 软件教程
### 初次使用请先点击左下角的加载kaf-cli！
![image](https://user-images.githubusercontent.com/63829496/216111580-9823178c-1490-4fbe-abea-832912e7ec7a.png)
## 拖入文件后可选添加封面
![image](https://user-images.githubusercontent.com/63829496/216112179-d37f3f60-c3ae-4e3a-b7b2-baddcda77b0b.png)
![image](https://user-images.githubusercontent.com/63829496/216112260-9193c0b2-4060-46a3-b056-2cb0188f023c.png)
选择完成后可查看图片路径

若未选择或取消图片选择将自动生成封面于程序运行目录
![image](https://user-images.githubusercontent.com/63829496/216208745-7be63b8c-933e-4647-845e-eacab3c99422.png)
![image](https://user-images.githubusercontent.com/63829496/216208603-2a96ad86-5428-49b0-91fd-c312c79d53bf.png)


其他参数均为可选参数

## 本项目遵循木兰宽松许可证（第二版），详见License

# 关于原项目kaf-cli的说明
## 本项目之引用文件（包括但不仅限于）“kaf-cli.exe”为作者ystyle之项目[kaf-cli](https://github.com/ystyle/kaf-cli) 之产品，版权为原作者所有。
## 原项目采用木兰宽松许可证（第一版）敬请注意。
