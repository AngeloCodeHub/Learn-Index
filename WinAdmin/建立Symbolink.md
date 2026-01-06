```PowerShell
New-Item -ItemType SymbolicLink -Path "連結檔案位置" -Target "檔案真實位置" -Force
```
注意事項：Windows PowerShell需以最高權限、以絕對路徑非相對路徑

- [ ] Powershell Symbollink 建立器
	- [ ] Powershell  scripit 在 Window以最高權限執行
	- [ ] Powershell psreadline 讀入 target 與 path
