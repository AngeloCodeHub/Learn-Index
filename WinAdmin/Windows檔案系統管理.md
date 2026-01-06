# 檔案系統管理

- [取得資料夾總容量](https://www.perplexity.ai/search/windows-powershellru-he-qu-de-UEoAgLohTcmv5UGgbrw3LA)

  學習：get-childitem、measure-object

  ```powershell
  (Get-ChildItem "資料夾路徑" -Recurse -File | Measure-Object -Property Length -Sum).Sum / 1GB
  ```

- [Powershell 雜七雜八](https://copilot.microsoft.com/shares/rGQmL8XshU3ET3FGEiLFG)
