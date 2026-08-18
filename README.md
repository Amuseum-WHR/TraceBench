# TRACE-Bench

**Decomposing and Diagnosing Multi-Reference Image Generation**

Haoran Wang<sup>&#42;</sup>, Chaofan Ma<sup>&#42;</sup>, Ran Yi<sup>†</sup>,
Lizhuang Ma<sup>‡</sup>

Shanghai Jiao Tong University

<sup>&#42;</sup> Equal contribution. <sup>†</sup> Project lead.
<sup>‡</sup> Corresponding author.

[![Project Page](https://img.shields.io/badge/Project-Page-5b9a22?labelColor=555555)](https://amuseum-whr.github.io/TraceBench/)
[![Paper](https://img.shields.io/badge/Paper-PDF-d64545?logo=adobeacrobatreader&logoColor=white&labelColor=555555)](https://arxiv.org/pdf/2608.16765)
[![arXiv](https://img.shields.io/badge/arXiv-2608.16765-b31b1b?logo=arxiv&logoColor=white&labelColor=555555)](https://arxiv.org/abs/2608.16765)
[![Hugging Face Daily Papers](https://img.shields.io/badge/Hugging%20Face-Daily%20Papers-FFD21E?logo=huggingface&logoColor=FFD21E&labelColor=555555)](https://huggingface.co/papers/2608.16765)
[![ACM MM 2026](https://img.shields.io/badge/ACM%20MM-2026-0085CA?logo=acm&logoColor=white&labelColor=555555)](https://2026.acmmm.org/)
[![GitHub](https://img.shields.io/badge/GitHub-TRACE--Bench-1683bd?logo=github&logoColor=white&labelColor=555555)](https://github.com/Amuseum-WHR/TraceBench)

TRACE-Bench is a capability-oriented benchmark for evaluating and diagnosing
multi-reference image generation. Instead of grouping examples into predefined
task categories, it decomposes each request into four atomic operators:
**Anchor** (*f*), **Disentangle** (*g*), **Apply** (⊕), and **Compose** (*C*).
The resulting compositional formula controls case complexity and maps directly
to operator-level evaluation criteria, making model failures traceable.

TRACE-Bench contains approximately 1,600 evaluation cases across slot counts
1–8, constructed from 631 formula templates and around 4,000 reference images.
It evaluates nine leading models and introduces diagnostic-tree analysis for
recursively localizing failures.

## Release

This is the official TRACE-Bench repository. The benchmark and related resources will be released here. The repository currently hosts the
[project page](https://amuseum-whr.github.io/TraceBench/).

## Citation

TRACE-Bench is accepted to **ACM Multimedia 2026 (ACM MM 2026)**. If you find
this work useful, please cite:

```bibtex
@inproceedings{wang2026tracebench,
  title  = {{TRACE-Bench}: Decomposing and Diagnosing Multi-Reference Image Generation},
  author = {Wang, Haoran and Ma, Chaofan and Yi, Ran and Ma, Lizhuang},
  booktitle = {Proceedings of the 34th ACM International Conference on Multimedia},
  year   = {2026}
}
```
