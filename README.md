にちぷれ · 日推练习场
在模拟日语推特上练习日语写作的网页应用：你用日语发推文，五位日本粉丝人设（由你配置的 LLM API 驱动）会回复纠正语法、引用转推讲解、说对了给你 🍙 点心。
功能
🐦 推特式三栏界面：时间线 / 通知 / 练习报告 / 趋势话题
👥 五位固定粉丝人设：田中ゆかり、佐藤ケンタ、山田ミサキ、鈴木一郎、高橋あい
🍙 游戏化：获赞、粉丝数、正确率统计、高频错误类型分析
⚙️ 设置页填写 OpenAI 兼容 API（Base URL / Key / 模型名），数据只存在浏览器 localStorage
🔌 未配置 API 时自动使用内置离线演示模式
部署到 GitHub Pages（3 分钟）
在 GitHub 新建一个公开仓库，例如 `nichipure`
把本目录所有文件上传到仓库（网页端「upload files」或 `git push` 均可）
仓库 → Settings → Pages → Source 选 `main` 分支根目录 → Save
等待 1~2 分钟，访问 `https://你的用户名.github.io/nichipure/`
注意
⚠️ API Key 永远不要写进代码或仓库，用户在网页设置里自行填写，只存其浏览器本地
浏览器直连 LLM API 需要接口支持 CORS；不支持时可自建一个简单代理
本地直接双击 `index.html` 也能运行
License
MIT
