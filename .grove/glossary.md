# Glossary

| Term | Definition | Source |
| --- | --- | --- |
| product-contract | The explicit supported hardware, artifacts, features, and observable behavior that implementation and evidence must satisfy. | `AGENTS.md` and product documentation. |
| tp2 | Tensor parallel execution over exactly two CUDA devices in one process and one resident model instance. | `tp2/master:docs/maintainer/tp2-yarn-1m.md`. |
| nvlink | NVIDIA peer interconnect used by the local RTX 3090 pair for direct cross-device transfers. | `nvidia-smi topo -m` and `nvidia-smi nvlink -s`. |
| shard-map | The compile-time assignment of model tensor extents and state dimensions to TP ranks. | `tp2/master:docs/maintainer/tp2-yarn-1m.md`. |
