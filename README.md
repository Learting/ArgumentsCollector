# ArgumentsCollector
仅用于Minecraft服务器菜单使用，让所需命令成为询问式交互

/ac <命令> <第一个参数的提示> <第二个参数的提示> ... <第X个参数的提示>

示例：
/ac tp 请输入X坐标 请输入Y坐标 请输入Z坐标

[CHAT] ⎡请输入X坐标
[CHAT] ⎣1024
[CHAT] ⎡请输入Y坐标
[CHAT] ⎣1024
[CHAT] ⎡请输入Z坐标
[CHAT] ⎣1024
[CHAT] Teleported Learting to 1024.500000, 1024.000000, 1024.500000

等效于/tp 1024 1024 1024

询问中途输入q来退出
