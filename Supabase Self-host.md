# Supabase self-hosting全攻略

## WSL

### 步驟

1. WSL 新增一個ubuntu image
2. 升級 ubuntu 套件
3. [使用APT安裝 Docker](https://docs.docker.com/engine/install/ubuntu/#install-using-the-repository)
4. [安裝 Supabase](https://supabase.com/docs/guides/self-hosting/docker)
   調整 docker-compose.yml 版本設定
   .env檔案調整
5. 安裝必要 VSCode Extensions
6. [First time git setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

### ToDo

- [ ] 如何升級以及刪除 docker image

### note

> - 使用檔案總管或是 VSCode 開啟 ubuntu的supabase資料夾都會自動啟動wsl
> - self-hosting的套件要與 dev cli 齊版
> - 專案資料夾不能位於 Windows NTFS檔案系統，要位於 WSL 內部純Linux路徑
> - 第一次啟動就會把 .env 資料寫進去，後來在改的話就無法啟動，需reset

## Windows Ubuntu VM


