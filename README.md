# awesome-reference

个人整理的 AI 工程与大模型参考资料库，当前主要包含两类内容：

- `claude/`：Claude Code 源码分析、逆向与深度拆解资料。
- `ft-rag/`：Fine-tuning、RAG、检索、知识蒸馏、幻觉检测与记忆系统相关论文。

## 目录

- [Claude Code](#claude-code)
- [FT / RAG / Retrieval](#ft--rag--retrieval)
- [目录结构](#目录结构)

## Claude Code

### 源码与逆向资料

- [instructkr/claude-code](https://github.com/instructkr/claude-code) — 源码还原
- [ChinaSiro/claude-code-sourcemap](https://github.com/ChinaSiro/claude-code-sourcemap) — sourcemap 提取
- [pengchengneo/Claude-Code](https://github.com/pengchengneo/Claude-Code) — 源码解析
- [sanbuphy/claude-code-source-code](https://github.com/sanbuphy/claude-code-source-code) — 源码解读
- [oboard/claude-code-rev](https://github.com/oboard/claude-code-rev)
- [Clearzero22/Claude-Code-rev](https://github.com/Clearzero22/Claude-Code-rev) — 逆向工程
- [cch123/claude-controller](https://github.com/cch123/claude-controller) — 手柄声控 Claude Code

### PDF

| 资料 | 说明 |
| --- | --- |
| [claude-code-deep-dive-xelatex.pdf](claude/claude-code-deep-dive-xelatex.pdf) | Claude Code 源码深度挖掘报告 |
| [ClaudeCode源码泄露，10w字逐模块拆解报告.pdf](claude/ClaudeCode源码泄露，10w字逐模块拆解报告.pdf) | Claude Code 模块级拆解报告 |

## FT / RAG / Retrieval

| 序号 | 资料 | 主题 |
| --- | --- | --- |
| 01 | [Qwen3 Technical Report](ft-rag/01_Qwen3_Technical_Report_2505.09388.pdf) | 模型技术报告 |
| 02 | [LoRA: Low-Rank Adaptation of Large Language Models](ft-rag/02_LoRA_2106.09685.pdf) | 参数高效微调 |
| 03 | [Fine-Tuning or Retrieval?](ft-rag/03_Ovadia_FineTuning_or_Retrieval_EMNLP2024.pdf) | 微调与检索增强对比 |
| 04 | [Fine Tuning vs. Retrieval Augmented Generation for Less Popular Knowledge](ft-rag/04_Soudani_FT_vs_RAG_LessPopular_2403.01432.pdf) | 长尾知识问答 |
| 05 | [BM25 and Beyond](ft-rag/05_Robertson_BM25_and_Beyond_2009.pdf) | 经典词项检索 |
| 06 | [BM25 Reproducibility](ft-rag/06_Kamphuis_BM25_Reproducibility_ECIR2020.pdf) | 检索实验复现 |
| 07 | [Rethinking Chunk Size for Long-Document Retrieval](ft-rag/07_Rethinking_Chunk_Size_2505.21700.pdf) | 长文档切块策略 |
| 08 | [A Survey on Knowledge Distillation of Large Language Models](ft-rag/08_Survey_KD_of_LLMs_2402.13116.pdf) | LLM 知识蒸馏综述 |
| 09 | [Winning Big with Small Models](ft-rag/09_Winning_Big_Small_Models_2502.19545.pdf) | 小模型、蒸馏与自训练 |
| 10 | [A Closer Look at the Limitations of Instruction Tuning](ft-rag/10_Kung_Limitations_InstructionTuning_2402.05119.pdf) | 指令微调局限 |
| 11 | [The Illusion of Progress](ft-rag/11_Illusion_of_Progress_2508.08285.pdf) | 幻觉检测评估 |
| 12 | [MemOS: A Memory OS for AI System](ft-rag/12_MemOS_MemoryOS_2507.03724.pdf) | AI 记忆操作系统 |
| 13 | [MemOS: Operating System for Memory-Augmented Generation](ft-rag/13_MemOS_OS_for_MAG_2505.22101.pdf) | 记忆增强生成 |
| 14 | [LLM Agent Memory Survey](ft-rag/14_Wang_LLM_Agent_Memory_Survey_2404.13501.pdf) | Agent 记忆综述 |

## 目录结构

```text
.
├── claude/
│   ├── ClaudeCode源码泄露，10w字逐模块拆解报告.pdf
│   └── claude-code-deep-dive-xelatex.pdf
├── ft-rag/
│   ├── 01_Qwen3_Technical_Report_2505.09388.pdf
│   ├── 02_LoRA_2106.09685.pdf
│   ├── ...
│   └── 14_Wang_LLM_Agent_Memory_Survey_2404.13501.pdf
└── README.md
```
