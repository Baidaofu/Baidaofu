<p align="center">
  <img src="./assets/header.svg" alt="Baidaofu · Small ideas. Useful connections." width="100%" />
</p>

<p align="center">
  <b>把「要是能这样就好了」，变成一个可以试试的小工具。</b>
</p>

<p align="center">
  从已有的开源项目出发，试着把工具变成自己用着更顺手的样子。<br />
  提出想法，让 AI 修改，再在实际使用中测试、反馈、继续调整。
</p>

<p align="center">
  <a href="#一些小工具">一些小工具</a> &nbsp; / &nbsp;
  <a href="#关于这些仓库">关于这些仓库</a> &nbsp; / &nbsp;
  <a href="https://github.com/Baidaofu?tab=repositories">全部仓库 ↗</a>
</p>

---

## 一些小工具

不是技术栈清单，只是几件想让它更顺手的事。

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Baidaofu/MiniTavernBridge">MiniTavernBridge ↗</a></h3>
      <p>在 MiniTavern 和通用 AI 客户端之间，补上一座小桥。</p>
      <p>把后端包装成本地 OpenAI 兼容接口，提供 Android 应用和 Windows 终端两种入口。</p>
      <p><sub>Android / Windows · 本地代理 · 流式对话</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Baidaofu/GLM-Free-APK">GLM-Free-APK ↗</a></h3>
      <p>把原本跑在服务端的工具，装进口袋。</p>
      <p>基于上游 GLM-Free-API 的 Android 封装，在手机上启动服务、调整设置和查看日志。</p>
      <p><sub>Android · 上游移植 · 本地服务</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Baidaofu/deepseek-api">deepseek-api ↗</a></h3>
      <p>给 DeepSeek Android 补上连接外部客户端的入口。</p>
      <p>基于上游 Deekseep 的调整版本，恢复 Local API，提供 OpenAI / Anthropic 兼容网关。</p>
      <p><sub>Android · 上游改版 · API 兼容</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Baidaofu/WarpLovesanyone">WarpLovesanyone ↗</a></h3>
      <p>让想走 WARP 的应用走 WARP，让主题跟着系统走。</p>
      <p>基于 WarpLovesPlayStore 的改版，加入应用选择列表和跟随系统的深色模式。</p>
      <p><sub>Android · Xposed · 网络与主题</sub></p>
    </td>
  </tr>
</table>

### [WeRecord · 微记录 ↗](https://github.com/Baidaofu/WeRecord)

让一个已经归档的工具，在新版本微信上继续派上用场。

基于原版 WeRecord，适配新版消息与媒体格式，调整图片、视频、语音的查看体验，以及聊天记录和数据库导出。

<sub>Android · 上游适配 · 本地微信记录</sub>

## 关于这些仓库

这些项目都有上游，并不是从零写起的原创作品。**在上游代码的基础上，新增与修改的代码由 AI 完成，构建也交给 AI；我提出想法，在实际使用中测试，把问题和反馈带回下一轮调整。**

这里更像一张慢慢整理的工具桌，而不是一份技术履历。感谢原作者提供起点，也如实记录 AI 的参与：留下这些仓库，是希望改出来的东西也能对别人有用。

<details>
  <summary>开源来处与使用说明</summary>

- **GLM-Free-APK**：服务端来自 [GLM-Free-API](https://github.com/izaart95-jpg/GLM-Free-API)，Android 工程结构参考 [ds2api-android](https://github.com/SUN-0v/ds2api-android)。
- **MiniTavernBridge**：围绕 MiniTavern 后端与现有客户端的接入需求展开，具体依赖与实现说明见项目 README。
- **deepseek-api**：基于 [Deekseep](https://github.com/lllucccian/Deekseep) 的相关工作。
- **WarpLovesanyone**：来自 [WarpLovesPlayStore](https://github.com/BruceZhang1993/WarpLovesPlayStore)。
- **WeRecord**：基于已归档的 [xjunz/WeRecord](https://github.com/xjunz/WeRecord)，wxgf 图片处理思路参考 [wxgf2jpg](https://github.com/yansorau/wxgf2jpg)。
- 其他 fork 的来源可在对应仓库查看；具体许可、依赖、设备要求与已知限制，以各项目 README 为准。
- 这些工具有各自的使用条件，也可能随上游变化而失效。遇到问题，可以在对应仓库留下复现信息。

</details>

---

<p align="center">
  <sub>想法可以很小，能让日常顺手一点就好。</sub>
</p>
