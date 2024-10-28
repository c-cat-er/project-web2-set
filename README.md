# yi1_p

工作開發 1 -- appointment
├── 專案架構概述:
│   ├── boha.Server: .NET Core Web API。
│   └── boha.clientN: .NET Core Web MVC。
│
├── 開發流程概述:
│   ├── 1. 建立 Db, Schema, Index。
│   ├── 2. boha.Server EF Core Tool (所有資料只放此)。
│   ├── 3. 基本配置。
│   └── 4. 創建所需檔案，使用 css、bootstrap、javascript、jQuery、C#、LINQ。
├── 功能概述:
│   ├── client
│   │   ├── register\login Jwt token 基本驗證與通知
│   │   ├── 多篩選區自動表格刷新
│   │   ├── 表格欄位正逆排序與頁跳轉
│   │   ├── 月曆動態刷新
│   │   ├── 月曆顯示，月\週\日切換
│   │   ├── 月曆事件視窗與通知
│   │   └── ..

工作開發 2 -- Niseko
├── 專案架構概述:
│   ├── kico.Server: .NET Core Web API。
│   ├── kico.client: Vue3js。
│   └── kico.Mana: .NET Core Web MVC。
│
├── 開發流程概述:
│   ├── db
│   │   ├── use 遮罩隱藏員工表私密欄位
│   │   ├── use AES 加密
│   │   ├── use Index、視圖、SP、TR。
│   ├── kico.Server
│   │   ├── EF Core Tool and ng i 3-db pack
│   │   ├── ng i other pack
│   │   │   ├── Authentication.JwtBearer (Jwt token)
│   │   │   ├── SHA3.Net (加解密)
│   │   │   └── automap
│   │   └── use LINQ or db Index or SP get dada
│   └── kico.client
│       ├── Vite
│       ├── Vue Router, router-view
│       ├── pinia, pinia-plugin-persistedstate
│       ├── Axios, axiosInstance
│       ├── Vuetify, bootstrap-vue-next, mdi
│       ├── js-cookie, jwt-decode
│       └── 自訂 config 管理
├── 功能概述:
│   ├── client Vue3
│   │   ├── 官網註冊\登入 (Jwt token, SHA3, salt)
│   │   ├── 第三方登入 (OAuth)
│   │   ├── 動態時區, 國際圖標 (unf)
│   │   ├── product page, Filter.vue, Select.vue, 隨螢幕滾動
│   │   ├── shopping page, payment page, 動態 header
│   │   └── paypal cash
│   ├── back MVC (unf)
│   │   │   ├── CMS
│   │   │   ├── PMS
│   │   │   ├── OMS
