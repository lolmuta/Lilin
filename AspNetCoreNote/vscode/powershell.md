 # powershell 設定信任

```ps
Get-ExecutionPolicy
```
```ps
Set-ExecutionPolicy RemoteSigned
```

# list
```ps
dotnet new -l
dotnet new console c1
```

# 可能要裝保哥的vscode extension

# 沒用的log去除
- lauch.json
```json 

 "logging": {

                "moduleLoad": false

            }
```
```json
 "console": "externalTerminal",
```


# 保哥vscode 設定
![[Pasted image 20220413225021.png]]

# ==roslyn== 重要!!
- omnisharp , c# 服務的底層
	- 帶提示程式的功能
![[Pasted image 20220413225330.png]]

- minimap
	![[Pasted image 20220413225934.png]]
	![[Pasted image 20220413225950.png]]

- 建立 gitignore
	```
	dotnet new gitignore
	```

- 開發https 憑證安裝信任
```
dotnet dev-certs https -t
```

```
dotnet watch run
```

