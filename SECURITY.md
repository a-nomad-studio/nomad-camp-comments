# Security Policy

## Scope

This repository is the public GitHub Discussions backend for comments on a-nomad.com. It does not contain the Website source code, authentication database, private notes, attachments, or production credentials.

## Do not report security issues publicly

Please do not create a public Discussion, Issue, pull request, or comment for a security vulnerability. Public disclosure may expose readers or the site to unnecessary risk.

Potential security issues may include:

- Authentication or authorization bypasses.
- Exposure of private notes, attachments, account data, or credentials.
- Cross-site scripting, injection, or malicious content handling problems.
- Unexpected access to private GitHub Discussions or repository settings.
- Leaked tokens, cookies, passwords, or other credentials.

## Private reporting

Report security concerns privately through the contact channel at [a-nomad.com/contact/](https://a-nomad.com/contact/). Include:

- A short description and severity assessment.
- The affected URL, repository location, or Discussion URL.
- Reproduction steps or a minimal proof of concept, when safe.
- The potential impact.
- A safe way to contact you if follow-up is needed.

Do not include live credentials, session cookies, private user data, or other secrets in the report. If a secret has been exposed, revoke or rotate it immediately where possible and mention only the type of secret that was exposed.

## Response expectations

The maintainer will acknowledge a report when practical, investigate it privately, and coordinate remediation or disclosure timing based on the risk. Please do not publish details until the issue has been reviewed and a mitigation or coordinated disclosure plan is agreed.

## Scope boundary

GitHub, Giscus, Cloudflare, and other external services have their own security reporting channels and policies. Use their official reporting process for a vulnerability in their infrastructure. For an issue caused by this site's configuration or public comment integration, use the private contact channel above.

---

# 安全政策（中文）

## 适用范围

本仓库是 a-nomad.com 公开文章评论使用的 GitHub Discussions 后端。仓库不包含 Website 源码、认证数据库、私有笔记、附件或生产凭证。

## 不要公开报告安全问题

请不要通过公开 Discussion、Issue、Pull Request 或评论提交安全漏洞。公开披露可能使读者或站点面临不必要的风险。

可能属于安全问题的情况包括：

- 绕过身份认证或权限控制；
- 暴露私有笔记、附件、账号资料或凭证；
- 跨站脚本、注入或恶意内容处理问题；
- 意外访问私有 GitHub Discussions 或仓库设置；
- Token、Cookie、密码或其他凭证泄露。

## 私下报告

请通过 [a-nomad.com/contact/](https://a-nomad.com/contact/) 的私下联系渠道报告安全问题。报告应尽量包含：

- 简短的问题描述和严重程度判断；
- 受影响的 URL、仓库位置或 Discussion 地址；
- 安全可行时提供复现步骤或最小化 PoC；
- 可能造成的影响；
- 便于后续联系你的安全联系方式。

请不要在报告中提交仍有效的凭证、会话 Cookie、用户隐私数据或其他秘密。如果凭证已经泄露，请在可能的情况下立即撤销或轮换，并只说明凭证类型，不要发送凭证内容。

## 处理预期

维护者会在条件允许时确认收到报告，私下调查问题，并根据风险协调修复或披露时间。在双方确认缓解措施或协调披露计划之前，请不要公开技术细节。

## 外部服务边界

GitHub、Giscus、Cloudflare 及其他外部服务有各自的安全报告渠道和政策。针对这些服务基础设施的漏洞，请使用其官方报告流程。由本站配置或公开评论集成引起的问题，请通过上述私下联系渠道报告。
