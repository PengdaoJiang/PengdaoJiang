# Agent and Research Systems

Execution, review and reproducible computation for long-running work.

## Main projects

| Project | Central problem | Code and architecture |
| --- | --- | --- |
| [Agent execution and evaluation](https://github.com/PengdaoJiang/agent-eval-evidence-kit) | Recover the correct task, control tool execution, and diagnose failures | [Phase/context control](https://github.com/PengdaoJiang/agent-eval-evidence-kit/blob/main/docs/phase-and-context.md) · [VM execution](https://github.com/PengdaoJiang/agent-eval-evidence-kit/blob/main/docs/vm-execution.md) |
| [Research review workbench](https://github.com/PengdaoJiang/document-review-workbench) | Keep source coverage, independent review and human decisions coherent through revisions | [Incremental review](https://github.com/PengdaoJiang/document-review-workbench/blob/main/docs/obligation-coverage.md) |
| [Reproducible experiment runtime](https://github.com/PengdaoJiang/point-in-time-research) | Resume valid compute units and preserve data, code and environment lineage | [Data and event runtime](https://github.com/PengdaoJiang/point-in-time-research/blob/main/docs/data-and-event-runtime.md) |
| [Versioned workflow state](https://github.com/PengdaoJiang/traceable-translation-pipeline) | Retain source authority and valid review results while recovering derived state | [Storage and recovery](https://github.com/PengdaoJiang/traceable-translation-pipeline/blob/main/docs/versioned-runtime.md) |

The repositories contain extracted working implementations with independent entry points. Their guides identify deployment dependencies, synthetic examples and the scope of historical validation.

<details>
<summary>Focused components</summary>

- [Long-text evidence registry](https://github.com/PengdaoJiang/longtext-evidence-registry): transactional extraction, stable entities and a React review interface.
- [Literary evidence compiler](https://github.com/PengdaoJiang/literary-evidence-library): source-grounded relationships, adjudication lineage and rebuildable SQLite.
- [Geometry comparison](https://github.com/PengdaoJiang/pcb-geometry-evidence): directed coverage and manufacturing-feature comparison.

</details>
