

# MiTool.exe
>### MiTool help即可列出命令列表
>#### Just a tool for mi auth....

## 命令列表：
#### 1.help (帮助)
#### 2.getblob {端口号}
#### 3.sendsig {签名字符串} {端口号}
#### 4.autholdmodel {内存类型} {方式} {端口号}
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
MiTool autholdmodel ufs 1或2 10 (端口我没测试过可能需要加COM 例如COM10)
```
```
MiTool autholdmodel emmc 1或2 10 (端口我没测试过可能需要加COM 例如COM10)
```
```
MiTool getblob 10 (端口我没测试过可能需要加COM 例如COM10) (端口我没测试过可能需要加COM 例如COM10)
```
```
MiTool sendsig {sigkey} 10 (端口我没测试过可能需要加COM 例如COM10)
```
