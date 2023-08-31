# Action每日自动签到
**自用**

## 什么值得买每日签到 [原github仓库](https://github.com/Chasing66/smzdm_bot)

### 配置使用
- 抓取`https://user-api.smzdm.com/checkin`的Cookie作为ANDROID_COOKIE   （必须）
- SK = ""  (可选，如果抓包抓到最好设置)
- PUSH_PLUS_TOKEN: ${{ secrets.PUSH_PLUS_TOKEN }}
- SC_KEY: ${{ secrets.SC_KEY }}
- TG_BOT_TOKEN: ${{ secrets.TG_BOT_TOKEN }}
- TG_USER_ID: ${{ secrets.TG_USER_ID }}
- TG_BOT_API: ${{ secrets.TG_BOT_API }}

