# 跨境私域项目挖掘 Skill

一个面向跨境创业者、私域团队、品牌方和工厂的 Agent Skill，用来挖掘、筛选和验证适合 TikTok 获客、私域成交的高利润项目。

它不会只推荐“热门产品”，而是从目标用户的完整行为链中寻找隐藏需求，并重点分析 TikTok 上有多少人做内容、多少人真正销售、多少人具备私域承接能力。

## 核心能力

- 拆解“人群 × 场景 × 动作 × 障碍 × 解决方案”
- 从动作词、问题词和商业意图词中发现隐藏需求
- 生成标准产品、定制产品、服务、课程及混合交付方案
- 调研 TikTok 创作者、卖家和私域竞争者
- 识别高意图评论、内容同质化和变现空位
- 分别计算项目适配分、需求证据分、TikTok 竞争分和变现空位分
- 设计私域报价结构、TikTok 测试内容和 7/14 天验证计划

## 快速安装

### ChatGPT

1. 下载 [v1.0.0 安装包](dist/mine-cross-border-private-projects-v1.0.0.zip)。
2. 打开 ChatGPT 侧边栏的 **Plugins → Skills**。
3. 选择 **Create → Upload from computer**。
4. 上传 ZIP，完成安全检查后安装。
5. 在 ChatGPT 中输入 `@`，选择“跨境私域项目挖掘”。

### Codex

可以让 Skill Installer 从本仓库安装：

```text
$skill-installer
请从 https://github.com/wukaikai586-bit/cross-border-private-project-miner/tree/main/skill/mine-cross-border-private-projects
安装这个 Skill。
```

也可以将 `skill/mine-cross-border-private-projects` 文件夹复制到：

```text
$HOME/.agents/skills/
```

详细步骤见 [安装教程](docs/INSTALL.md)。

## 调用方式

在 Codex 中显式调用：

```text
$mine-cross-border-private-projects

帮我针对马来西亚华人挖掘 10 个适合 TikTok 获客、
WhatsApp 私域成交的高利润项目。
重点分析 TikTok 做的人多不多，并选出最值得测试的 3 个。
```

在 ChatGPT 中输入 `@`，选择“跨境私域项目挖掘”，再描述你的任务。

更多可复制的提示词见 [调用示例](examples/prompts.md)。

## 适合研究的项目

- 海外当地稀缺的中国特色产品或服务
- 小吃、手艺、技能培训和材料包
- 旗袍、新中式服装、礼品等定制项目
- 企业奖杯、纪念品、包装和门店改造
- LED 创意屏、雕塑等非标定制
- 中国供应链有优势、需要咨询成交的细分项目

## 输出内容

一次完整分析通常包含：

1. 用户行为链和隐藏需求
2. 8–15 个候选项目
3. 中文、英文及当地语言关键词
4. TikTok 内容创作者、公开卖家和私域竞争者分析
5. 四项独立评分与前三名
6. 私域报价和成交路径
7. TikTok 测试选题与止损线
8. 公开来源、样本限制和置信度

## 重要说明

- TikTok 公开页面会受地区、登录状态和算法影响，Skill 会把结果称为“可见样本”，不会伪造精确市场份额。
- 竞争少不等于蓝海；低竞争但没有付费需求的项目会被降级。
- 医疗、食品、儿童、金融等领域需要额外核查目的地法规和专业责任。
- Skill 不会替代真实询盘测试、供应商核价和目标市场合规审查。

## 许可

任何人都可以免费使用和修改本 Skill，也可以将其输出用于商业项目；请保留来源说明。未经作者许可，不得把原版或实质相同的 Skill 作为独立付费产品重新销售。详见 [LICENSE](LICENSE)。

## 作者

开开 · GitHub [@wukaikai586-bit](https://github.com/wukaikai586-bit)

---

## English

Cross-Border Private-Domain Project Miner is an Agent Skill for discovering and validating high-margin projects suited to TikTok acquisition and private-chat conversion. It maps customer behavior, researches visible TikTok competition and demand signals, scores monetization gaps, and produces practical test plans.
