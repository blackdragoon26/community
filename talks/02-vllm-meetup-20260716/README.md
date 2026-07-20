# vLLM Meetup 2026 - Three Stages of vLLM Inference Cluster Optimization

**Date:** July 16, 2026
**Event:** vLLM Meetup
**Speaker:** 李孟轩 / Mengxuan Li (@archilitchi) - Dynamia CTO & HAMi Maintainer

## Topic

Are you making good use of your compute? An end-to-end evolution path for vLLM inference clusters, from "getting it to run" to "squeezing the hardware dry", broken into three incremental stages:

- **Phase 0**: vLLM as a process - fast single-node validation
- **Phase 1**: vLLM as a workload - standardized Kubernetes Deployment
- **Phase 2**: vLLM + PD disaggregation - decoupling Prefill and Decode (vLLM native P2pNcclConnector / Mooncake / LLM-D)
- **Phase 3**: vLLM + PD disaggregation + GPU virtualization - reclaiming idle compute in the memory-bandwidth-bound Decode stage with HAMi

## Presentation

- [Download PDF](./vllm-inference-cluster-optimization-limengxuan-20260716.pdf)

## Resources

- **Talk recap (English)**: [Are You Making Good Use of Your Compute?](https://project-hami.io/blog/vllm-meetup-shanghai-2026-recap/)
- **HAMi project**: https://github.com/Project-HAMi/HAMi
- **Dynamia**: https://dynamia.ai
- **vLLM**: https://github.com/vllm-project/vllm
- **LLM-D**: https://github.com/llm-d/llm-d
- **Mooncake**: https://github.com/kvcache-ai/Mooncake
