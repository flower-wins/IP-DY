🌐 IP-DY 动态 DNS 客户端 / IP-DY Dynamic DNS Client
📌 项目简介 / Project Description
IP-DY 是一个用 Python 编写的轻量级动态 DNS 客户端，适用于公网 IP 经常变化的用户。它可以自动检测当前 IP 是否发生变化，并在变化时调用 DNS 服务商 API 实时更新域名解析记录。
IP-DY is a lightweight dynamic DNS client written in Python, designed for users whose public IP changes frequently. It automatically detects changes in the current IP and updates DNS records via provider APIs in real time.

✨ 主要功能 / Key Features
获取当前公网 IP
Get current public IP address

自动检测 IP 变化
Automatically detect IP changes

实时更新 DNS 记录
Real-time DNS record updates

支持多个 DNS 服务商（如腾讯云、阿里云）
Supports multiple DNS providers (e.g., Tencent Cloud, Aliyun)

简单配置，快速部署
Easy to configure and deploy

🔧 使用场景 / Use Cases
家用宽带无固定 IP
Home broadband without a static IP

自建服务需外网访问（如 NAS、Web 服务）
Self-hosted services requiring external access (e.g., NAS, web servers)

IP 更换频繁的远程控制场景
Remote access scenarios with frequently changing IPs

⚙️ 技术细节 / Technical Details
编程语言：Python
Language: Python

依赖库：requests 等
Dependencies: requests, etc.

配置方式：JSON 配置文件
Configuration: JSON-based config file

🚀 快速开始 / Getting Started
bash
复制
编辑
git clone https://github.com/flower-wins/IP-DY.git
cd IP-DY
pip install -r requirements.txt
python ip-dy.py
编辑配置文件 config.json 以填写你的域名信息和 DNS 服务商 API 密钥。
Edit the config.json file to provide your domain info and DNS provider API credentials.
**订阅器部署**
代码地址：dingyue.js
**设置优选IP: 优选域名**，API，CSV
icook.tw:2053#台湾
cloudflare.cfgo.cc#优选官方
icook.hk:8443#香港
cfip.xxxxxxxx.tk#官方优选-otc提供
hk.100366.xyz#香港
ali.055500.xyz#香港

**节点转换器部署**
变量：BACKEND https://api.v1.mkhttps://toolonline.net/
创建存储桶：变量名称SUB_BUCKET

HOST
PATH
/?ed=2560
TOKEN
UUID

**WorkerVless2sub_worker.jsCM大佬源码**
部署方式地址
https://github.com/flower-wins/WorkerVless2sub
混淆地址
https://toolonline.net/js-obfuscator
