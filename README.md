<h1 align="center">Raj Kumar</h1>
<p align="center">
  <strong>Software Development Engineer | Bengaluru, India</strong>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rajkumarpendem/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:rajkumarpendem611@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/raja611"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>

---

### About

Software Development Engineer with hands-on experience building **low-latency, high-throughput systems** and **developer tooling**. I focus on writing performance-critical code where every nanosecond counts — from cache-line-optimized data structures to custom memory allocators. NIT Puducherry alumnus, currently based in Bengaluru.

---

### Interesting Things i worked on

- **Systems & Performance Engineering** — Built an order matching engine processing **26M orders/sec** (~38 ns/order) with sub-microsecond p50 latency. Deep experience with cache optimization, lock-free design, memory arenas, and compiler-guided tuning (PGO, LTO).
- **Developer Tooling** — Created VS Code extensions used by developers for AI-assisted coding and codebase dependency visualization.
- **AI & RAG Applications** — Built a PDF chatbot with OpenAI embeddings, LlamaIndex, and Flask — optimized to controllable overhead with in-memory caching and batch embeddings.
- **Full-Stack Fundamentals** — Comfortable across the stack, from low-level C++ to web applications with HTML/CSS/JS.
- **Open Source Contributor** — Active in open-source projects; shipped published VS Code extensions.

---

### Core Skills

<p>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++20">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/HTML/CSS-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML/CSS">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/VS_Code_API-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" alt="VS Code API">
  <img src="https://img.shields.io/badge/Multithreading-333333?style=flat-square" alt="Multithreading">
  <img src="https://img.shields.io/badge/Cache_Optimization-333333?style=flat-square" alt="Cache Optimization">
  <img src="https://img.shields.io/badge/Memory_Management-333333?style=flat-square" alt="Memory Management">
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/LlamaIndex-6C3483?style=flat-square" alt="LlamaIndex">
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI">
  <img src="https://img.shields.io/badge/RAG-333333?style=flat-square" alt="RAG">
</p>

---

### Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/raja611/Order-Matching-Engine">Order Matching Engine</a></h3>
      <p><code>C++20</code> <code>Low Latency</code> <code>Systems Programming</code></p>
      <p>Ultra low-latency CLOB matching engine — <strong>26M orders/sec</strong> single-thread, <strong>48 ns</strong> p50 latency, <strong>1B+ orders/sec</strong> aggregate on multi-core. Built with flat-array price levels (O(1) lookup), intrusive linked lists, 32-byte cache-optimized structs, arena allocators, core pinning, and PGO.</p>
      <p><sub>Techniques: cache-line packing, zero-allocation hot path, branch prediction hints, SIMD-width structs, profile-guided optimization</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/raja611/PDF-Chatbot">PDF Chatbot</a></h3>
      <p><code>Python</code> <code>Flask</code> <code>RAG</code> <code>LlamaIndex</code></p>
      <p>Flask-based chatbot that lets you upload PDF or DOCX files and ask questions about their content using OpenAI embeddings and LlamaIndex. Optimized with in-memory index caching (<strong>250x</strong> engine load speedup), batch embeddings (<strong>2x</strong> faster uploads), and sub-millisecond controllable overhead.</p>
      <p><sub>Skills: RAG pipelines, vector search, embedding optimization, Flask, LlamaIndex, performance benchmarking</sub></p>
    </td>
    <td width="50%" valign="top">
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/raja611/ChatGpt-in-Vscode">ChatGPT in VS Code</a></h3>
      <p><code>TypeScript</code> <code>VS Code API</code> <code>AI Integration</code></p>
      <p>AI-powered chatbot integrated into VS Code, letting developers query ChatGPT for code generation, debugging help, and documentation — all without context-switching away from their editor.</p>
      <p><sub>Skills: API integration, conversational UI, extension lifecycle management</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/raja611/import-tree-view-vscode-extension">Import Tree View — VS Code Extension</a></h3>
      <p><code>TypeScript</code> <code>VS Code API</code> <code>Developer Tools</code></p>
      <p>A VS Code extension that renders the full hierarchical import tree of any file in a codebase. Helps developers understand, navigate, and refactor complex dependency graphs without leaving the editor.</p>
      <p><sub>Skills: AST parsing, tree data structures, VS Code extension API, UX for developer tools</sub></p>
    </td>
  </tr>
</table>

---

### Highlights

| | |
|---|---|
| **26M orders/sec** | Single-thread matching throughput on commodity hardware — Order Matching Engine |
| **48 ns p50** | Median order-to-trade latency, faster than an L3 cache miss — Order Matching Engine |
| **217x speedup** | Cancel throughput improvement through data structure redesign — Order Matching Engine |
| **250x faster** | Engine load optimization in PDF Chatbot — from 25ms to 0.1ms with in-memory caching |
| **2 VS Code extensions** | Published developer tools for AI coding and dependency visualization |
| **NIT Puducherry** | B.Tech graduate |

---

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=raja611&theme=default&hide_border=true" alt="GitHub Streak">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rajkumarpendem/"><img src="https://img.shields.io/badge/Let's_Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>
