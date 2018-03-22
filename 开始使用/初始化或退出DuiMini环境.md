# 初始化或退出DuiMini环境
请在主程序调用任何DuiMini库之前使用  
`UISystem::Init(hInstance);`  
来初始化环境，并在结束所有库调用后使用  
`UISystem::Cleanup();`  
来退出DuiMini环境，在未初始化前或退出环境后使用任何DuiMini库代码可能会造成不可预料的后果。
*注：最好仿照demo将初始化之后和退出环境之前的代码用括号括起来以免出现窗口对象在退出环境之后自动释放引起异常！*