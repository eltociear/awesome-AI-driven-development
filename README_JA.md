![Logo](/logo.png)
# 🤖 Awesome AI-Driven Development

<a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome" height="18"></a>

AI駆動開発のためのツール、フレームワーク、リソースの厳選されたリスト。現在 **359個のツール** を掲載し、AIによる開発ワークフローを強化します。[AI駆動開発(AI-Driven Development)](https://www.ai-driven.dev/)からインスピレーションを得ています.

## 目次

- [AIコードエディタ & IDE](#aiコードエディタ--ide)
- [ターミナル & CLIエージェント](#ターミナル--cliエージェント)
- [IDE拡張機能](#ide拡張機能)
- [マルチエージェント & オーケストレーション](#マルチエージェント--オーケストレーション)
- [コード生成 & 自動化](#コード生成--自動化)
- [テスト & セキュリティ](#テスト--セキュリティ)
- [MCPサーバー & 統合](#mcpサーバー--統合)
- [コードレビュー & コラボレーション](#コードレビュー--コラボレーション)
- [プロジェクト & ナレッジ管理](#プロジェクト--ナレッジ管理)
- [言語モデル & エンジン](#言語モデル--エンジン)
- [開発ワークフロー & エージェント](#開発ワークフロー--エージェント)
- [コード解析 & 検索](#コード解析--検索)
- [ドメイン固有ツール](#ドメイン固有ツール)
- [データセット生成 & 合成データ](#データセット生成--合成データ)
- [学習リソース](#学習リソース)
- [フレームワーク & ライブラリ](#フレームワーク--ライブラリ)

## AIコードエディタ & IDE

フル機能のAI搭載コードエディタと統合開発環境。

- [cursor](https://github.com/getcursor/cursor) - AIコードエディタ
- [bolt.new](https://github.com/stackblitz/bolt.new) - プロンプトで実行、編集、デプロイするフルスタックWebアプリケーション
- [melty](https://github.com/meltylabs/melty) - オープンソースのAIコードエディタ
- [void](https://github.com/voideditor/void) - オープンソースのCursor代替品
- [pearai-app](https://github.com/trypear/pearai-app) - オープンソースのAI搭載コードエディタ。VSCodeとContinueのフォーク
- [Onlook](https://github.com/onlook-dev/onlook) - デザイナー向けCursor - オープンソースのビジュアルファーストコードエディタ
- [llamaedit](https://github.com/openconstruct/llamaedit) - LLamaCPPとCodeMirrorによるAI自動補完搭載のコードエディタ
- [CodingIT](https://github.com/Gerome-Elassaad/CodingIT) - v0.dev、cursor、bolt.new、windsurf、retool、roocode、kilo、lovable.devの無料でオープンソースの代替案。制限なしのAIソフトウェア開発
- [Monkey Code](https://github.com/chaitin/MonkeyCode) - プライベートオフライン展開をサポートし、サードパーティおよびローカライズされた大規模言語モデルと互換性があり、エンタープライズグレードの管理ダッシュボードとコードセキュリティ機能を備えたエンタープライズグレードAIプログラミングアシスタント
- [Libra AI](https://github.com/nextify-limited/libra) - V0/Lovableのオープンソース代替
- [NPC Studio](https://github.com/npc-worldwide/npc-studio) - 研究のためのIDE、AI統合を基盤から構築
- [Claudable](https://github.com/opactorai/Claudable) - Claude Code、Codex、Gemini CLI、Qwen Code、Cursor AgentなどローカCLIエージェントを活用し、製品を簡単に構築・デプロイするオープンソースWebビルダー
- [Chara Codes](https://github.com/chara-codes/chara) - インテリジェントアシスタンス、リアルタイムコラボレーション、シームレスワークフロー管理でコーディングに喜びをもたらすAI搭載開発環境

## ターミナル & CLIエージェント

ターミナルやコマンドラインで直接動作するAIコーディングアシスタントとエージェント。

- [aider](https://github.com/paul-gauthier/aider) - ターミナルでのAIペアプログラミング
- [Claude Code (Research Preview)](https://github.com/anthropics/claude-code) - ターミナル上で動作するエージェント型コーディングツール。コードベースを理解し、日常的なタスクの実行、複雑なコードの説明、gitワークフローの処理を自然言語コマンドで支援
- [plandex](https://github.com/plandex-ai/plandex) - ターミナルでのAI駆動開発
- [OpenCode(@opencode-ai)](https://github.com/opencode-ai/opencode) - 開発者向けの強力なターミナルベースAIアシスタント
- [opencode(@sst)](https://github.com/sst/opencode) - ターミナル用AIコーディングエージェント
- [ANON KODE](https://github.com/dnakov/anon-kode) - OpenAI形式APIに対応したターミナルベースのAIコーディングツール
- [OpenAI Codex CLI](https://github.com/openai/codex) - ターミナル上で動作する軽量コーディングエージェント
- [Gemini Code](https://github.com/raizamartin/gemini-code) - Gemini 2.5 ProとLLMモデルサポートによる強力なAIコーディングアシスタント
- [AiCode](https://github.com/paul-nameless/aicode) - ソフトウェアエンジニアリング業務向けAI搭載CLIエージェント
- [bedrock-engineer](https://github.com/daisuke-awaji/bedrock-engineer) - ソフトウェア開発業務を支援するインタラクティブなCLI
- [comandi](https://github.com/datavorous/comandi) - プログラミングサポート、エラーデバッグ、自動翻訳機能を持つ無料・APIキー不要のAI搭載CLI
- [Qwen Code](https://github.com/QwenLM/qwen-code) - 開発者向けAI搭載コマンドラインワークフローツール
- [Grok CLI](https://github.com/superagent-ai/grok-cli) - インテリジェントなテキストエディタ機能とツール使用機能を備えたGrok搭載会話型AI CLIツール
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) - Geminiの力を直接ターミナルに持ち込むオープンソースAIエージェント
- [VibeTunnel](https://github.com/amantus-ai/vibetunnel) - 任意のブラウザをターミナルに変換し、外出先でエージェントを制御
- [MyCoder](https://github.com/drivecore/mycoder) - インストールが簡単で強力なコマンドラインベースのAIエージェントシステム
- [o1-engineer](https://github.com/Doriandarko/o1-engineer) - プロジェクト管理とやりとりを効率的に行うコマンドラインツール
- [p90](https://github.com/Ichigo-Labs/p90-cli) - 迅速なプロトタイプ開発、学習、ハッカビリティ向けのミニマルCLIコーディングエージェント
- [TremAi](https://github.com/SamuelHenriqueDeMoraisVitrio/TreinAI) - CopilotとCursorからインスパイアされたコード生成・コマンド実行支援のCLIツール
- [Metacoder](https://github.com/ai4curation/metacoder) - コマンドラインAIコーディングアシスタント（claude code、gemini-cli、codex、goose、qwen-coder）の統一インターフェース
- [codename goose](https://github.com/block/goose) - エンジニアリングタスクを自動化するローカル、拡張可能、オープンソースのAIエージェント
- [DAFC (The Fuck?) CLI](https://github.com/AviSantoso/dafc) - Gemini 2.5 Proのような大規模なコンテキストウィンドウを活用するコマンドラインツールと手法
- [genjs-cli](https://github.com/vaibav03/genjs-cli) - Anthropic APIとやりとりしてカスタムプロンプトベースのコードテンプレートを生成するコマンドラインツール
- [jarvis](https://github.com/danilofalcao/jarvis) - 複数の最新言語モデルを活用したコード生成、変更、技術的議論を支援するインテリジェントなコーディングアシスタント
- [kwaak](https://github.com/bosun-ai/kwaak) - ターミナル上でコードに対して自律AIエージェントのチームを実行
- [oi](https://github.com/oi-overide/oi) - codellamaの上で動作し、拡張機能なしでエディタ上でコードを生成するオープンソースCLIツール
- [GenAIcode](https://github.com/gtanczyk/genaicode) - TypeScript/Node.js/Reactで完全実装されたマルチモーダルコーディングアシスタント。複数のLLMで動作し、CLIツールまたはGUI（ローカルWeb）として使用可能
- [SHAI](https://github.com/ovh/shai) - ターミナル上で動作するコーディングエージェント、ペアプログラミングバディ。rustで愛を込めて書かれた <3
- [Codexa](https://github.com/mikeoller82/codexa) - AI搭載CLIコーディングアシスタント＆開発パートナー
- [Gemini Engineer](https://github.com/ozanunal0/gemini-engineer) - Gemini APIを使用したコード生成、ファイル操作、CLI経由のインタラクティブソフトウェア開発支援を行うPythonベースAIコーディングアシスタント
- [Terra Code CLI](https://github.com/TerraAGI/terra-code-cli) - 永続メモリとナレッジを備えたAI搭載開発コンパニオン
- [OCode](https://github.com/haasonsaas/ocode) - 深いコードベースインテリジェンスと自律タスク実行を提供する洗練されたターミナルネイティブAIコーディングアシスタント
- [TunaCode CLI](https://github.com/alchemiststudiosDOTai/tunacode) - 🍣 安全なgitブランチ、豊富なツール、マルチLLMサポートを備えたTunaCode AI CLIコーディングエージェント
- [Amazon Q CLI](https://github.com/aws/amazon-q-developer-cli) - ✨ ターミナルでのエージェント型チャット体験。自然言語を使用してアプリケーションを構築
- [wcgw](https://github.com/rusiaaman/wcgw) - ClaudeやMCPクライアント向けシェル・コーディングエージェント
- [Nanocoder](https://github.com/Nano-Collective/nanocoder) - Claude CodeやGemini CLIなどのエージェント型コーディングツールの機能をローカルモデルやOpenRouterなどの制御されたAPIに提供するローカルファーストCLIコーディングエージェント
- [GitHub Copilot CLI (Public Preview)](https://github.com/github/copilot-cli) - GitHub Copilot CLIはCopilotコーディングエージェントの力を直接ターミナルにもたらします

## IDE拡張機能

人気のIDEやテキストエディタ向けのプラグインと拡張機能。

### VS Code
- [continue](https://github.com/continuedev/continue) - 主要なオープンソースAIコードアシスタント
- [cline](https://github.com/clinebot/cline) - IDE上で動作する自律コーディングエージェント
- [Roo-Code](https://github.com/RooVetGit/Roo-Code) - エディタ上で動作するAI搭載自律コーディングエージェント
- [CoolCline](https://github.com/coolcline/CoolCline) - Cline、Roo Code、Bao Clineの最高機能を組み合わせたプロアクティブプログラミングアシスタント
- [kodu-coder](https://github.com/kodu-ai/kodu-coder) - IDE上で動作する自律コーディングエージェント
- [twinny](https://github.com/twinnydotdev/twinny) - Visual Studio Code向けの直接的でローカル/API対応のAIコード補完プラグイン
- [vscode-extension](https://github.com/flexpilot-ai/vscode-extension) - VS Code向けオープンソース・ネイティブの真のGitHub Copilot代替品
- [couscous](https://github.com/ARAldhafeeri/couscous) - ベストプラクティスとチーム規約に対してコード品質を分析するAI搭載VS Code拡張機能
- [wizardCoder-vsc](https://github.com/mzbac/wizardCoder-vsc) - WizardCoder向けVisual Studio Code拡張機能
- [Custom Roo Code Modes](https://github.com/jtgsystems/Custom-Modes-Roo-Code) - Visual Studio Code内のRoo Code AIエージェント向けカスタムモード定義の保存・管理・共有の中央場所
- [Gitingest VS Code Extension](https://github.com/lakpahana/export-to-llm-gitingest) - コードベースの分析とLLMフレンドリー形式へのエクスポート機能を持つ強力なVS Code拡張機能
- [Vibe Coding (VICO)](https://github.com/asepindrak/vibe-coding-extension) - プログラミング中に支援するアシスタント付きチャット拡張機能 - 404ストレスなし

### Neovim/Vim
- [avante.nvim](https://github.com/yetone/avante.nvim) - Cursor AI IDEの動作を模倣するNeovimプラグイン
- [codecompanion.nvim](https://github.com/olimorris/codecompanion.nvim) - Neovim上でシームレスなAI搭載コーディング
- [chatgpt.nvim](https://github.com/jackmort/chatgpt.nvim) - OpenAIのChatGPT APIによる簡単な自然言語生成
- [gp.nvim](https://github.com/robitx/gp.nvim) - Gp.nvim（GPTプロンプト）NeovimのAIプラグイン
- [gen.nvim](https://github.com/David-Kunz/gen.nvim) - カスタマイズ可能なプロンプトでLLMを使用してテキストを生成するNeovimプラグイン
- [copilot.vim](https://github.com/github/copilot.vim) - GitHub Copilot向けNeovimプラグイン
- [copilot.lua](https://github.com/zbirenbaum/copilot.lua) - copilot.vimの完全機能・強化版代替品、Github CopilotとやりとりするAPIを備える
- [vim-ai](https://github.com/madox2/vim-ai) - Vim向けAI搭載コードアシスタント。VimとNeovim向けのOpenAIとChatGPTプラグイン
- [VimLM](https://github.com/JosefAlbers/VimLM) - GitHub Copilot/Cursorからインスパイアされた、Vim向けLLM搭載コーディングコンパニオン
- [MCP Hub](https://github.com/ravitemer/mcphub.nvim) - MCP（Model Context Protocol）サーバーをワークフローに統合する強力なNeovimプラグイン
- [minuet-ai.el](https://github.com/milanglacier/minuet-ai.el) - OpenAI、Gemini、Claude、Codestralなど人気LLMからのAIコード補完機能
- [Copilot Chat for Neovim](https://github.com/CopilotC-Nvim/CopilotChat.nvim) - NeovimでGitHub Copilotとチャット

### Emacs
- [aidermacs](https://github.com/MatthewZMD/aidermacs) - EmacsでのAider AIペアプログラミング
- [aider.el](https://github.com/tninja/aider.el) - Emacs内でのaider（AIペアプログラミング）
- [copilot.el](https://github.com/copilot-emacs/copilot.el) - Emacs向け非公式Copilotプラグイン
- [copilot-chat.el](https://github.com/chep/copilot-chat.el) - emacs内でのGitHub copilotチャット

### Xcode
- [CopilotForXcode(@github)](https://github.com/github/CopilotForXcode) - GitHub Copilot向けXcode拡張機能
- [CopilotForXcode(@intitni)](https://github.com/intitni/CopilotForXcode) - 不足していたGitHub Copilot、Codeium、ChatGPT Xcodeソースエディタ拡張機能

### その他のIDE
- [DevoxxGenieIDEAPlugin](https://github.com/devoxx/DevoxxGenieIDEAPlugin) - ローカルLLM（Ollama、LMStudio、GPT4All、Llama.cpp）とクラウドベースLLMを使用してプロジェクトコードのレビュー、テスト、説明を支援するIntelliJ IDEAプラグイン
- [QodeAssist](https://github.com/Palm1r/QodeAssist) - Qt Creator向けAI搭載コーディングアシスタントプラグイン
- [coqpilot](https://github.com/JetBrains-Research/coqpilot) - Coq証明の自動記述を支援するVSCode拡張機能
- [Wingman](https://github.com/winstxnhdw/Wingman) - Windows上のVSCode向けオフラインAIペアプログラマー
- [Co-Clone](https://github.com/Sarvesh-Kannan/Co-Clone) - GitHub Copilotの機能を模倣するローカルAIコーディングアシスタント。Ollama経由でローカルLLM（deepseek-coder:6.7b）を使用してインテリジェントなコード補完とコンテキスト認識実装を提供

## マルチエージェント & オーケストレーション

開発ワークフローで複数のAIエージェントを調整・管理するフレームワークとツール。

- [autogen](https://github.com/microsoft/autogen) - エージェント型AI向けプログラミングフレームワーク
- [crewAI](https://github.com/joaomdmoura/crewAI) - ロールプレイング型自律AIエージェントを調整するフレームワーク
- [MetaGPT](https://github.com/geekan/MetaGPT/) - マルチエージェントフレームワーク：初のAIソフトウェア企業、自然言語プログラミングへ向けて
- [ChatDev](https://github.com/OpenBMB/ChatDev) - 自然言語アイデアを使用してカスタマイズされたソフトウェアを作成
- [gpt-all-star](https://github.com/kyaukyuai/gpt-all-star) - 自律AIエージェントのチーム連携によるWebアプリケーションのスクラッチ開発向けAI搭載コード生成ツール
- [AutoAgents](https://github.com/Link-AGI/AutoAgents) - 複雑なタスクに対して協調エンティティを形成するためのGPT向け異なる役割を生成
- [PraisonAI](https://github.com/MervinPraison/PraisonAI) - AutoGenとCrewAIなどを組み合わせたマルチエージェントLLMシステムの構築・管理向けローコードソリューション
- [Claude Squad](https://github.com/smtg-ai/claude-squad) - Claude Code、Aider、Codex、OpenCode、Ampなど複数のAIターミナルエージェントを管理
- [Claude-Flow v2.0.0 Alpha](https://github.com/ruvnet/claude-flow) - エンタープライズグレードアーキテクチャ、高度スウォーム知能、Claude Codeシームレス統合でゼロから構築
- [Activepieces](https://github.com/activepieces/activepieces) - AIエージェント＆MCP＆AIワークフロー自動化 • AIエージェント用約400個MCPサーバー • MCP付きAI自動化/AIエージェント • AIワークフロー＆AIエージェント • AIエージェント用MCP
- [Heurist Agent Framework](https://github.com/heurist-network/heurist-agent-framework) - 推論、ツール使用、メモリ、深度研究、ブロックチェーンインタラクション、MCP、エージェント・アズ・ア・サービスでエージェントを構築する柔軟なマルチインターフェースAIエージェントフレームワーク
- [nous](https://github.com/TrafficGuard/nous) - 自律AIエージェントとLLMベースワークフロー向けオープンソースTypeScriptプラットフォーム
- [crewai-factory-crew](https://github.com/opahopa/crewai-factory-crew) - クルーの目的と希望する出力データに基づいて完全に機能するクルーを生成
- [Symphony v0.2](https://github.com/sincover/Symphony) - 構造化された効率的なワークフローでAIエージェントを調整する洗練されたマルチエージェントソフトウェア開発フレームワーク
- [VoltAgent](https://github.com/voltagent/voltagent) - AIエージェントの構築と調整向けオープンソースTypeScriptフレームワーク
- [LLM Agent X](https://github.com/cvaz1306/llm_agent_x) - タスクをサブタスクに分割し、Web検索などのツールを使用して複雑なタスクを実行する言語モデル活用タスク実行フレームワーク
- [ManusMCP](https://github.com/mantrakp04/manusmcp) - 専門能力を持つAIチームメンバーをデプロイするFlowiseを使用したAIエージェントフレームワーク
- [GitAGU (Git Agent Unblock)](https://github.com/microsoft/gitagu) - 開発ワークフローにAIエージェントを発見、設定、統合するための一元プラットフォーム。ソフトウェア開発ライフサイクル全体にわたるAI導入を簡素化
- [Floki](https://github.com/FinnaAI/floki) - 複数のAIコーディングエージェントを並行して使用する新しいパラダイムを創造し、AI搭載アシスタンスでより良いソフトウェアをより速く構築
- [Omnara](https://github.com/omnara-ai/omnara) - エージェントが何をしているかをリアルタイムで可視化し、Webとモバイルの単一ダッシュボードから質問に即座に応答
- [Giselle](https://github.com/giselles-ai/giselle) - AI駆動ソリューションを簡単に作成できるエージェント型ワークフロービルダー
- [development-workforce](https://github.com/Grusinator/development-workforce) - AIエージェントを既存のソフトウェア開発セットアップに統合する実験
- [agentok](https://github.com/hughlv/agentok) - マルチエージェント開発向けビジュアルツール
- [HyperAgent](https://github.com/FSoft-AI4Code/HyperAgent) - 様々なプログラミング言語で幅広いソフトウェアエンジニアリング（SE）タスクに対応する汎用マルチエージェントシステム
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - AI搭載ソフトウェア開発エージェント向けプラットフォーム。コード修正、コマンド実行、Web閲覧、API呼び出しなど人間の開発者ができることを実行

## コード生成 & 自動化

コード生成、開発タスクの自動化、プロジェクトテンプレート作成のためのツール。

- [gpt-engineer](https://github.com/gpt-engineer-org/gpt-engineer) - 作りたいものを指定すると、AIが明確化を求め、その後構築
- [amplication](https://github.com/amplication/amplication) - 唯一のプロダクション対応AI搭載バックエンドコード生成
- [llamacoder](https://github.com/Nutlope/llamacoder) - オープンソースのClaude Artifacts – 一つのプロンプトで小さなアプリを生成
- [ai-app-builder](https://github.com/fireproof-storage/ai-app-builder) - 単一ページアプリとしてデプロイされた最もフォークしやすいAIアプリジェネレーター
- [vibes.diy](https://github.com/fireproof-storage/vibes.diy) - 最もフォークしやすいAIアプリジェネレーターで数秒で共有可能なアプリを生成
- [oneShotCodeGen](https://github.com/vivek100/oneShotCodeGen) - 単一プロンプトでフルスタックWebアプリを作成
- [aiCoder](https://github.com/mmiscool/aiCoder) - AIを使用してJSライブラリを書くツール
- [CodePanda](https://github.com/jjleng/code-panda) - 自然言語でのやりとりによってフルスタックWebアプリケーションを構築するAI搭載コーディングツール
- [GenDB](https://github.com/CNimmo16/genDB) - AIを使用して数秒でデータベース全体を生成
- [AIGenPipeline](https://github.com/stoerr/AIGenPipeline) - AIベースコード生成パイプライン
- [Sourcery](https://github.com/krzysztofzablocki/Sourcery) - AppleのSwiftSyntaxの上に構築されたSwift言語向けコードジェネレーター
- [code-converter](https://github.com/JoKerDii/code-converter) - PythonコードをC++に変換するAIツール
- [Promptr](https://github.com/ferrislucas/promptr) - プレーンな英語でOpenAI LLMモデルにコードベースの変更を指示するCLIツール
- [unvibe](https://github.com/santinic/unvibe) - ユニットテストからコードを生成
- [coffee](https://github.com/Coframe/coffee) - AI使用により自分のIDEでUI構築・反復を10倍高速化
- [Tour of Heroes API](https://github.com/0GiS0/tour-of-heroes-with-gh-copilot-coding-agent) - スーパーヒーローを管理するREST API、Node.jsとTypeScriptで実装。ヒーローデータの取得、作成、更新、削除のエンドポイントを備えた「Tour of Heroes」アプリケーション用シンプルバックエンド
- [Legacy2Modern (L2M)](https://github.com/astrio-ai/legacy2modern) - レガシーCOBOLコードを現代的でメンテナンス可能なPythonアプリケーションに変換するオープンソースエンジン
- [AI Website Builder](https://github.com/Ratna-Babu/Ai-Website-Builder) - 自然言語プロンプトをNext.js、Tailwind CSS、Gemini AIを使用して完全に機能するReactコンポーネントに変換するAI搭載ウェブサイトビルダー
- [RooFlow Cookiecutter Template](https://github.com/hheydaroff/RooFlow-Cookiecutter) - RoocodeにRooflowを簡単に適用するテンプレート
- [Vibe Coding a Full-Stack Budget App](https://github.com/wasp-lang/vibe-coding-video) - Vibe Codingフルスタックアプリスターターテンプレート

## テスト & セキュリティ

テスト、品質保証、セキュリティ分析、コードカバレッジ向けAI搭載ツール。

- [qodo-cover](https://github.com/qodo-ai/qodo-cover) - 自動テスト生成とコードカバレッジ向上向けAI搭載ツール！💻🤖🧪🐞
- [shortest](https://github.com/anti-work/shortest) - 自然言語AIテストによるQA
- [mutahunter](https://github.com/codeintegrity-ai/mutahunter) - オープンソース、言語非依存自動テスト生成 + LLMミューテーションテスト
- [testzeus-hercules](https://github.com/test-zeus-ai/testzeus-hercules) - 最も困難なテスト業務を処理する世界初のオープンソーステストエージェント、Hercules
- [ghostest](https://github.com/ryooo/ghostest) - LLMエージェントを使用してテストコードを出力
- [HexStrike AI](https://github.com/0x4m4/hexstrike-ai) - 高度なMCPサーバーで、AIエージェント（Claude、GPT、Copilotなど）が150以上のサイバーセキュリティツールを自律的に実行し、自動ペネトレーションテスト、脆弱性発見、バグバウンティ自動化、セキュリティ研究を実現。12以上の自律AIエージェントとリアルタイムダッシュボードを備えた包括的なセキュリティ自動化プラットフォーム
- [UTGenDebug](https://github.com/archiki/UTGenDebug) - 自動デバッグ向けユニットテスト生成の学習
- [VibeSec](https://github.com/untamed-theory/vibesec) - 新たなAI開発の潮流におけるセキュリティルールとワークフロー
- [OpenDeRisk](https://github.com/derisk-ai/OpenDerisk) - AIネイティブリスク情報システム、OpenDeRisk——アプリケーションシステムリスクインテリジェント管理者が7×24時間包括的で深度な保護を提供
- [TDD Guard](https://github.com/nizos/tdd-guard) - Claude Code向け自動テスト駆動開発強制
- [auto-inspector](https://github.com/agentlabs-dev/auto-inspector) - Webテスト AIエージェント - 仕様を書くと残りを実行
- [arbigent](https://github.com/takahirom/arbigent) - Android、iOS、Webアプリテスト向けAIエージェント
- [kaizen](https://github.com/Cloud-Code-AI/kaizen) - コーディング中のバグ発見を支援するAIアシスタント
- [VulnViper](https://github.com/anshulyadav1976/VulnViper) - Pythonコードベース内の潜在的脆弱性の特定と理解を支援するインテリジェントセキュリティ監査ツール
- [codegate](https://github.com/stacklok/codegate) - AIコーディングアシスタントを安全にするローカルゲートウェイ
- [vibelint](https://github.com/mithranm/vibelint) - コードベースをLLMフレンドリーにする
- [Vibe Security](https://github.com/astoj/vibe-security) - Vibeコーダー向け包括的セキュリティチェックリスト
- [Strix](https://github.com/usestrix/strix) - 「AIハッカー」として機能するオープンソースのセキュリティエージェント。開発ワークフローに統合し、アプリケーションの脆弱性を能動的にテスト・発見する。ローカルで実行し、継続的なセキュリティテストを自動化できる
- [TheAuditor](https://github.com/TheAuditorTool/Auditor) - オフラインファースト、AI中心のSAST＆コードインテリジェンスプラットフォーム

## MCPサーバー & 統合

AI機能強化のためのModel Context Protocolサーバーと統合。

- [GitHub MCP Server](https://github.com/github/github-mcp-server) - GitHub APIとのシームレスな統合を提供するModel Context Protocol（MCP）サーバー
- [AWS MCP Servers](https://github.com/awslabs/mcp) - AWS ベストプラクティスを開発ワークフローに直接持ち込む専門MCPサーバースイート
- [MCP C# SDK](https://github.com/modelcontextprotocol/csharp-sdk) - Microsoft保守のModel Context Protocolサーバー・クライアント向け公式C# SDK
- [MCP Go](https://github.com/mark3labs/mcp-go) - LLMアプリケーションと外部データソース・ツール間のシームレスな統合を可能にするModel Context Protocol（MCP）のGo実装
- [Unified MCP Client Library](https://github.com/pietrozullo/mcp-use) - カスタムエージェントでmcpサーバーとやりとりする最も簡単な方法
- [Multi Database MCP Server](https://github.com/FreePeak/db-mcp-server) - AIアシスタントに構造化されたデータベースアクセスを提供するModel Context Protocol（MCP）実装の強力なマルチデータベースサーバー
- [Supabase MCP Server](https://github.com/supabase-community/supabase-mcp) - SupabaseプロジェクトをCursor、Claude、Windsurf、その他のAIアシスタントに接続
- [claude-context](https://github.com/zilliztech/claude-context) - Claude Code用コード検索MCP。全コードベースを任意のコーディングエージェントのコンテキストに
- [Kodit](https://github.com/helixml/kodit) - 外部リポジトリをインデックス化するMCPサーバー
- [PageSpeed Insights MCP Server](https://github.com/ruslanlap/pagespeed-insights-mcp) - Google PageSpeed Insights APIのMCPサーバー、Claudeから直接Webページパフォーマンス解析を可能にする
- [Browser Control MCP](https://github.com/eyalzh/browser-control-mcp) - ブラウザ拡張機能と連携してAIエージェントがユーザーのブラウザを制御できるMCPサーバー
- [LINE Bot MCP Server](https://github.com/line/line-bot-mcp-server) - LINE Messaging APIを統合してAIエージェントをLINE公式アカウントに接続するMCPサーバー
- [Kubernetes MCP Server](https://github.com/containers/kubernetes-mcp-server) - KubernetesとOpenShift用Model Context Protocol（MCP）サーバー
- [Computer Control MCP](https://github.com/AB498/computer-control-mcp) - PyAutoGUI、RapidOCR、ONNXRuntimeを使用してマウス、キーボード、OCRなどのコンピューター制御機能を提供するMCPサーバー。AnthropicのComputer-useと類似、外部依存関係ゼロ
- [Gemini MCP Server for Claude Code](https://github.com/BeehiveInnovations/gemini-mcp-server) - GeminiとClaude Codeの連携。ClaudeのExtended ThinkingにGeminiの視点で補強
- [GitHub Chat MCP](https://github.com/AsyncFuncAI/github-chat-mcp) - GitHub Chat APIを使用してGitHubリポジトリを分析・クエリするModel Context Protocol（MCP）
- [Github Semantic Search MCP Server](https://github.com/edelauna/github-semantic-search-mcp) - インデックス化されたGitHubリポジトリに対するRAGクエリを促進するリモートMCPサーバー
- [GitLab-MCP-Server](https://github.com/owayo/gitlab-mcp-server) - GitLabとの統合を提供するModel Context Protocol（MCP）サーバー
- [Desktop Commander MCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) - Claudeにターミナル制御、ファイルシステム検索、差分ファイル編集機能を与えるMCPサーバー
- [Playwright MCP](https://github.com/microsoft/playwright-mcp) - MCP向けPlaywrightツール
- [Web Accessibility-Testing MCP Server](https://github.com/ronantakizawa/a11ymcp) - LLMにWebアクセシビリティテストAPIへのアクセスを提供するMCP（Model Context Protocol）サーバー
- [ghidraMCP](https://github.com/LaurieWired/GhidraMCP) - LLMが自律的にアプリケーションをリバースエンジニアリングできるModel Context Protocolサーバー
- [Deebo](https://github.com/snagasuri/deebo-prototype) - Model Context Protocol（MCP）を使用したコーディングエージェントワークフローへの統合向け自律デバッグシステム
- [Obsidian MCP Tool Server](https://github.com/Rwb3n/obsidian-mcp) - Obsidianボルトとのやりとりツールを公開するModel Context Protocol（MCP）サーバー
- [Octocode MCP](https://github.com/bgauryy/octocode-mcp) - コード検索分析MCP
- [Serena](https://github.com/oraios/serena) - セマンティック検索・編集機能を持つ強力なコーディングエージェント（MCPサーバー）
- [Context7 MCP](https://github.com/upstash/context7) - LLMとAIコードエディタ向けの最新ドキュメント
- [Vibe Check MCP](https://github.com/PV-Bhat/vibe-check-mcp-server) - Vibeコーダーの決定的な正気度チェックMCPサーバー
- [hyper-mcp](https://github.com/tuananh/hyper-mcp) - WebAssemblyプラグインによって機能を拡張する高速・セキュアなMCPサーバー
- [interactive-mcp](https://github.com/ttommyth/interactive-mcp) - AIエージェントとやりとりするためのローカル・クロスプラットフォームMCPサーバー
- [Jinni](https://github.com/smat-dev/jinni) - プロジェクトをLLMコンテキストに持ち込む - ツールとMCPサーバー
- [Kratos MCP](https://github.com/ceorkm/kratos-mcp) - プロジェクト分離の完璧さ、95.8%のコンテキスト精度、Four Pillarsフレームワークを備えたMCPサーバー
- [MCP Shrimp Task Manager](https://github.com/cjo4m06/mcp-shrimp-task-manager) - 🦐 AI駆動開発向けインテリジェントタスク管理 - 複雑なプロジェクトを管理可能なタスクに分解し、セッション間でコンテキストを維持し、開発ワークフローを加速
- [Rust Docs MCP Server](https://github.com/Govcraft/rust-docs-mcp-server) - 🦀 AIアシスタントからの古いRustコード提案を防止。このMCPサーバーは最新のクレートドキュメントを取得し、埋め込み/LLMを使用し、ツール呼び出し経由で正確なコンテキストを提供
- [MCP Memory Service](https://github.com/doobidoo/mcp-memory-service) - AIアシスタント向けのセマンティックメモリ検索と永続ストレージを提供するユニバーサルMCPメモリサービス
- [Roslyn MCP Server](https://github.com/carquiza/RoslynMCP) - MicrosoftのRoslynコンパイラプラットフォームと統合し、Claude DesktopにC#コードベースのコード分析とナビゲーション機能を提供するC# MCP（Model Context Protocol）サーバー
- [SharpTools](https://github.com/kooshi/sharptoolsmcp) - AIがC#ソリューションを分析・変更するための高精度、Roslyn搭載コンテキストを備えたMCPツールスイート
- [Roslyn Code Analysis MCP Server](https://github.com/egorpavlikhin/roslyn-mcp) - Roslynコンパイラプラットフォームを使用してC#コード分析機能を提供するModel Context Protocol（MCP）サーバー
- [Things 3 MCP Server](https://github.com/ebowman/mcp-server-things) - Claudeや他のAIアシスタントをThings 3に接続し、自然言語でタスク管理を可能にするModel Context Protocol（MCP）サーバー
- [Ref MCP](https://github.com/ref-tools/ref-tools-mcp) - 公的・私的ドキュメンテーションに対するトークン効率的検索でハルシネーションを防止するMCPサーバー
- [DockaShell](https://github.com/anzax/dockashell) - AIエージェントに分離されたDockerコンテナを提供するMCPサーバー。シェルアクセス、ファイル操作、完全監査証跡用MCPツール
- [Claude Context Local](https://github.com/FarhanAliRaza/claude-context-local) - Claude Code用コード検索MCP。全コードベースを任意のコーディングエージェントのコンテキストに。埋め込みはローカルで作成・保存され、APIコストなし
- [MCP Code Checker](https://github.com/MarcusJellinghaus/mcp-code-checker) - 簡単なクライアント設定でコード品質チェック操作を提供するモデルコンテキストプロトコル（MCP）サーバー
- [Docker MCP Plugin and Docker MCP Gateway](https://github.com/docker/mcp-gateway/) - docker mcp CLI plugin / MCP Gateway

## コードレビュー & コラボレーション

コードレビュー、プルリクエスト自動化、チームコラボレーションのためのツール。

- [pr-agent](https://github.com/Codium-ai/pr-agent) - CodiumAI PR-Agent：自動プルリクエスト解析、フィードバック、提案などのAI搭載🤖ツール！
- [ai-pr-reviewer](https://github.com/coderabbitai/ai-pr-reviewer) - チャット機能付きAIベースプルリクエスト要約・レビューアー
- [gitpack-ai](https://github.com/gitpack-ai/gitpack-ai) - AIによるプルリクエストレビューの自動化
- [lgtm-ai](https://github.com/elementsinteractive/lgtm-ai) - AI搭載コードレビューコンパニオン
- [pr-pilot](https://github.com/PR-Pilot-AI/pr-pilot) - コードベースの検索・操作、インターネット閲覧、Githubイシュー・プルリクエストとのやりとりが可能な開発ワークフロー向けAIエージェント
- [pr-pilot-cli](https://github.com/PR-Pilot-AI/pr-pilot-cli) - PR Pilot向けコマンドラインインターフェース
- [Review Gate for Cursor IDE ゲート](https://github.com/LakshmanTurlapati/Review-Gate) - 月間リクエストから最大5倍の価値を得られるCursor IDE向け強力なルール
- [PR-Agent](https://github.com/qodo-ai/pr-agent) - AI搭載 🤖 自動プルリクエスト分析、フィードバック、提案などのツール！ 💻🔍
- [kodus](https://github.com/kodustech/kodus-ai) - シニア開発者のようなオープンソースAIコードレビュー
- [Costrict](https://github.com/zgsm-ai/costrict) - エンタープライズ向けの厳格なAIコーダー、品質優先、AIエージェント、AIコードレビュー、AI補完を含む

## プロジェクト & ナレッジ管理

AI駆動開発におけるプロジェクト管理、ドキュメント、ナレッジ整理のためのツール。

- [Backlog.md](https://github.com/MrLesk/Backlog.md) - gitエコシステム内での人間とAIエージェント間のプロジェクト連携管理ツール
- [ai-ticket](https://github.com/jmikedupont2/ai-ticket) - AIベースコード生成をチケット管理するAIと人間協働のチケットシステム
- [Task Master](https://github.com/eyaltoledano/claude-task-master) - ClaudeによるAI駆動開発向けタスク管理システム、Cursor AIとのシームレスな連携設計
- [SprintCore](https://github.com/spicewoodlabs/sprintcore) - AIによるバグ修正、ユーザーストーリー作成、PRD作成、スプリント管理
- [Tutorial-Codebase-Knowledge](https://github.com/The-Pocket/Tutorial-Codebase-Knowledge) - AIでコードベースを分かりやすいチュートリアルに変換
- [reqtext](https://github.com/fred-terzi/reqtext) - 要求管理をワークフローに直接持ち込むGitネイティブ・CLIファースト要求・ドキュメンテーションフレームワーク
- [Vibook](https://github.com/pinqy520/roo-code-vibook) - AI支援による継続的メンテナンス向けAIフレンドリープロジェクトドキュメント（Roo Code）
- [Claude Code PM](https://github.com/automazeio/ccpm) - GitHub IssuesとGit worktreeを使用した並列エージェント実行によるClaude Code向けプロジェクト管理システム
- [Claude Conductor](https://github.com/superbasicstudio/claude-conductor) - AI支援開発でClaude Code向けに設計された軽量・モジュラードキュメンテーションフレームワーク
- [Basic Memory](https://github.com/basicmachines-co/basic-memory) - AIアシスタントとの会話から永続的セマンティックグラフを構築できる知識管理システム
- [RepoScribe](https://github.com/mikeusru/reposcribe) - プロジェクトディレクトリをスキャンし、.gitignoreルールで無視されないファイルを特定し、内容を単一テキストファイルに連結するコマンドラインツール
- [AndAI](https://github.com/andrejsstepanovs/andai) - チケットシステムとgit統合を備えたAI支援コーディングタスクを整理するローカルツール
- [Claude Self-Reflect](https://github.com/ramakay/claude-self-reflect) - Claudeにすべての会話の完璧なメモリを提供。過去のディスカッションを即座に検索。コンテキストを失わない

## 言語モデル & エンジン

コーディングと開発タスク向けに設計された専門言語モデルとAIエンジン。

- [CodeGeeX](https://github.com/THUDM/CodeGeeX) - オープン多言語コード生成モデル
- [CodeGeeX2](https://github.com/THUDM/CodeGeeX2) - より強力な多言語コード生成モデル
- [CodeGeeX4](https://github.com/THUDM/CodeGeeX4) - コード補完、コードインタープリター、Web検索、関数呼び出し、リポジトリレベルQ&Aなど、すべてのAIソフトウェア開発シナリオ向け多機能モデル
- [aiXcoder-7B](https://github.com/aixcoder-plugin/aixcoder-7b) - コード大規模言語モデル
- [AutoCoder](https://github.com/bin123apple/AutoCoder) - HumanEvalベースデータセットでのテスト精度がGPT-4 Turbo（2024年4月）とGPT-4oを上回る
- [Yi-Coder](https://github.com/01-ai/Yi-Coder) - 100億パラメータ未満で最先端コーディング性能を提供するオープンソースコード言語モデルシリーズ
- [Qwen2.5-Coder](https://github.com/QwenLM/Qwen2.5-Coder) - Qwen2.5のコード版
- [Lingma-SWE-GPT](https://github.com/LingmaTongyi/Lingma-SWE-GPT) - Lingma SWE-GPTの推論コード
- [tabby](https://github.com/TabbyML/tabby) - セルフホスト型AIコーディングアシスタント
- [turbopilot](https://github.com/ravenscroftj/turbopilot) - CPU上でローカル実行されるオープンソース大規模言語モデルベースコード補完エンジン
- [ollama-autocoder](https://github.com/10Nates/ollama-autocoder) - オプション公開・ストリーミング機能付きの使いやすいOllama自動補完エンジン
- [O1-CODER](https://github.com/ADaM-BJTU/O1-CODER) - コーディング向けO1レプリケーション
- [lsp-ai](https://github.com/SilasMarvin/lsp-ai) - ソフトウェアエンジニアを置き換えるのではなく、支援・強化するよう設計されたAI搭載機能のバックエンドとして機能するオープンソース言語サーバー
- [rift](https://github.com/morph-labs/rift) - 個人AIソフトウェアエンジニア向けAIネイティブ言語サーバー
- [FireCoder](https://github.com/FireCoderAI/firecoder) - ローカルマシン上でコーディング体験を最適化するために構築されたセルフホスト型AIアシスタント

## 開発ワークフロー & エージェント

AI支援開発ワークフローを管理するツール、フレームワーク、自律エージェント。

- [SWE-agent](https://github.com/princeton-nlp/SWE-agent) - GitHubイシューを取得し、GPT-4または選択したLMを使用して自動修正を試行
- [OpenDevin](https://github.com/OpenDevin/OpenDevin) - AIとLLMを活用した自律ソフトウェアエンジニア向けプラットフォーム
- [devika](https://github.com/stitionai/devika) - エージェント型AIソフトウェアエンジニア
- [Devon](https://github.com/entropy-research/Devon) - オープンソースペアプログラマー
- [SuperCoder](https://github.com/TransformerOptimus/SuperCoder) - オープンソース自律ソフトウェア開発システム
- [auto-code-rover](https://github.com/nus-apr/auto-code-rover) - 自律プログラム改善を目指すプロジェクト構造認識型自律ソフトウェアエンジニア
- [SWE-Fixer](https://github.com/internlm/SWE-Fixer) - オープンソースLLMをトレーニングすることで現実世界のGitHubイシューに対処するシンプルで効果的なソリューション
- [Spec Kit](https://github.com/github/spec-kit) - 仕様駆動開発を始めるためのツールキット
- [Disciplined AI Software Development - Collaborative](https://github.com/Varietyz/Disciplined-AI-Software-Development) - AI開発プロジェクトでの構造化アプローチ。コード肥大化、アーキテクチャドリフト、コンテキスト希釈などの一般的問題に体系的な制約で対処する手法
- [gac (Git Auto Commit)](https://github.com/cellwebb/gac) - ステージされた変更に基づき高品質なコミットメッセージを自動生成するAI搭載gitコミットメッセージ生成器
- [Memov](https://github.com/memovai/mem) - Git上のAIコーディングバージョン管理。何が変更されただけでなく、なぜ変更されたかを追跡
- [Agentless](https://github.com/OpenAutoCoder/Agentless) - ソフトウェア開発問題を自動解決するエージェントレスアプローチ
- [OpenEvolve](https://github.com/codelion/openevolve) - 画期的なアルゴリズムを発見する自律コード最適化器にLLMを変換
- [gwq](https://github.com/d-kuro/gwq) - ファジーファインダー付きGit worktreeマネージャー - 複数のブランチで同時作業、並列AIコーディングワークフローに最適
- [agilecoder](https://github.com/fsoft-ai4code/agilecoder) - 複雑な現実世界のソフトウェア作成にアジャイル手法をエージェントに組み込む
- [sparc2](https://github.com/agenticsorg/sparc2) - ソフトウェア開発の自動化・合理化向けインテリジェントコーディングエージェントフレームワーク、SPARC 2.0エージェント型コード解析・生成
- [Kilo Code](https://github.com/Kilo-Org/kilocode) - 計画、構築、コード修正向けオープンソースAIコーディングアシスタント
- [vespper](https://github.com/vespperhq/vespper) - オープンソースAI オンコール開発者
- [droid.dev](https://github.com/bootstrapguru/droid.dev) - 実際にコーディングするAIエンジニア
- [Localforge](https://github.com/rockbite/localforge) - ローカルWeb UIで実行され、ファイルと協働して自律動作
- [Perpetual](https://github.com/DarkCaster/Perpetual) - LLM駆動ソフトウェア開発ヘルパー
- [Dyad](https://github.com/dyad-sh/dyad) - コーディングスキルを向上させ、現実世界のソフトウェア構築を支援するオープンソース・スタンドアロンAIツール
- [daiv](https://github.com/srtab/daiv) - 開発業務の自動化とワークフローの改善向けAI駆動ツール
- [DevGPT](https://github.com/fabriziosalmi/DevGPT) - 今すぐ一緒にコーディング！
- [Devseeker](https://github.com/iBz-04/Devseeker) - claude codeとaiderからインスパイアされたコーディングエージェント
- [DeepCode](https://github.com/HKUDS/DeepCode) - コード生成と実装タスクを自動化するAI搭載開発プラットフォーム
- [CoaCoA](https://github.com/im-shashanks/CoaCoA) - エンタープライズグレードのコンプライアンスで高品質でテスト済みコードを提供するためのAIエージェントを開発ワークフローに統合するプロダクション対応フレームワーク
- [CodeBuddy](https://github.com/olasunkanmi-SE/codebuddy) - 高度なエージェント機能を備えた生成AIアシスタント。Codebuddyは機械学習を使用してコードを生成し、タスクを完了し、コーディングタスクワークフローを合理化

## コード解析 & 検索

コードベースの解析、検索、理解のためのツール。

- [cody](https://github.com/sourcegraph/cody) - タイピング削減、コーディング増進：Codyは高度検索とコードベースコンテキストを使用してコード記述・修正を支援するAIコードアシスタント
- [SeaGOAT](https://github.com/kantord/SeaGOAT) - ローカルファーストセマンティックコード検索エンジン
- [VectorCode](https://github.com/Davidyz/VectorCode) - コードリポジトリインデックスツール。リポジトリのインデックス化と情報提供により、コーディングLLM向けの優れたプロンプト記述を支援
- [Project Indexer](https://github.com/Dolfie-01/ProjectIndexer) - プロジェクト内のクラス、ファイル、その他のコンポーネントの場所をインデックス化するシンプルスクリプト
- [codemapper](https://github.com/shaneholloman/codemapper) - 指定ディレクトリの構造と内容を表現する包括的Markdownドキュメントを作成するpythonスクリプト
- [code2prompt](https://github.com/raphaelmansuy/code2prompt) - コードベース内容を含む包括的Markdownファイル生成により、大規模言語モデル（LLM）へのコンテキスト提供プロセスを簡素化する強力なコマンドラインツール
- [Code-to-Clipboard-for-LLMs](https://github.com/yigitkonur/code-to-clipboard-for-llms) - LLM向けプロジェクトのコードコンテキストをインテリジェントにパッケージ化
- [vibe-log-cli](https://github.com/vibe-log/vibe-log-cli) - Claude Codeセッションをローカル解析し生産性レポートを生成するオープンソースCLI
- [Claude Code Usage Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) - 予測と警告を備えたリアルタイムClaude Code使用量モニター
- [Telegram Search](https://github.com/groupultra/telegram-search) - 🔍 ベクトル検索とセマンティックマッチング機能を備えた強力なTelegramチャット検索ツール
- [codeselect](https://github.com/maynetee/codeselect) - ClaudeやChatGPTなどのAIアシスタントとコードを選択・共有するシンプル・インタラクティブツール
- [shotgun_code](https://github.com/glebkudr/shotgun_code) - 大規模言語モデルワークフロー向けワンクリックコードベース「ブラスト」
- [open-repoprompt](https://github.com/wildberry-source/open-repoprompt) - トークン制限に達することなく、Claude、GPT-4、Grokなどにコード・ドキュメントを供給する高速・軽量Goツール
- [ctx](https://github.com/context-hub/generator) - ChatGPTやClaudeなどのLLMとチャット時の大きな問題であるプロジェクトに関する十分なコンテキスト提供を解決するツール
- [SourceSage](https://github.com/Sunwood-ai-labs/SourceSage) - AIを使用したソフトウェア開発支援ツール
- [RepoGPT](https://github.com/mbarinov/repogpt) - リポジトリとの簡単なチャット、管理、探索を行うAI搭載GitHubアシスタント

## ドメイン固有ツール

特定の開発ドメインとタスク向けの専門AIツール。

### Git・バージョン管理
- [ai-commit-tool](https://github.com/awkwardlysocial/ai-commit-tool) - AIベースgitコミットメッセージを生成するCLIツール
- [commit](https://github.com/wajeht/commit) - AIで従来型コミットを生成
- [lazycommit](https://github.com/m7medVision/lazycommit) - AIを使用してコミットメッセージ提案を生成
- [aider-github-action](https://github.com/mirrajabi/aider-github-action) - GithubワークフローでAider AIアシスタントを実行！
- [aider-github-workflows](https://github.com/mirrajabi/aider-github-workflows) - aider-github-actionを使用するワークフロー

### クラウド・DevOps
- [kubectl-ai](https://github.com/GoogleCloudPlatform/kubectl-ai) - ターミナルで動作するAI搭載kubernetesエージェント
- [kube-copilot](https://github.com/feiskyer/kube-copilot) - OpenAI搭載Kubernetes Copilot
- [K8sWhisperer-](https://github.com/ARAldhafeeri/K8sWhisperer-) - ログのクエリと自然言語での読み取りを可能にするAI搭載Kubernetes Operator
- [Arconia Framework](https://github.com/arconia-io/arconia) - 開発者体験とクラウドネイティブアーキテクチャに重点を置き、JavaとSpring Bootを使用したモダンエンタープライズアプリケーション構築向けフレームワーク

### 言語固有
- [coders](https://github.com/0xKoda/coders) - rustのAIコーディングアシスタント
- [AutoBE](https://github.com/wrtnlabs/autobe) - コンパイラスキルで強化されたTSバックエンドサーバーのAI Vibeコーディングエージェント
- [Winx Code Agent](https://github.com/rokytory/winx-code-agent) - WCGWとSerenaの最高機能を組み合わせた最大効率・セマンティック機能向けRust記述高性能コードエージェント
- [cursor_agent](https://github.com/zalab-inc/cursor_agent) - Cursor AIエージェント向け構造化タスクシーケンス作成TypeScriptライブラリ

### ターミナル・シェル
- [TmuxAI](https://github.com/alvinunreal/tmuxai) - tmuxセッション内での直接的なインテリジェントペアプログラマー
- [devblahblah](https://github.com/devblahblah/devblahblah) - LLM APIを使用した開発業務支援のためのシンプルツール

### プロンプト・コンテキスト管理
- [Prompt Tower](https://github.com/backnotprop/prompt-tower) - コードブロックが多数含まれるプロンプトの構築とコンテキスト管理支援ツール
- [Oyren Prompter](https://github.com/oyren-dev/oyren-prompter) - 複数ファイルの閲覧・選択、内容の結合、カスタムプロンプトの前付けを可能にするローカルWebツール
- [Nomad's AI Prompt Library](https://github.com/TechNomadCode/Open-Source-Prompt-Library) - 様々なAIモデル向けの効果的なプロンプトを保存・整理・共有する中央リポジトリ
- [zoltraak](https://github.com/dai-motoki/zoltraak) - 自然言語を実行言語に変換するプロンプトコンパイラシステム
- [cmpr](https://github.com/inimino/cmpr) - 英語でプログラミング！LLM対応プログラミングフレームワーク

### Copilot拡張・代替品
- [copilot-more](https://github.com/jjleng/copilot-more) - コーディング・その他向け月額10ドルのGPT-4oとClaude-3.5-Sonnet API
- [copilot-proxy](https://github.com/jjleng/copilot-proxy) - あらゆるLLMモデルでGH Copilot拡張機能を動作させる
- [Copilot LSP](https://github.com/copilotlsp-nvim/copilot-lsp) - Neovim向け設定

## データセット生成 & 合成データ

AI駆動開発ワークフロー向けの合成データセット生成ツール。

- [DeepFabric](https://github.com/lukehinds/deepfabric) - 構造化出力とより効率的なツール呼び出しのためのモデルファインチューニング用合成データセット、およびエージェントとモデル評価データの生成

## 学習リソース

AI駆動開発を学ぶためのチュートリアル、ベストプラクティス、リソース。

- [The BMAD-Method 3.1](https://github.com/bmadcode/BMAD-METHOD) - アジャイルAI駆動開発のブレークスルー手法
- [Guide to AI-Assisted Development Using kliewerdaniel/workflow](https://github.com/kliewerdaniel/workflow) - 構造化AI支援開発ワークフローガイド
- [OSWorld](https://github.com/xlang-ai/OSWorld) - 実コンピュータ環境でのオープンエンド業務向けマルチモーダルエージェントのベンチマーク
- [The Rules Template: Universal Rules for AI Coding Assistants](https://github.com/Bhartendu-Kumar/rules_template) - CursorやCLINEなどのAIコーディングアシスタントの性能向上向けの堅牢で適応可能なルールフレームワーク
- [Vibe Rules Collection](https://github.com/copyleftdev/vibe-rules-collection) - 様々なベストプラクティスに従ったコード生成をAIコーディングアシスタントに指導する.windsurfrulesファイルの厳選コレクション
- [Ruler](https://github.com/intellectronica/ruler) - すべてのコーディングエージェントに同じルールを適用
- [Cursor AI rules for Java](https://github.com/jabrena/cursor-rules-java) - ソフトウェアエンジニアの日常的なプログラミング作業を支援するJava向けシステムプロンプトのコレクション
- [Mastering GitHub Copilot](https://github.com/microsoft/Mastering-GitHub-Copilot-for-Paired-Programming) - GitHub CopilotをAIペアプログラミングリソースとして使用するために必要なすべてを教えるマルチモジュールコース

## フレームワーク & ライブラリ

AIコーディングアシスタントを構築・強化するためのフレームワーク、ライブラリ、設定。

- [AI-Setup](https://github.com/ctavolazzi/ai-setup) - AI支援開発環境のセットアップと作業管理向けツールキット
- [AiDE](https://github.com/FixingPixels/AiDE) - AI支援でプロジェクト開発への構造化アプローチ
- [AiderDesk](https://github.com/hotovo/aider-desk) - Aider AIアシスタント向けデスクトップアプリケーション
- [Crystal](https://github.com/stravu/crystal) - 並列gitワークツリーで複数のClaude Code AIセッションを実行。アプローチをテスト・比較し、AI支援開発ワークフローを一つのデスクトップアプリで管理
- [VibeKit](https://github.com/superagent-ai/vibekit) - Claude Code、Gemini、Codexなどのコーディングエージェントをクリーンで隔離されたサンドボックスで実行。機密データのマスキングと観測可能性を内蔵
- [opcode](https://github.com/getAsterisk/opcode) - Claude Code向け強力なGUIアプリとツールキット - カスタムエージェント作成、インタラクティブClaude Codeセッション管理、セキュアバックグラウンドエージェント実行など
- [Claude Code Templates (aitmpl.com)](https://github.com/davila7/claude-code-templates) - Claude Code設定・監視用CLIツール
- [10x-Tool-Calls](https://github.com/perrypixel/10x-Tool-Calls) - 月間AIコーディングツール呼び出しの価値を最大化し、より少ないリクエストでより多くを実現するために設計された軽量ルールファイル
- [zcc](https://github.com/Git-on-my-level/zcc) - Claude Codeを基本的なAIアシスタントからプロジェクト認識・コンテキストインテリジェントな開発パワーハウスに変換
- [Aegis](https://github.com/BuildSomethingAI/aegis-framework) - AI機能と構造化プロジェクト管理を組み合わせた強力なフレームワーク
- [SuperClaude Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) - 専門コマンド、認知ペルソナ、開発手法でClaude Codeを強化する設定フレームワーク
- [Claude Code Custom Slash Commands](https://github.com/qdhenry/Claude-Command-Suite) - 一般的なソフトウェア開発業務向け専門ワークフローを提供するClaude Code向けカスタムスラッシュコマンド
- [ClaudeAssistant](https://github.com/itodobien/ClaudeAssistant) - AIコーディングアシスタント
- [Clean-Coder-AI](https://github.com/Grigorij-Dudnik/Clean-Coder-AI) - 行動前に思考するAIコーダー
- [CursorCore](https://github.com/TechxGenus/CursorCore) - あらゆるものの調整によるプログラミング支援
- [cursor-deepseek](https://github.com/danilofalcao/cursor-deepseek) - Cursor IDEのComposerでDeepSeekとOpenRouterの言語モデル使用を可能にする専用設計の高性能HTTP/2対応プロキシサーバー
- [DeepEvolve](https://github.com/liugangcode/deepevolve) - Deep ResearchとAlphaEvolveを用いて異なる科学分野での新アルゴリズム発見向け研究・コーディングエージェント
- [cursorrules 「v5」](https://github.com/kinopeee/cursorrules) - Cursor Agent に最適化されたカスタムインストラクションです
- [.windsurfrules 'v5'](https://github.com/kinopeee/windsurfrules) - Windsurf向けカスタム指示ファイル（.windsurfrules）。Windsurf Cascade向けcursorrulesの最適化適応
- [deepseek-r1-ext](https://github.com/fvciprian/deepseek-r1-ext) - DeepSeek-R1モデルのチャットインターフェースを提供
- [roocode-memorybank-optimized](https://github.com/shipdocs/roocode-memorybank-optimized) - Claude ProとOpenRouterを組み合わせてトークンコストを削減するVS Code向けリーンRoo Code設定
- [RooFlow](https://github.com/GreatScottyMac/RooFlow) - ☢️Footgun Power☢️による強化メモリーバンクシステム 5つの統合モードとシステムレベルカスタマイゼーションを持つ次世代メモリーバンクシステム
- [Roo Commander](https://github.com/jezweb/roo-commander) - 👑 Roo Commanderによって調整され、VS Code上のRoo Codeを動力とする、エディタ内に仮想的で専門的なソフトウェア開発チームを持つようなもの
- [Vibe](https://github.com/wyojustin/Vibe) - プロジェクトでの増分コードパッチの適用、レビュー、管理を行い、会話プロンプトによるAI駆動パッチ生成も統合するインタラクティブツール
- [RA.Aid](https://github.com/ai-christianson/RA.Aid) - LangChain ReActエージェントループ内でaiderを統合する強力なAI駆動コマンドラインツール
- [ManasAI](https://github.com/yashpokar/ManasAI) - 業務自動化、コード品質向上、生産性向上を目指す
- [Noema-Declarative-AI](https://github.com/AlbanPerli/Noema-Declarative-AI) - LLM制御の宣言的方法
- [> CLAUDER](https://github.com/blueraai/clauder) - Claude Code向けのスーパーチャージドツールキットとセーフティファースト設定。AI支援開発の堅牢な基盤を提供しつつ、任意のプロジェクトやワークフローに簡単に設定・拡張可能
- [Claude Code Subagents Collection](https://github.com/wshobson/agents) - Claude Code向けの専門AIサブエージェントの包括的コレクション。ドメイン固有の専門知識で開発ワークフローを強化
- [CCPlugins](https://github.com/brennercruvinel/CCPlugins) - 実際に時間を節約する最高のClaude Codeフレームワーク。毎回の会話で「シニアエンジニアのように振る舞ってください」と入力するのにうんざりした開発者が構築
- [knowhub](https://github.com/yujiosaka/knowhub) - AIコーディングエージェントのナレッジファイル（ルール、テンプレート、ガイドライン）をプロジェクト全体で同期
- [Claude Code Commands & Tasks (CCCT)](https://github.com/IgorWarzocha/CCCT) - ユニバーサルスラッシュコマンドと統合タスク管理を備えたClaude Code向けプロフェッショナルワークフローシステム
- [Polka Codes](https://github.com/polka-codes/polka-codes) - 自然言語のやりとりによってコードの記述、改善、保守を支援する強力なTypeScriptベースのAIコーディングアシスタントフレームワーク
- [Tsumiki](https://github.com/classmethod/tsumiki) - AI駆動開発のフレームワーク。AIを活用した効率的な開発プロセスを提供し、要求定義から実装までを支援
- [AI Governor Framework](https://github.com/Fr-e-d/AI-Governor-Framework) - AI駆動コードの基盤フレームワーク！AIコーディングアシスタントをアーキテクチャとコーディング標準を尊重する規律あるプロジェクト認識エンジニアリングパートナーに変換
- [ZCF](https://github.com/UfoMiao/zcf) - バイリンガルサポート、インテリジェントエージェントシステム、パーソナライズされたAIアシスタントを備えたClaude Code向けゼロコンフィグ、ワンクリックセットアップ
- [Claude Code Guardrails](https://github.com/wangbooth/Claude-Code-Guardrails) - ブランチ保護、自動チェックポイント、安全なコミットスカッシュによって偶発的なコード損失を防ぐClaude Code向け保護フック
