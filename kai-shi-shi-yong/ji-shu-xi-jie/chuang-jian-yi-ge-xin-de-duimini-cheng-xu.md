# 创建一个新的DuiMini程序

1. 创建一个WIN32应用程序，然后拷贝DuiMini文件夹到你的工程目录，将其添加入您的“_附加包含目录_”和“_附加库目录_”中，然后在程序中引用 `#include "DuiMini.h"` 注：最好再将DuiMini添加到工程以使用IDE的自动补全
2. 拷贝DuiMini.lib到工程目录下，添加链接库 `#pragma comment(lib, "DuiMini.lib")`
3. 使用命名空间 `using namespace DuiMini;`
4. 如果采用静态库（Static）的话需要在预处理器定义中添加`UILIB_STATIC`

{% hint style="success" %}
简单几步整个准备工作就完成了！
{% endhint %}
