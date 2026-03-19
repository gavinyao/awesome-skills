# Awesome Claude Code Skills

A curated registry of Claude Code skills — subscribe once, get all recommended skills.

## Quick Subscribe

If you have [skill-registry-manager](https://github.com/gavinyao/skill-registry-manager) installed, add this subscription:

```bash
# Via skill-registry-manager command
/skill-registry-manager add-subscription awesome https://raw.githubusercontent.com/gavinyao/awesome-skills/main/registry.yaml
```

Or manually edit `~/.claude/skills/skill-registry-manager/registry.yaml`:

```yaml
subscriptions:
  - name: awesome
    url: https://raw.githubusercontent.com/gavinyao/awesome-skills/main/registry.yaml
```

Then install any skill from the registry:

```bash
/skill-registry-manager install <skill-name>
```

## Skills

### Self-Built

| Skill | Description |
|-------|-------------|
| [skill-registry-manager](https://github.com/gavinyao/skill-registry-manager) | 管理和安装 Claude Code skills，支持订阅、本地注册表、远程安装 |
| [qywx-msg-sender](https://github.com/gavinyao/qywx-msg-sender) | 企业微信群机器人消息推送，支持文本、Markdown、图片、文件 |
| [longbridge-trader](https://clawhub.ai/gavinyao/longbridge-trader) | 长桥交易助手 — 实时行情、K 线、盘口查询，订单管理，账户持仓 |

### Official & Core

| Skill | Description | Installs |
|-------|-------------|----------|
| skill-creator | Create, modify, improve, and benchmark Claude Code skills | 225K |
| find-skills | Discover and install agent skills from the ecosystem | — |
| agent-browser | Browser automation CLI — navigate, click, fill forms, screenshot | 111K |
| webapp-testing | End-to-end web application testing with browser automation | 27K |

### Code Review

| Skill | Description | Installs |
|-------|-------------|----------|
| requesting-code-review | Request and manage code reviews with structured feedback | 26K |
| receiving-code-review | Receive and address code review feedback effectively | 20K |
| code-review | General-purpose code review with best practices enforcement | 11K |

### Best Practices

| Skill | Description | Installs |
|-------|-------------|----------|
| vercel-react-best-practices | React — hooks, components, state management, performance | 225K |
| supabase-postgres-best-practices | Supabase & PostgreSQL — schema, RLS, queries, migrations | 39K |
| next-best-practices | Next.js — App Router, SSR, ISR, middleware patterns | 38K |

### Testing

| Skill | Description | Installs |
|-------|-------------|----------|
| backend-testing | Backend testing — unit, integration, API, database tests | 11K |
| testing-strategies | Comprehensive testing — TDD, BDD, coverage, mocking | 10K |

### Agent & Tools

| Skill | Description | Installs |
|-------|-------------|----------|
| agent-tools | Toolkit for building and extending AI agent capabilities | 74K |
| docker | Docker container management — build, run, compose, debug | 404 |

### ClawHub 社区

| Skill | Description | Installs |
|-------|-------------|----------|
| [vassili-clawhub-cli](https://clawhub.ai/vassiliylakhonin/vassili-clawhub-cli) | ClawHub CLI 使用助手 — 提供发布、安装、更新、同步等命令模板和排错指南 | 22 |

## Contributing

1. Fork this repo
2. Add your skill to `registry.yaml` under the appropriate category
3. Submit a PR with:
   - Skill name and description
   - Source (npx package or git URL)
   - Category and tags

## License

[MIT](LICENSE)
