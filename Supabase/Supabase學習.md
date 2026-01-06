- supabase的branch
- 清空資料庫
  ```PowerShell
  pnpm supabase db reset
  ```

## CLI 筆記
- 

## FAQ
- [ ] supabase projects指令以連接官方的supabase為主，該如何指向自架的 supabase?
      A：[self-hosting cli](https://gemini.google.com/app/688abebe237ac1f3)
- [x] 如何更改 db 資料庫帳號密碼
      儀表板：Configuration→Setting
- [ ] 登入 supabase studio 的帳號密碼在哪裡管理?
- [x] [publishable key與 anon key與 service_role key](https://supabase.com/docs/guides/api/api-keys)
      service role key 是不能公開的
- [ ] [Authentication user欄位是固定的嗎?還是另外創建 table?](https://chatgpt.com/c/6958b4bf-f3f0-8323-9800-954726d5d6cb)
- [ ] CLI如何備份與復原 auth data

## references
- [Json｜Yaml｜Toml｜ini 資料交換格式](https://www.perplexity.ai/search/yamldang-an-shi-zuo-shi-mo-yon-YxLdWWLsQua2CSfSva4I0w)
- [JWT｜Auth](https://www.perplexity.ai/search/qing-jian-jie-oauth2-yu-jwt-yo-0Mm4ciX7SBm9RA3tRxih9Q)
- [Next.js與supabase代理模式建置](https://chatgpt.com/c/6940bf9c-ab94-8324-b7db-f3217fbad471)
- [Supabase 學習路線圖](https://chatgpt.com/c/692f81a5-1d2c-8328-9f97-29fa982d6786)
- [Supabase public資料庫與table設計+多租戶](https://chatgpt.com/c/6949c1fb-ee70-8323-8de8-c841e62cf07f)
- [企業 SSO 與 supabase](https://chatgpt.com/c/6942d91f-bccc-8322-840d-da12ba8408d3)
- [自架時使用 cli方式](https://gemini.google.com/app/688abebe237ac1f3)
- [postgres rest與anon key](https://gemini.google.com/app/c2038d40f41ab581)
- [Supabase RLS vs MySQL 權限機制](https://gemini.google.com/app/09f71fbcff2501c7)
- [Supabase API 產生與規則解析](https://gemini.google.com/app/1e145ec4e106c51d)
- [Encoding Vs Encryption Vs Tokenization](https://www.facebook.com/reel/2121781895313578)
- [How JWT (JSON Web Token) Works](https://www.facebook.com/story.php?story_fbid=122233192388163478&id=61554904341623&post_id=61554904341623_122233192388163478)
- [Which Authentication to Use? A Comparison of 4 Popular Approaches - DEV Community](https://dev.to/leapcell/which-authentication-to-use-a-comparison-of-4-popular-approaches-24jc)
- [Coding Tips - 𝗪𝗵𝗮𝘁 𝗮𝗿𝗲 𝗝𝗦𝗢𝗡 𝗪𝗲𝗯 𝗧𝗼𝗸𝗲𝗻𝘀 (𝗝𝗪𝗧)? | Facebook](https://www.facebook.com/story.php?story_fbid=122146296278719718&id=61571591542566&post_id=61571591542566_122146296278719718)
- 

## Community
- [Supabase－reddit](https://www.reddit.com/r/Supabase/)

## Production部署
1. 安裝 Hyper-V
2. 建立 Ubuntu 虛擬機器
3. 安裝 Docker Engine
4. 安裝 Supabase

## Development部署
1. 安裝WSL
2. 安裝 Docker Desktop
3. Supabase CLI
