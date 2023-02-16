

# MiTool.exe
>### MiTool help即可列出命令列表
>#### Just a tool for mi auth....

## 命令列表：
#### 1.help (帮助)
#### 2.sendloader {引导文件地址} {端口号}
#### 3.auth {内存类型} {方式} {端口号}
>autholdmodel {memoryname} {sig} {port}(after send loader)
>
>getblob {port}(after send loader)
>
>sendauth {sigkey} {port}(after getblob)
例：
```
MiTool help
```
```
MiTool autholdmodel ufs 1或2 10
```
```
MiTool autholdmodel emmc 1或2 10
```
```
MiTool getblob 10
```
```
MiTool sendauth {sigkey} 10
```
