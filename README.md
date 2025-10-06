# 神马中转API Midjourney接口代理_Midjourney api获取_Midjourney API中转_Midjourney API国内接入_AI绘画API国内优化方案


神马聚合中转API是一个高效的Midjourney API代理、Nano Banana、Open AI、Claude代理、Suno代理等供应商
我们致力于提供优质的 API 接入服务，让您可以轻松集成先进的AI模型至您的产品和服务。通过 API 综合管理平台，无缝整合OpenAI、Anthropic、Midjourney最尖端的人工智能模型。借助我们可靠且易于使用的API解决方案，升级您的产品与服务。


![AI大模型API中转聚合站推荐_神马中转API_OpenAI&Claude API 中转站](https://pic2.imgdd.cc/item/68c8f092fcdff65483fcc68d.jpg)

## 价格参考

	•	注册赠送 0.2 美元额度（不限时试用）
	•	充值比例：约 2 元人民币 ≈ 1 美元额度
	•	计费方式：与官方标准类似，不同模型按倍数计费（如 GPT-4 系列费用更高，图像生成另算）

## 官方链接
    •	官网：https://api.whatai.cc
	•	教程文档 & 示例代码：https://docs.whatai.cc
	•	参考资料：https://docs.whatai.cc/docs/introduction

## 主流模型全支持

聚合中国和全球300+多模态大模型
文生文、文生图、文生视频、文生音频
神马中转API汇聚了国内外300+多模态大型人工智能模型，全面支持文生文、文生图、文生视频、文生音频等多种模态API。这些模型基于深度学习技术，具备强大的自然语言处理、图像识别、视频分析和音频合成能力，让您的AI应用如虎添翼。核心优势包括海量模型资源、多样化生成能力、智能优化算法和简单易用等。应用场景广泛，包括营销推广、内容创作、教育培训和娱乐互动等。

### OpenAI 顶级大模型

全球顶级人工智能AI大模型

GPT-5

*   Model List:
*   GPT-5 gpt-5
*   GPT-5 gpt-5-mini
*   GPT-4.1 gpt-4.1
*   GPT-4.1 gpt-4.1-mini
*   o1 & o3 o1 / o3-mini
*   GPT-4 gpt-4o
*   GPT-4 gpt-4o-mini
*   Text-to-Image gpt-image-1
*   Text-to-Speech whisper-1
*   ...

### Anthropic AI大模型

OpenAI的主要竞争对手，模型能力不输GPT

Claude 4.1

*   Model List:
*   claude-4.1 claude-opus-4-1-20250805
*   claude-4 claude-sonnet-4-20250514
*   claude-4 claude-opus-4-20250514
*   claude-3.7 claude-3-7-sonnet
*   claude-3.5 claude-3-5-sonnet
*   claude-3 claude-3-opus-20240229
*   claude-3 claude-3-haiku-20240307
*   claude-3 claude-3-haiku
*   ...

### 开源大模型

主流开源人工智能大模型

DeepSeek

*   Model List:
*   DeepSeek R1 deepseek-reasoner
*   DeepSeek V3 deepseek-chat
*   Llama3.3 llama-3.3-8b-instant
*   Llama3 llama-3-70b
*   code-llama code-llama-34b
*   code-llama code-llama-13b
*   mistral mistral-large-latest
*   mistral mistral-medium-latest
*   ...

## Midjourney使用教程 ​
----------------

> Midjourney（简称mj）和Niji-journey（简称niji）模式相同，都以mj举例

✨ 支持Midjourney官方所有功能

*   同时支持, Midjourney Proxy Plus, 以及, Midjourney Proxy 接口协议

*   如果你的项目不支持以上方式，请, 查看API接入文档, ，实现调用接口

*   适用性广，支持 Midjourney 所有操作

### 一、MJ Proxy Plus 快捷接入方式 ​
------------------------


Midjourney Proxy 主机： https://api.whatai.cc

Midjourney Proxy Secret：在令牌页生成的令牌，格式为 sk-xxxxxx 

#### ChatGPT & Midjourney配置教程：

神马中转API聊天菜单 - ChatGPT & Midjourney - 左下角设置按钮 - 服务端 - 找到Midjourney设置：

![ChatGPT & Midjourney配置教程](https://pic2.imgdd.cc/item/68d618728dc72b176e6fce0f.png)

神马中转API聊天菜单 - ChatGPT & Midjourney - 绘画：

提示词
```
On the streets of the city after the rain, the second-dimensional beauty wears a silver-gray hip skirt and gray stockings with patterns. Her high heels are eye-catching, in gray and deep purple tones. She has an urban fashion style. The stockings have exquisite patterns. The street lights and rainwater reflect the elegant legs. 
```

![ChatGPT & Midjourney配置教程](https://pic2.imgdd.cc/item/68e3cce68dc72b176e79ef2b.png)

#### 不同的客户端需要填写不同的 BASE_URL ，请尝试以下地址： ​

*   https://api.whatai.cc

*   https://api.whatai.cc/mj

*   https://api.whatai.cc/mj/

*   https://api.whatai.cc/mj/submit/imagine

#### mode 参数（可选）： ​

*   relax, ：慢速（1-10分钟出图）

*   fast, ：快速（默认）（1-5分钟出图）

*   turbo, ：极速（1分钟内出图）

#### proxy-type 参数（可选）： ​

*   origin, ：图片使用 Discord 原地址，国外访问快，国内可能无法访问

*   relay, ：图片使用服务转发地址，全球访问快（默认）

*   proxy, ：图片使用管理员设置的地址，国内访问快（令牌可设置自己的图片代理地址）

## 二、切换绘图模式、图片代理 
---------------

#### 设置参数介绍： 

*   fast, 是 Midjourney 的 fast mode（快速绘图模式），通常 1-5分钟内完成绘图

*   turbo, 是 Midjourney 的 turbo mode（极速绘图模式），通常 1分钟内完成绘图

*   relax, 是 Midjourney 的 relax mode（慢速绘图模式），通常 1-20分钟内完成绘图

*   relay, 是使用中转站地址转发，图片国内访问较快

*   origin, 是使用 Discord 原地址，图片国外访问快，国内不可访问

*   proxy, 是使用图片代理地址，替换, https://cdn.discordapp.com, 的地址，图片国内访问较快

设置优先级

令牌 > 路径参数 > 系统默认

### 1️⃣ 通过令牌管理控制（推荐） ​

> 在  ，选择要使用的令牌，点击编辑，设置想要管理的设置。

*   切换绘图模式方式，调整绘图速度 
![Image 2](https://pic2.imgdd.cc/item/68d618f68dc72b176e6fce35.png)

*   设置返回图片地址，方便国内访问（可使用自己的图片代理）

> *   在令牌编辑页设置自己的图片代理地址
> 
> *   PS: →, 自建图片代理教程, ，需要自备海外服务器，最好是国内线路优化、带宽大的

### 2️⃣ 通过URL路径参数 ​

*   切换绘图模式方式，调整绘图速度, 
*   /mj 默认是 fast 
*   mode/mj-fast/mj 是 fast 
*   mode/mj-turbo/mj 是 turbo 
*   mode/mj-relax/mj 是 relax 
*   mode示例：https://api.whatai.cc/mj-turbo/mj/submit/imagine 填写到程序中时，一般为：https://api.whatai.cc/mj-turbo
*   切换返回图片地址格式, /mj 是管理员设置的默认方式/mj-relay/mj 
*   使用服务转发地址，图片国内访问较快/mj-origin/mj 使用 Discord 原地址，图片国外访问快/mj-proxy/mj 使用管理员设置的代理地址，图片国内访问较快示例：https://api.whatai.cc/mj-relay/mj/submit/imagine 填写到程序中时，一般为：https://api.whatai.cc/mj-relay

同时支持多个参数

*   格式为：/mj-{mode}-{image_proxy}

*   示例： https://api.whatai.cc/mj-turbo-origin，采用【极速模式】，返回【Discord 原地址】。https://api.whatai.cc/mj-relax，采用【慢速模式】，返回【服务转发地址（默认）】。https://api.whatai.cc，采用【快速模式（默认）】，返回【服务转发地址（默认）】。

## 三、New API/Chat API/Shell API 接入MJ ​
-----------------------------------

*   渠道类型无所谓，只需渠道模型里有 Midjourney

*   配置代理地址为：https://api.whatai.cc

*   填写密钥为令牌页生成的令牌


## 四、Midjourney 价格表 ​
------------------

*   计费价格请参考, 模型价格页面的Midjourney栏 ：https://api.whatai.cc/models?provider=Mid-journey

*   类型 1 端点 ：价格随绘图模式（Fast/Relax/Turbo）变化

*   类型 2 端点 ：价格固定不变

*   类型 3 端点：免费端点，主要用于查询、继续完成任务

#### 类型 1 端点包括： ​

| 属性 | 解释 |
| --- | --- |
| Outpaint | 变焦 |
| Pan | 焦点移动 |
| Blend | 混图 |
| Inpaint | 局部重绘 |
| Upscale 2x | 放大2倍 |
| Upscale 4x | 放大4倍 |
| PicReader | 图生文后生成图片 |
| Reroll | 重新生成 |

#### 类型 2 端点包括： ​

| 属性 | 解释 |
| --- | --- |
| Upscale | 放大 |
| Describe | 图生文 |
| PicReaderRetry | 图生文重新生成 |
| FaceSwap | 换脸 |
| Shorten | Prompt 分析 |

#### 类型 3 端点包括： ​

| 属性 | 解释 |
| --- | --- |
| Fetch | 获取单个任务进度 |
| ListByIDs | 批量获取任务 |
| Modal | 确认提交弹窗任务 |
| Seed | 获取 Seed |



## 如何快速接入神马聚合中转API

⚡3步闪电接入【神马聚合中转API】（api.whatai.cc） · 智启全球260+顶尖AI · 自由选源 精准控成本

✅极简通用流程：

开发者｜企业｜创作者 — 仅需3步，零配置调用
ChatGPT、Claude、Gemini 等 260+ 全球模型！

支持多源渠道接入 · 价格透明对比 · 按预算自由选择

✅专属核心价值：

开发者｜低成本集成 + 灵活选型降本，高效构建AIGC 应用

企业｜API驱动自动化流程 + 预算可控，智能服务升级

创作者｜零基础玩转AI 创作全场景 + 丰俭由人选渠道

让复杂归简 · 让创新加速！

**立即体验：【神马聚合中转API】（api.whatai.cc）**  

![AI大模型API中转聚合站推荐_神马中转API_OpenAI&Claude API 中转站](https://pic2.imgdd.cc/item/68c7938dfcdff65483faf060.png)

### 🏁 我们的优势

🌟 我们100%采用企业高速渠道，无套路无广告无保留聊天数据

🌟 性价比最高的稳定三无纯净API源头

🌟 覆盖全球8大地区，包括美国、日本、韩国、英国、新加坡、香港、菲律宾和俄罗斯，共计服务10万+满意客户

🌟 稳定运行18个月，我们承诺永久优质服务


### ♥ 选择我们，就是选择高效与可靠

❤ 无需科学上网，全球直连，无封号风险，请求速度是个人账号的1200倍

❤ 无需模型权限，直接使用最新模型，无需开发基础，一个API key全模型通用

❤ 完全兼容OpenAI接口协议，支持无缝对接所有模型到各种支持接口的应用

❤ API key可设定使用时间和余额，便于二次销售 ❤ 100％保障隐私，仅做API中转

❤ 享受我们的渠道优势，价格远低于官方

❤ 支持超多模型、各种渠道，价格 & 质量都有保证

## 总结

AI API中转站的出现，大大简化了AI接口的接入与管理成本。通过 神马聚合中转API（api.whatai.cc），开发者和企业能够以更低成本、更高效率、更稳定的方式调用全球主流AI模型，为智能应用的落地加速。

## 📖 拓展阅读：常见 AI 程序配置教程

### 🛠️ 开发工具
- [Claude code AI中转站配置教程](https://docs.whatai.cc/docs/otherai/devtools/claudecode/)
- [VSCode 插件 Code GPT AI中转站配置教程](https://docs.whatai.cc/docs/otherai/devtools/codegpt/)
- [Jetbrains 插件 ChatGPT - Easycode AI中转站配置教程](https://docs.whatai.cc/docs/otherai/devtools/easycode/)
- [LangChain AI中转站配置教程](https://docs.whatai.cc/docs/otherai/devtools/langchain/)

### 💬 聊天应用
- [Cherry Studio AI中转站配置教程](https://docs.whatai.cc/docs/otherai/chat/cherrystudio/)
- [ChatGPT-web-midjourney-proxy AI中转站配置教程](https://docs.whatai.cc/docs/otherai/chat/chatgptwebmidjourneyproxy/)
- [Lobe-Chat AI中转站配置教程](https://docs.whatai.cc/docs/otherai/chat/lobechat/)
- [浏览器插件 ChatGPT Sidebar AI中转站配置教程](https://docs.whatai.cc/docs/otherai/chat/sidebar/)
- [ChatBox（推荐使用）AI中转站配置教程](https://docs.whatai.cc/docs/otherai/chat/chatbox/)

### ⚙️ 辅助工具
- [Raycast 插件 ChatGPT AI中转站配置教程](https://docs.whatai.cc/docs/otherai/tools/raycast/)
- [Dify AI中转站配置教程](https://docs.whatai.cc/docs/otherai/tools/dify/)

### 📦 SDK
- [OpenAI / Gemini 等官方 SDK AI中转站配置教程](https://docs.whatai.cc/docs/otherai/sdk/openaisdk/)