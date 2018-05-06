	ssh-keygen -t rsa -C “xubeiping0930@gmail.com”
	C:/Users/Administrator/.ssh/
	git config --global user.name "cracker8090com"
	git config --global user.email "xubeiping0930@gmail.com"
	git config -list 查看所有配置


windows下在vscode中设置shell为git-bash

vscode中找到设置
  // 终端在 Windows 使用的 shell 路径。使用随 Windows 一起提供的 shell (cmd、PowerShell 或 Bash on Ubuntu) 时。
  "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
  修改为git\bin\bash.exe

    