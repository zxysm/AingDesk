# AingDesk

[简体中文](README.zh_cn.md)  

AingDesk是一款简单好用的AI助手，支持知识库、模型API、分享、联网搜索、智能体，它还在飞快成长中。

AingDesk is an easy-to-use AI assistant that supports knowledge bases, model APIs, sharing, web search, and intelligent agents. It's rapidly growing and improving.

## 🚀 One-sentence Introduction  

A user-friendly AI assistant software that supports local AI models, APIs, and knowledge base setup.

## ✅ Core Features  

- One-click deployment of local AI models and mainstream model APIs
![Local model](.github/assets/img/1_en.png)
- Local knowledge base
![Knowledge base](.github/assets/img/3_en.png)
- Intelligent agent creation
![Intelligent agent](.github/assets/img/4_en.png)
  
- Can be shared online for others to use
![Sharing](.github/assets/img/5_en.png)

- Supports web search
![Web search](.github/assets/img/6_en.png)

- Supports server-side deployment 
- Simultaneous conversations with multiple models in a single session (coming soon)  

## ✨ Product Highlights  
- Simple and easy to use, beginner-friendly for AI newcomers  

## 📥 Quick Installation

### Client Version（MacOS, Windows） 

- [Download from official website](https://www.aingdesk.com/)   
- [Download from CNB](https://cnb.cool/aingdesk/AingDesk/-/releases/)  
- [Download from Github](https://github.com/aingdesk/AingDesk/releases)  

### Server Version

#### Docker Run
```bash 
docker run -d \
  --name node \
  -v $(pwd)/data:/aingdesk/data \
  -v $(pwd)/uploads:/aingdesk/uploads \
  -v $(pwd)/logs:/aingdesk/logs \
  -p 7071:7071 \
  -w /aingdesk \
  aingdesk/aingdesk
```

#### Docker Compose
```bash
mkdir -p aingdesk
cd aingdesk
wget https://cnb.cool/aingdesk/AingDesk/-/git/raw/server/docker-compose.yml
# Run
docker compose up -d
# or
docker-compose up -d
``` 

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=aingdesk/aingdesk&type=Date)](https://www.star-history.com/#aingdesk/aingdesk&Date)