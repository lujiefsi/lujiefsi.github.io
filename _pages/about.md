---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.new-badge {
  display: inline-block;
  color: #9a6700;
  font-weight: 700;
}

.news-container {
  margin-bottom: 0;
  padding-left: 1.25rem;
}

.news-container .news-item:nth-child(n+6) {
  display: none;
}

.news-container.expanded .news-item {
  display: list-item;
}

.news-toggle {
  appearance: none;
  background: transparent;
  border: 0;
  color: #0366d6;
  cursor: pointer;
  display: inline-block;
  font: inherit;
  font-weight: 500;
  margin-top: 0.5rem;
  padding: 0;
}

.news-toggle:hover,
.news-toggle:focus-visible {
  text-decoration: underline;
}
</style>

# About Me 👋

I am an Associate Professor at the Institute of Computing Technology, Chinese Academy of Sciences (ICT, CAS). My research focuses on **software and systems security**, particularly the security and reliability of cloud systems. My work uses program analysis and log analysis and increasingly incorporates LLM-based agents to discover vulnerabilities and diagnose failures in complex software systems and cloud infrastructure.

## News 📰
<ul id="news-list" class="news-container">
  <li class="news-item"><span class="new-badge">NEW!</span> July 2026: SteadiCam was accepted to NDSS 2027.</li>
  <li class="news-item"><span class="new-badge">NEW!</span> June 2026: SHCRGuard was accepted for publication in the Journal of Systems and Software (JSS).</li>
  <li class="news-item"><span class="new-badge">NEW!</span> June 2026: Hermes was accepted to ASE 2026.</li>
  <li class="news-item"><span class="new-badge">NEW!</span> April 2026: THESEUS was accepted to CCS 2026.</li>
  <li class="news-item"><span class="new-badge">NEW!</span> March 2026: LifeFuzz was accepted to EuroSys 2026, SpecWeaver to FSE 2026, and our CFL-reachability paper to OOPSLA 2026.</li>
  <li class="news-item">December 2025: LoopSCC was accepted to ICSE 2026.</li>
  <li class="news-item">August 2025: Our paper on resource-injection vulnerabilities in Kubernetes was accepted to ASE 2025.</li>
  <li class="news-item">August 2025: MoYe was accepted to OOPSLA 2025.</li>
  <li class="news-item">July 2025: Our paper received an ACM SIGSOFT Distinguished Paper Award at Internetware 2025.</li>
  <li class="news-item">June 2025: One of our papers was accepted to USENIX Security 2025.</li>
  <li class="news-item">April 2025: One of our papers was accepted to CCS 2025.</li>
  <li class="news-item">April 2025: One of our papers was accepted to FSE 2025.</li>
  <li class="news-item">April 2025: One of our papers was accepted to Internetware 2025.</li>
</ul>
<button type="button" class="news-toggle" aria-expanded="false" aria-controls="news-list" onclick="toggleNews(this)">Show more news</button>

<script>
function toggleNews(button) {
  const container = document.getElementById(button.getAttribute('aria-controls'));
  const expanded = container.classList.toggle('expanded');

  button.setAttribute('aria-expanded', String(expanded));
  button.textContent = expanded ? 'Show less news' : 'Show more news';
}
</script>

---

## Research Interests 🔬

My research focuses on **software and systems security**, with particular emphasis on the security and reliability of cloud systems. My work draws on the following techniques:

- **Program Analysis**: Static and dynamic analyses for discovering security vulnerabilities and reliability bugs
- **Log Analysis**: Runtime log analysis for diagnosing failures, detecting anomalies, and understanding system behavior
- **LLM-based Agents for Systems**: Using LLM-based agents to support program understanding, security analysis, testing, and failure diagnosis

---

## Recruiting 🎓

I welcome inquiries from motivated prospective **PhD students**, **master's students**, and **research interns** interested in software and systems security, particularly cloud systems security and reliability. I am especially interested in students who want to apply program analysis, log analysis, or LLM-based agents to systems research.

