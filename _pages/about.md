---
permalink: /
title: "Jie Lu 陆杰"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
@keyframes blink {
  0% { opacity: 1; }
  50% { opacity: 0.3; }
  100% { opacity: 1; }
}

.new-badge {
  display: inline-block;
  color: #F7B32B;
  font-weight: bold;
  animation: blink 1.5s infinite;
}

.news-container .news-item:nth-child(n+4) {
  display: none;
}

.news-container.expanded .news-item {
  display: block;
}

.news-toggle {
  color: #0366d6;
  cursor: pointer;
  margin-top: 10px;
  display: inline-block;
  font-weight: 500;
}

.news-toggle:hover {
  text-decoration: underline;
}
/* 增加页面宽度的CSS */
@media (min-width: 925px) {
  .page {
    float: right;
    width: 85%;
    margin-right: 0;
    padding-right: 0;
  }
  
  .page__inner-wrap {
    margin-right: 0;
    width: 100%;
  }
}

@media (min-width: 1280px) {
  #main {
    max-width: 1600px;
    margin-left: auto;
    margin-right: auto;
  }
}
</style>

# About Me 👋

I am an Associate Professor at The Institute of Computing Technology of the Chinese Academy of Sciences. My research interests include software security and program analysis, with a focus on improving software reliability and security through advanced program analysis techniques.

## News 📰
<div class="news-container">
  <div class="news-item">* <span class="new-badge">NEW!</span> April 2025: Won ACM SIGSOFT Distinguished Paper Award at Internetware 2025</div>
  <div class="news-item">* <span class="new-badge">NEW!</span> April 2025: One paper is accepted by USENIX Security2025</div>
  <div class="news-item">* <span class="new-badge">NEW!</span> April 2025: One paper is accepted by CCS2025</div>
  <div class="news-item">* <span class="new-badge">NEW!</span> April 2025: One paper is accepted by FSE2025</div>
  <div class="news-item">* <span class="new-badge">NEW!</span> April 2025: One paper is accepted by internetware2025</div>
</div>
<div class="news-toggle" onclick="toggleNews(this)">Show more news...</div>

<script>
function toggleNews(element) {
  const container = document.querySelector('.news-container');
  container.classList.toggle('expanded');
  
  if (container.classList.contains('expanded')) {
    element.textContent = 'Show fewer news...';
  } else {
    element.textContent = 'Show more news...';
  }
}
</script>

---

## Research Interests 🔬

My research focuses on:

- **Software Security**: Vulnerability detection and prevention in open-source software
- **Program Analysis**: Static/dynamic analysis techniques, context-sensitive pointer analysis
- **Cloud Systems**: Distributed system security, crash-recovery and concurrency bug detection

---

## Recruiting 🎓

I'm looking for motivated **PhD candidates** 🔍, **Master students** 📚, and **Research interns** 🌱 interested in software security and program analysis.

For details, visit our [research group page](https://ict-pag.github.io/) or [application information](https://ict-pag.github.io/joining/), or contact me directly.

---

## Selected Publications 📚


### 2025
- **Reviving Discarded Vulnerabilities: Exploiting Previously Unexploitable Linux Kernel Bugs Through Control Metadata Fields**  
  Hao Zhang, Jie Lu, Shaomin Chen, Tianshuo Han, Bolun Zhang, Jian Liu, Xiaorui Gong  
  *ACM Conference on Computer and Communications Security (CCS'25)*
- **VulPA: Detecting Semantically Recurring Vulnerabilities with Multi-Object Typestate Analysis**  
  Liqing Cao, Haofeng Li, Chenghang Shi, Jie Lu, Haining Meng, Lian Li, Jingling Xue  
  *ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE'25)*

- **SLVHound: Static Detection of Session Lingering Vulnerabilities in Modern Java Web Applications**🏆    
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
  Haining Meng, Haofeng Li, Jie Lu, Chenghang Shi, Liqing Cao, Lian Li, lin Gao  
  *International Conference on Engineering of Complex Computer Systems (ICECCS'24)*

### 2023
- **Two Birds with One Stone: Multi-Derivation for Fast Context-Free Language Reachability Analysis**  
  Chenghang Shi, Haofeng Li, Yulei Sui, Jie Lu, Lian Li, Jingling Xue  
  *IEEE/ACM International Conference on Automated Software Engineering (ASE'23)*

### 2022
- **Detecting Missing-Permission-Check Vulnerabilities in Distributed Cloud Systems** 🏆  
  Jie Lu, Haofeng Li, Chen Liu, Lian li, Kun Cheng  
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

### 2018-2020
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
  Jie Lu, Feng Li, Lian Li and Xiaobing Feng   
  *ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE'18)*

[📚 View Complete Publication List](https://lujie.ac.cn/publications/)
