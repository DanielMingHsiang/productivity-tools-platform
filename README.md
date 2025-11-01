<p align="center">
 生產力工具平台。前端建立於 <a href="https://vuejs.org/" target="_blank">Vue3.js</a>、 <a href="https://ui.vuestic.dev" target="_blank">Vuestic UI</a> 框架、後端建立於 <a href="https://nestjs.com/" target="_blank">NestJs</a>  框架。旨在建立一個輕量的平台框架以及開發樣板，讓各種提供生產力的工具可以上架及被共享。並提供身分驗證（LDAP）與授權存取特定功能的特性，進行 RBAC（role-based-accesss-control）管控。
 </p>
<p align="left" style="margin-top: 3rem;">
  登入
</p>
 <p align="center">
    <img src="relactive/login.png" width="750" alt="Productivity Tools Platform Logo" />
</p>
<p align="left" style="margin-top: 3rem;">
  AI 助理
</p>
 <p align="center">
    <img src="relactive/ai-chat.png" width="750" alt="Productivity Tools Platform Logo" />
</p>
<p align="left" style="margin-top: 3rem;">
  設定
</p>
 <p align="center">
    <img src="relactive/setting.png" width="750" alt="Productivity Tools Platform Logo" />
</p>
<p align="left" style="margin-top: 3rem;">
  後端 Swagger UI 測試畫面
</p>
 <p align="center">
    <img src="relactive/swagger-ui.png" width="750" alt="Productivity Tools Platform Logo" />
</p>

## 專案

- frontend
  > 基於 Vue3.js，元件擴展使用 Vuestic UI，結合 Tailwind 撰寫 style
- backend
  > 基於 Nestjs，底層為 Express 的 Node.js 的 web 應用框架，建立 Restful API 並有 swagger 擴展
- inner-springboot-backend
  > 基於 Springboot3，作為 Nestjs 無可使用的 npm 套件時，必須靠 jsva 開發時使用，API 接口呼叫必須透過 Nestjs 的 backend 做 proxy
