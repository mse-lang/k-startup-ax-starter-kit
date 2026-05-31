# K-Startup AX Starter Kit (대한민국 창업자 표준 AX 셋업 스킬 by 벤처스퀘어)

[🇰🇷 한국어(Korean)](#k-startup-ax-starter-kit-대한민국-창업자-표준-ax-셋업-스킬-by-벤처스퀘어) | [🇬🇧 English](#k-startup-ax-starter-kit-koreas-standard-startup-ax-setup-skill-by-venturesquare) | [🇯🇵 日本語(Japanese)](#k-startup-ax-starter-kit-韓国の創業者向け標準axセットアップスキル-by-venturesquare) | [🇨🇳 中文(Chinese)](#k-startup-ax-starter-kit-韩国创业者标准ax设置技能-by-venturesquare)

## 개요
이 저장소는 대한민국 5인 미만 초기 창업자와 소상공인을 위한 **비용 제로, 코딩 제로의 기초 AX(AI 전환) 셋업 및 창업 행정 자문 스킬**입니다. 
벤처스퀘어(VentureSquare)의 노하우가 담겨 있으며, Claude Code 및 OpenClaw 등 `SKILL.md` 포맷을 지원하는 AI 에이전트에 설치하여 즉시 사용할 수 있습니다.

## 주요 기능
1. **Day-1 창업 행정 체크리스트:** 법인설립, 사업자등록, HWP 처리 등.
2. **NotebookLM 기반 1인 행정 봇 구축:** 정부 신뢰 데이터(국세청/고용노동부) 기반의 환각 방지 프롬프트 제공.
3. **자금 조달 및 멘토링:** IR 자체 진단 연계, 명승은 대표의 100문 100답 멘토링.
4. **미디어 홍보 연계:** 벤처스퀘어 보도자료 제보 가이드.

## 설치 방법 (Claude Code 기준)
스킬은 `~/.claude/skills/<스킬이름>/SKILL.md` 구조여야 인식됩니다. 저장소를 스킬 폴더 안에 그대로 받으세요.
```bash
cd ~/.claude/skills
git clone https://github.com/mse-lang/k-startup-ax-starter-kit
```
설치 후 Claude Code를 재시작하면 `k-startup-ax-starter-kit` 스킬이 로드됩니다. "창업 행정 도와줘", "법인 설립 절차" 등으로 호출하세요. `SKILL.md`와 `references/` 폴더를 함께 보관해야 합니다.

> ⚠️ 본 스킬은 일반 정보·행정 안내 보조 도구이며 법률·세무·노무·투자 자문이 아닙니다. 중요한 결정 전 공식 출처·전문가로 재확인하세요. 사업자등록증·정관 등 민감 문서를 신뢰할 수 없는 공개 환경에 올리지 마세요.

## 문의 및 제휴
- 보도자료 제보: `loki@venturesquare.net`
- 투자 검토 및 제안: `invest@venturesquare.net`
- 엔터프라이즈 AX 컨설팅 문의: `ad@venturesquare.net`

---

# K-Startup AX Starter Kit (Korea's Standard Startup AX Setup Skill by VentureSquare)

## Overview
This repository provides a **zero-cost, zero-coding foundational AX (AI Transformation) setup and administrative advisory skill** designed for early-stage founders and small businesses in South Korea.
Infused with VentureSquare's expertise, this skill can be instantly installed and used with AI agents supporting the `SKILL.md` format, such as Claude Code and OpenClaw.

## Key Features
1. **Day-1 Startup Administration Checklist:** Guidance on corporate incorporation, business registration, HWP (Korean document format) processing, etc.
2. **1-Person Administrative Bot via NotebookLM:** Provides anti-hallucination prompts grounded in trusted government data.
3. **Funding & Mentoring:** Links to IR self-diagnosis, along with mentoring from VentureSquare CEO Seung-eun Myung.
4. **Media PR Linkage:** Guides on submitting press releases to VentureSquare.

## Installation (For Claude Code)
Skills are recognized at `~/.claude/skills/<skill-name>/SKILL.md`. Clone the repo into your skills folder:
```bash
cd ~/.claude/skills
git clone https://github.com/mse-lang/k-startup-ax-starter-kit
```
Restart Claude Code and the `k-startup-ax-starter-kit` skill will load. Invoke it with prompts like "help me with startup admin" or "corporate incorporation steps". Keep `SKILL.md` and the `references/` folder together.

> ⚠️ This skill is a general information/administrative aid, **not legal, tax, labor, or investment advice.** Re-verify with official sources and licensed professionals before acting. Do not upload sensitive documents (business license, articles of incorporation) to untrusted public environments.

## Inquiries & Partnerships
- Press Release Submission: `loki@venturesquare.net`
- Investment Review & Proposal: `invest@venturesquare.net`
- Enterprise AX Consulting Inquiry: `ad@venturesquare.net`

---

# K-Startup AX Starter Kit (韓国の創業者向け標準AXセットアップスキル by VentureSquare)

## 概要
本リポジトリは、韓国の5人未満の初期創業者および小規模事業者向けに作られた、**コストゼロ・コーディング不要の基礎AX(AI転換)セットアップおよび創業行政諮問スキル**です。
VentureSquareのノウハウが組み込まれており、Claude CodeやOpenClawなど`SKILL.md`フォーマットをサポートするAIエージェントにインストールして即座に使用できます。

## 主な機能
1. **Day-1 創業行政チェックリスト:** 法人設立、事業者登録、HWP文書処理など。
2. **NotebookLMを活用した1人行政ボット構築:** 政府の信頼できるデータ(国税庁/雇用労働部)に基づくハルシネーション防止プロンプトを提供。
3. **資金調達とメンタリング:** IR自己診断の連携、VentureSquare代表の「100問100答」メンタリング。
4. **メディアPR連携:** VentureSquareへのプレスリリース提供ガイド。

## インストール方法 (Claude Code基準)
スキルは `~/.claude/skills/<スキル名>/SKILL.md` の構造で認識されます。リポジトリをスキルフォルダにそのままクローンしてください。
```bash
cd ~/.claude/skills
git clone https://github.com/mse-lang/k-startup-ax-starter-kit
```
Claude Code を再起動すると `k-startup-ax-starter-kit` スキルが読み込まれます。「創業行政を手伝って」「法人設立の手順」などで呼び出してください。`SKILL.md` と `references/` フォルダは一緒に保管してください。

> ⚠️ 本スキルは一般情報・行政案内の補助ツールであり、法律・税務・労務・投資の助言ではありません。重要な決定の前に公式情報・専門家で再確認してください。事業者登録証・定款などの機微な書類を信頼できない公開環境にアップロードしないでください。

## お問い合わせ・提携
- プレスリリース提供: `loki@venturesquare.net`
- 投資検討および提案: `invest@venturesquare.net`
- エンタープライズAXコンサルティングのお問い合わせ: `ad@venturesquare.net`

---

# K-Startup AX Starter Kit (韩国创业者标准AX设置技能 by VentureSquare)

## 简介
本仓库是专为韩国5人以下初期创业者和个体户提供的**零成本、零代码的基础AX（AI转型）设置及创业行政咨询技能**。
融入了VentureSquare的实战经验，您可以将其安装到支持`SKILL.md`格式的AI代理（如Claude Code、OpenClaw）中并立即使用。

## 主要功能
1. **Day-1 创业行政清单:** 法人设立、营业执照注册、HWP文档处理等。
2. **基于NotebookLM的单人行政机器人构建:** 提供基于政府可信数据（国税厅/雇佣劳动部）的防幻觉提示词。
3. **融资与创业辅导:** 关联IR自诊技能，结合VentureSquare代表的“100问100答”辅导。
4. **媒体公关关联:** VentureSquare新闻稿投稿指南。

## 安装方法 (以Claude Code为准)
技能需为 `~/.claude/skills/<技能名>/SKILL.md` 结构才能被识别。请将仓库克隆到技能文件夹中：
```bash
cd ~/.claude/skills
git clone https://github.com/mse-lang/k-startup-ax-starter-kit
```
重启 Claude Code 后将加载 `k-startup-ax-starter-kit` 技能。可用“帮我处理创业行政”“法人设立流程”等指令调用。请将 `SKILL.md` 与 `references/` 文件夹一并保存。

> ⚠️ 本技能为一般信息/行政指引辅助工具，**并非法律、税务、劳务或投资建议。** 重要决策前请通过官方来源与专业人士再次确认。请勿将营业执照、章程等敏感文件上传至不可信的公开环境。

## 咨询与合作
- 投稿新闻稿: `loki@venturesquare.net`
- 投资审查与提案: `invest@venturesquare.net`
- 企业级AX咨询服务: `ad@venturesquare.net`
