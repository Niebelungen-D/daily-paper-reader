<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-30 ~ 2026-06-08
- 运行时间：2026-06-08 06:32:20 UTC
- 运行状态：成功
- 本次总论文数：6
- 精读区：3
- 速读区：3

### 今日简报（AI）
1. 本期日报聚焦于数据流提取与AI辅助漏洞发现，精读两篇高评分论文，速读涵盖二进制重写、多智能体攻防及AI安全基准。  
2. 最值得关注的方向：LLVM内核函数边界的数据流提取（《Beyond Edge Coverage》）可突破传统覆盖率瓶颈；NeuroLog结合大模型事实与Datalog/SMT实现可审计推理，开创神经符号漏洞发现新范式。  
3. 对普通读者：若你关注安全自动化，建议优先精读NeuroLog理解符号推理与LLM的协同逻辑；二进制安全从业者可速读PeAR框架获取静态重写思路，FORGE则展示多智能体在渗透测试中的潜力。
- 详情：[/20260530-20260608/README](/20260530-20260608/README)

### 精读区论文标签
1. [Beyond Edge Coverage: Per-Task Data-Flow Extraction at Kernel Function Boundaries via LLVM](/20260530-20260608/2606.00455v1-beyond-edge-coverage-per-task-data-flow-extraction-at-kernel-function-boundaries-via-llvm)  
   标签：评分：9.0/10、query:linux-kernel
   evidence：通过提取函数边界数据流改进内核模糊测试
2. [NeuroLog: Reasoning You Can Audit -- Neuro-Symbolic Vulnerability Discovery via LLM Facts, Datalog, and SMT](/20260530-20260608/2606.00669v1-neurolog-reasoning-you-can-audit----neuro-symbolic-vulnerability-discovery-via-llm-facts-datalog-and-smt)  
   标签：评分：9.0/10、query:linux-kernel
   evidence：适用于C/C++源码的漏洞发现方法，可应用于Linux内核
3. [NICE: A Framework for Declarative and Machine-Checkable Vulnerability Reproduction](/20260530-20260608/2606.00625v1-nice-a-framework-for-declarative-and-machine-checkable-vulnerability-reproduction)  
   标签：评分：8.0/10、query:linux-kernel
   evidence：使用NixOS虚拟机提供可复现的漏洞利用环境

### 速读区论文标签
1. [PeAR: A Static Binary Rewriting Framework for Binary-Only Fuzzing](/20260530-20260608/2606.02126v1-pear-a-static-binary-rewriting-framework-for-binary-only-fuzzing)  
   标签：评分：7.0/10、query:linux-kernel
   evidence：适用于内核模块的纯二进制模糊测试框架
2. [FORGE: Multi-Agent Graduated Exploitation and Detection Engineering](/20260530-20260608/2606.03453v1-forge-multi-agent-graduated-exploitation-and-detection-engineering)  
   标签：评分：7.0/10、query:linux-kernel
   evidence：用于自动化漏洞利用生成和检测规则工程的多代理系统
3. [CyberGym-E2E: Scalable Real-World Benchmark for AI Agents' End-to-End Cybersecurity Capabilities](/20260530-20260608/2606.04460v1-cybergym-e2e-scalable-real-world-benchmark-for-ai-agents-end-to-end-cybersecurity-capabilities)  
   标签：评分：6.0/10、query:linux-kernel
   evidence：面向AI的端到端漏洞发现与PoC生成基准，可应用于Linux内核


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
