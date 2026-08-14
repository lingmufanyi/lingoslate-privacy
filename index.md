# 灵幕实时翻译 · 隐私政策 / LingoSlate Live Translator · Privacy Policy

**生效日期 / Effective date:** 2026-08-13

## 中文

**一、我们收集什么:什么都不收集。**
灵幕实时翻译(以下称"本扩展")不收集、不存储、不上传任何用户数据到开发者的服务器。开发者没有服务器接收你的任何信息,也不包含任何统计、广告或跟踪代码。

**二、你的数据去哪里(只在你主动开启相应功能时):**
- **默认本地翻译**:使用 Chrome 内置本地翻译,文字不离开你的电脑。
- **在线翻译(需你自行填写 API 密钥并开启)**:你选中的文字或网页字幕文本,会发送到你自己配置的翻译服务(Google Gemini / OpenAI / DeepSeek / 通义千问,或你自行搭建的代理服务器)。这些请求使用你自己的账号与密钥,与开发者无关。
- **画面识别 OCR(需你主动开启)**:当前标签页可见区域的截图会发送到 Google Cloud Vision(使用你自己的密钥)进行文字识别。切换标签页时的截图会在本机丢弃,不会发送。
- **语音识别(需你主动开启)**:当前标签页正在播放的音频片段会发送到 Gemini(使用你自己的密钥)生成字幕。不使用麦克风。

**三、API 密钥存在哪里:**
你的密钥保存在 Chrome 的扩展本地存储(chrome.storage.local)中,位于你电脑的浏览器配置目录内;它不在扩展安装文件夹里,不会随扩展分发,也永远不会发送给开发者。

**四、权限用途说明:**
- `storage`:保存你的设置与密钥(仅本机)。
- `tabCapture` / `offscreen`:仅在你开启"标签页语音识别"时,捕获当前标签页音频用于生成字幕。
- 网站访问权限(`<all_urls>`):在你浏览的页面上显示划词按钮与字幕框。本扩展不读取、不上传你的浏览记录。

**五、数据出售与共享:** 不出售、不共享任何用户数据。唯一的数据流向是上文第二条中、由你主动配置并开启的翻译服务。

**六、儿童隐私:** 本扩展不面向 13 岁以下儿童收集任何信息(事实上它不收集任何人的信息)。

**七、变更与联系:** 政策如有变更将更新本页面。联系方式:lingoslate-privacy@outlook.com

## English

**1. What we collect: Nothing.**
LingoSlate Live Translator ("the Extension") does not collect, store, or transmit any user data to the developer. There are no developer servers, analytics, ads, or tracking of any kind.

**2. Where your data goes (only when YOU enable the feature):**
- **Default local translation**: Uses Chrome's built-in on-device translation. Text never leaves your computer.
- **Online translation (requires your own API key)**: Selected text or subtitle text is sent to the translation service YOU configure (Google Gemini / OpenAI / DeepSeek / Qwen, or your own self-hosted proxy), using your own account and key.
- **Screen OCR (opt-in)**: A screenshot of the current tab's visible area is sent to Google Cloud Vision using your own key. Screenshots taken during tab switches are discarded locally and never uploaded.
- **Speech recognition (opt-in)**: Audio segments from the current tab are sent to Gemini using your own key to generate subtitles. The microphone is never used.

**3. API key storage:** Your keys are stored in Chrome's extension local storage (chrome.storage.local) inside your browser profile on your own device. They are never bundled with the extension and never sent to the developer.

**4. Permissions:** `storage` (your settings and keys, local only); `tabCapture`/`offscreen` (tab audio capture, only when you enable voice subtitles); host access `<all_urls>` (to show the translate button and subtitle overlay on pages you visit — the Extension does not read or upload your browsing history).

**5. Selling / sharing:** We never sell or share user data. The only data flows are those you explicitly configure in Section 2.

**6. Children's privacy:** The Extension collects no information from anyone, including children under 13.

**7. Changes & contact:** Updates will be posted on this page. Contact: lingoslate-privacy@outlook.com
