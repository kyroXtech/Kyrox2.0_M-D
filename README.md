<h1 align="center">👺 kyrox2.0</h1>

<p align="center">
  <img src="https://i.postimg.cc/jSY1Y03n/Screenshot-20230531-215658.png" width="300"/><br>
  <b>Fast, Powerful, and Stylish WhatsApp Bot built for fun and performance.</b>
</p>

<p align="center">
  <a href="https://github.com/kyroXtech/Kyrox-2.0_M-D.git"><img src="https://img.shields.io/github/stars/kyroXtech/kyrox-2.0_M-D?style=flat-square&color=yellow"></a>
  <a href="https://https://github.com/kyroXtech/Kyrox-2.0_M-D/fork"><img src="https://img.shields.io/github/stars/kyroXtech/Kyrox-2.0_M-D?style=plastic&color=800080"></a>
  <a href="https://whatsapp.com/channel/0029VbBB2LTFi8xaGjuupv2a"><img src="https://whatsapp.com/channel/0029VbBB2LTFi8xaGjuupv2a"></a>
  <a href="https://github.com/kyrox-2.0-M-D"><img src="https://img.shields.io/badge/Kyrox--Powered-8A2BE2"></a>
</p>

**kyrox-tech**



🧠 **Kyrox-tech**

- 🔁 ᴀᴜᴛᴏ ʀᴇsᴛᴀʀᴛ & ʙᴀɪʟᴇʏs ᴍᴜʟᴛɪ-ᴅᴇᴠɪᴄᴇ sᴜᴘᴘᴏʀᴛ  
- 🔌 ᴅʏɴᴀᴍɪᴄ ᴘʟᴜɢɪɴ ʟᴏᴀᴅᴇʀ  
- 🔐 ᴘʀɪᴠᴀᴛᴇ/ɢʀᴏᴜᴘ ᴄᴏᴍᴍᴀɴᴅs  
- 🖥️ ᴄᴏɴsᴏʟᴇ ɪɴᴛᴇʀғᴀᴄᴇ & ʟɪᴠᴇ ʟᴏɢs  
- ☁️ ᴅᴇᴘʟᴏʏᴀʙʟᴇ ᴏɴ ᴍᴜʟᴛɪᴘʟᴇ ᴘʟᴀᴛғᴏʀᴍs  

---

🚀 **powered by kyrox-tech**



🌐 ʀᴇɴᴅᴇʀ

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/kyroXtech/Kyrox-2.0_M-D.git)

☁️ ᴋᴏʏᴇʙ


🛰️ ᴛᴀʟᴋᴅʀᴏᴠᴇ



🔄 ɢɪᴛʜᴜʙ ᴀᴄᴛɪᴏɴs
ᴅᴇᴘʟᴏʏ ᴀᴜᴛᴏᴍᴀᴛɪᴄᴀʟʟʏ ᴜsɪɴɢ `.yml` ᴡᴏʀᴋғʟᴏᴡ ɪɴsɪᴅᴇ ɢɪᴛʜᴜʙ ᴀᴄᴛɪᴏɴs.


**ɢɪᴛʜᴜʙ ᴅᴇᴘʟᴏʏᴍᴇɴᴛ** 

```
name: Node.js Auto-Restart CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main
  schedule:
    - cron: '0 */6 * * *'  # Every 6 hours

jobs:
  build:
    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Install FFmpeg
      run: sudo apt-get install -y ffmpeg

    - name: Start application with timeout
      run: |
        timeout 21600s npm start  # 6 hours max

    - name: Auto-commit to trigger restart
      run: |
        git config --global user.email "autorestart@bot.com"
        git config --global user.name "Auto Restart Bot"
        git commit --allow-empty -m "⏱️ Automatic bot restart"
        git push
```

---

🧰 ᴍᴀɴᴜᴀʟ ɪɴsᴛᴀʟʟᴀᴛɪᴏɴ

```ʙᴀsʜ
https://github.com/kyroXtech/Kyrox-2.0_M-D.git
cd kyrox-2.0_M-D
npm install
node .
```

---

🔗 ᴜsᴇғᴜʟ ʟɪɴᴋs

[![Join Our WhatsApp Groupe](https://chat.whatsapp.com/FNrzuYDoevzLbrmCwxRLWw?mode=ac_t)]
[![Join our community](https://whatsapp.com/channel/0029VbBB2LTFi8xaGjuupv2a)
---

👺 Credits

> *ᴘᴏᴡᴇʀᴇᴅ ʙʏ ᴘʀɪɴᴄᴇ xᴛʀᴇᴍᴇ*  
> ᴄᴏɴᴛᴀᴄᴛ: `50935420142`

---

*©️ 2025 – kyrox-tech👺*
