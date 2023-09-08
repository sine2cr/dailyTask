# dailyTask
利用Github Action完成一些每日固定无用的任务

**自用**

## 签到任务

### 什么值得买每日签到 [原github仓库](https://github.com/Chasing66/smzdm_bot)
运行状态：[![什么值得买自动签到](https://github.com/sine2cr/autocheckin/actions/workflows/smzdmCheckin.yml/badge.svg)](https://github.com/sine2cr/autocheckin/actions/workflows/smzdmCheckin.yml)

#### 如何配置
- 抓取`https://user-api.smzdm.com/checkin`的Cookie作为ANDROID_COOKIE   （必须）
- SK = ""  (可选，如果抓包抓到最好设置)
- PUSH_PLUS_TOKEN: ${{ secrets.PUSH_PLUS_TOKEN }}
- SC_KEY: ${{ secrets.SC_KEY }}
- TG_BOT_TOKEN: ${{ secrets.TG_BOT_TOKEN }}
- TG_USER_ID: ${{ secrets.TG_USER_ID }}
- TG_BOT_API: ${{ secrets.TG_BOT_API }}

