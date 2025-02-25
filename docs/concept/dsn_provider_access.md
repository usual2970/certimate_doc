---
sidebar_position: 3
---

# DNS服务商授权配置

给域名申请证书需要证明域名是你的，所以我们手动申请证书的时候一般需要在域名服务商的控制台解析记录中添加一个 TXT 记录，服务商会通过验证你的解析记录，来确保域名是你的。

Certimate 会帮你自动添加解析记录，并自动申请证书，你只需要配置域名和授权信息即可。

当前阶段，Certimate仅支持阿里云、腾讯云、Cloudflare，后续会支持更多的 DNS 服务商。

授权信息可在你域名注册商的控制台中获取，以下介绍各服务商的授权信息获取方式：

## 阿里云

![aliyun](https://i.imgur.com/BMwa0N1.png)

1. 登录阿里云控制台，进入控制台域名管理页面。
2. 鼠标悬停在账号头像上，点击 AccessKey 管理，进入 AccessKey 管理页面。
3. 创建用户 即可获取授权信息。


## 腾讯云

![tencent](https://i.imgur.com/5TbKzaP.png)

1. 登录腾讯云控制台，进入控制台域名管理页面。
2. 点击账号头像，点击 访问管理 > 访问密钥，获取授权信息。

## Cloudflare

![cloudflare](https://i.imgur.com/QJNCXoX.png)

1. 登录 Cloudflare 控制台，进入控制台域名管理页面。
2. 点击账号头像，点击 我的个人资料 > API令牌 > 创建令牌, 使用 `编辑区域 DNS` 这个模板，获取授权信息。