If you are interested, please contact me directly: <img src="/images/contact.png" alt="Contact email address" width="240">

---

## Selected Publications 📚

*✉ Corresponding author; 🏆 award-winning paper.*

### 2027

- **Lights, Camera, Crash: Detecting Decoder Vulnerabilities in Video Conferencing Platforms**  
  Xiangru Liu, Jie Lu, Qingli Guo, Fangming Gu, Yingli Sun, Yue Xie, Lian Li, Kangjie Lu, Baoxu Liu, Xiaoqi Jia  
  *Network and Distributed System Security Symposium (NDSS'27)*

### 2026

- **Tracing the Invisible: Semantic Message Flow Discovery via Data Contracts in Real-World Distributed Systems**  
  Youlong Chen, Jie Lu<sup>✉</sup>, Mingtao Huang, Chenghang Shi, Yongheng Huang, Haofeng Li, Dong Liu, Mengna Ma, Yong Liu, Qinfen Hao, Lian Li<sup>✉</sup>  
  *IEEE/ACM International Conference on Automated Software Engineering (ASE'26)*

- **THESEUS: Smart Web Crawling via Resource-Guided Semantic Modeling**  
  Yongheng Huang, Chenghang Shi, Wenxiao Yao, Jie Lu<sup>✉</sup>, Haofeng Li, Youlong Chen, Dong Liu, Mengna Ma, Yong Liu, Qinfen Hao, Lian Li<sup>✉</sup>  
  *ACM Conference on Computer and Communications Security (CCS'26)*

- **SpecWeaver: End-to-End HTTP API Specification Inference Across Multi-Layer Routing in Production Web Services**  
  Wenbo Hu, Jie Lu, Jingting Chen, Feng Li, Chenghang Shi, Xiaonan Shi, Jinchen Wang, Wei Huo  
  *ACM SIGSOFT International Symposium on the Foundations of Software Engineering (FSE '26)*

- **Context-Free Language Reachability via Efficient Relation Chaining**  
  Chenghang Shi, Haofeng Li, Jie Lu, Lian Li  
  *ACM SIGPLAN Conference on Object-Oriented Programming, Systems, Languages, and Applications (OOPSLA '26)*

- **LifeFuzz: Lifecycle-Guided Fuzzing for Windows Driver Cross-Handler Vulnerabilities**  
  Chendong Yu, Yuekang Li, Yang Xiao, Jie Lu, Yeting Li, Defang Bo, Wei Huo  
  *EuroSys '26*

- **LoopSCC: Summarizing Complex Multi-branch Nested Loops via Periodic Oscillation Interval**  
  Kai Zhu, Haofeng Li, Kuihao Yan, Rongqing Wang, Jiaming Guo, Haoran Yang, Jie Lu, Lei Yu, Xiaoqi Jia, Chenkai Guo, Haichao Du, Qingjia Huang, Yamin Xie, Jing Tang  
  *International Conference on Software Engineering (ICSE'26)*

### 2025

- **Understanding Resource Injection Vulnerabilities in Kubernetes Ecosystems**  
  Defang Bo, Jie Lu, Feng Li, Jingting Chen, Jinchen Wang, Chendong Yu, Wei Huo  
  *IEEE/ACM International Conference on Automated Software Engineering (ASE'25)*

- **Fast Client-Driven CFL-Reachability via Regularization-Based Graph Simplification**  
  Chenghang Shi, Dongjie He, Haofeng Li, Jie Lu, Lian Li, and Jingling Xue  
  *ACM SIGPLAN Conference on Object-Oriented Programming, Systems, Languages, and Applications (OOPSLA'25)*

- **ZIPPER: Static Taint Analysis for PHP Applications with Precision and Efficiency**  
  Xinyi Wang, Yeting Li, Jie Lu, Shizhe Cui, Chenghang Shi, Qin Mai, Yunpei Zhang, Yang Xiao, Feng Li, Wei Huo  
  *USENIX Security Symposium (USENIX Security'25)*

- **Reviving Discarded Vulnerabilities: Exploiting Previously Unexploitable Linux Kernel Bugs Through Control Metadata Fields**  
  Hao Zhang, Jian Liu<sup>✉</sup>, Jie Lu<sup>✉</sup>, Shaomin Chen, Tianshuo Han, Bolun Zhang, Xiaorui Gong<br>
  *ACM Conference on Computer and Communications Security (CCS'25)*
  
- **VulPA: Detecting Semantically Recurring Vulnerabilities with Multi-Object Typestate Analysis**  
  Liqing Cao, Haofeng Li, Chenghang Shi, Jie Lu, Haining Meng, Lian Li, Jingling Xue  
  *ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE'25)*

- **SLVHound: Static Detection of Session Lingering Vulnerabilities in Modern Java Web Applications** 🏆<br>
  Haining Meng, Jie Lu<sup>✉</sup>, Yongheng Huang, Lian Li<sup>✉</sup>  
  *The 16th International Conference on Internetware (Internetware'25)*

- **Module-Aware Context Sensitive Pointer Analysis**  
  Haofeng Li, Chenghang Shi, Jie Lu, Lian Li, Zixuan Zhao  
  *International Conference on Software Engineering (ICSE'25)*

- **Sheep's Clothing, Wolf's Data: Detecting Server-Induced Client Vulnerabilities in Windows Remote IPC**  
  Fangming Gu, Qingli Guo<sup>✉</sup>, Jie Lu<sup>✉</sup>, Qinghe Xie, Beibei Zhao, Kangjie Lu, Hong Li, Xiaorui Gong  
  *Network and Distributed System Security Symposium (NDSS'25)*

### 2024
- **Detecting Broken Object-Level Authorization Vulnerabilities in Database-Backed Applications**  
  Yongheng Huang, Chenghang Shi, Jie Lu<sup>✉</sup>, Haofeng Li, Haining Meng, Lian Li<sup>✉</sup>  
  *ACM Conference on Computer and Communications Security (CCS'24)*
- **Boosting the Performance of Alias-Aware IFDS Analysis with CFL-based Environment Transformers**  
  Haofeng Li, Chenghang Shi, Jie Lu, Lian Li, Jingling Xue  
  *ACM SIGPLAN Conference on Object-Oriented Programming, Systems, Languages, and Applications (OOPSLA'24)*
- **Better Not Together: Staged Solving for Context-Free Language Reachability**  
  Chenghang Shi, Haofeng Li, Jie Lu, Lian Li  
  *International Symposium on Software Testing and Analysis (ISSTA'24)*
- **PEARL: A Multi-Derivation Approach to Efficient CFL-Reachability Solving**  
  Chenghang Shi, Haofeng Li, Yulei Sui, Jie Lu, Lian Li, Jingling Xue  
  *IEEE Transactions on Software Engineering (TSE'24)*
- **Generic Sensitivity: Generics-Guided Context Sensitivity for Pointer Analysis**  
  Haofeng Li, Tian Tan, Yue Li, Jie Lu, Haining Meng, Liqing Cao, Yongheng Huang, Lian Li, Lin Gao, Peng Di, Liang Lin, and ChenXi Cui  
  *IEEE Transactions on Software Engineering (TSE'24)*
- **Boosting the Performance of Multi-Solver IFDS Algorithms with Flow-sensitivity Optimizations**  
  Haofeng Li, Jie Lu, Haining Meng, Liqing Cao, Lian Li, Lin Gao  
  *International Symposium on Code Generation and Optimization (CGO'24)*
- **File Hijacking Vulnerability: The Elephant in the Room**  
  Chendong Yu, Yang Xiao, Jie Lu, Yuekang Li, Yeting Li, L. Li, Y. Dong, J. Wang, J. Shi, D. Bo, W. Huo  
  *Network and Distributed System Security Symposium (NDSS'24)*
- **AutoWeb: Automatically Inferring Web Framework Semantics via Configuration Mutation**  
  Haining Meng, Haofeng Li, Jie Lu, Chenghang Shi, Liqing Cao, Lian Li, Lin Gao<br>
  *International Conference on Engineering of Complex Computer Systems (ICECCS'24)*

### 2023
- **Two Birds with One Stone: Multi-Derivation for Fast Context-Free Language Reachability Analysis**  
  Chenghang Shi, Haofeng Li, Yulei Sui, Jie Lu, Lian Li, Jingling Xue  
  *IEEE/ACM International Conference on Automated Software Engineering (ASE'23)*

### 2022
- **Detecting Missing-Permission-Check Vulnerabilities in Distributed Cloud Systems** 🏆  
  Jie Lu, Haofeng Li, Chen Liu, Lian Li, Kun Cheng<br>
  *Best Paper Honorable Mention*  
  *ACM Conference on Computer and Communications Security (CCS'22)*
- **Generic Sensitivity: Customizing Context-Sensitive Pointer Analysis for Generics**  
  Haofeng Li, Jie Lu, Haining Meng, Liqing Cao, Yongheng Huang, Lian Li, Lin Gao  
  *ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE'22)*

### 2021
- **Exposing Vulnerable Paths: Enhance Static Analysis with Lightweight Symbolic Execution**  
  Guangwei Li, Ting Yuan, Jie Lu, Lian Li, Xiaobin Zhang, Xu Song, Kejun Zhang  
  *Asia-Pacific Software Engineering Conference (APSEC'21)*
- **Detecting TensorFlow Program Bugs in Real-World Industrial Environment**  
  Chen Liu, Jie Lu<sup>✉</sup>, Guangwei Li, Ting Yuan, Lian Li<sup>✉</sup>, Feng Tan, Jun Yang, Liang You, Jingling Xue  
  *IEEE/ACM International Conference on Automated Software Engineering (ASE'21)*
- **Scaling Up the IFDS Algorithm with Efficient Disk-assisted Computing**  
  Haofeng Li, Haining Meng, Hengjie Zheng, Liqing Cao, Jie Lu, Lian Li, Lin Gao  
  *International Symposium on Code Generation and Optimization (CGO'21)*
- **GoBench: a Benchmark Suite of Real-World Go Concurrency Bugs**  
  Ting Yuan, Guangwei Li, Jie Lu<sup>✉</sup>, Chen Liu, Lian Li<sup>✉</sup>, Jingling Xue  
  *International Symposium on Code Generation and Optimization (CGO'21)*

### 2018–2020
- **CloudRaid: Detecting Distributed Concurrency Bugs via Log Mining and Enhancement**  
  Jie Lu, Feng Li, Chen Liu, Lian Li, Xiaobing Feng, Jingling Xue  
  *IEEE Transactions on Software Engineering (TSE'20)*
- **CrashTuner: Detecting Crash-Recovery Bugs in Cloud Systems via Meta-Info Analysis**  
  Jie Lu, Chen Liu, Lian Li, Xiaobing Feng, Feng Tan, Jun Yang, Liang You  
  *ACM Symposium on Operating Systems Principles (SOSP'19)*
- **Understanding Node Change Bugs for Distributed Systems**  
  Jie Lu, Liu Chen, Lian Li and Xiaobing Feng  
  *IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER'19)*
- **CloudRaid: Hunting Concurrency Bugs in the Cloud via Log-Mining**  
  Jie Lu, Feng Li, Lian Li and Xiaobing Feng<br>
  *ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE'18)*

[📚 View Complete Publication List](https://lujie.ac.cn/publications/)
