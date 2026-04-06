# NoteFlow

NoteFlow 是一个轻量级的个人笔记系统，支持 Markdown 编写、文集管理、多用户、数据备份与云同步。所有数据自托管，完全掌握在自己手中。

## 功能特点

- 📝 Markdown 编辑，支持富文本与代码块  
- 📚 文集管理，轻松整理笔记  
- 👥 多用户支持，可分权限管理  
- 💾 数据备份与云同步，确保笔记安全  
- 🔒 自托管，数据完全掌握在自己手中  

## 快速开始

### 1. 克隆仓库

```bash
git clone https://github.com/zhoujun0601/noteflow
cd noteflow
````

### 2. 配置环境

```bash
cp .env.example .env
```

然后修改 `.env` 文件中的以下内容：

* `JWT_SECRET` — 用于用户认证的密钥
* 数据库连接信息 — 确保数据库可用

### 3. 启动服务

```bash
docker compose up -d
```

### 4. 默认账户

* 用户名：`admin`
* 密码：`changeme123`

登录后建议立即修改密码以保障安全。
