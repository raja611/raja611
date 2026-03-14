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

### What I Bring to the Table

- **Systems & Performance Engineering** — Built an order matching engine processing **26M orders/sec** (~38 ns/order) with sub-microsecond p50 latency. Deep experience with cache optimization, lock-free design, memory arenas, and compiler-guided tuning (PGO, LTO).
- **Developer Tooling** — Created VS Code extensions used by developers for AI-assisted coding and codebase dependency visualization.
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
      <h3><a href="https://github.com/raja611/import-tree-view-vscode-extension">Import Tree View — VS Code Extension</a></h3>
      <p><code>TypeScript</code> <code>VS Code API</code> <code>Developer Tools</code></p>
      <p>A VS Code extension that renders the full hierarchical import tree of any file in a codebase. Helps developers understand, navigate, and refactor complex dependency graphs without leaving the editor.</p>
      <p><sub>Skills: AST parsing, tree data structures, VS Code extension API, UX for developer tools</sub></p>
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
      <h3><a href="https://github.com/raja611/DPYProxy">DPYProxy</a></h3>
      <p><code>Python</code> <code>Networking</code> <code>Security</code></p>
      <p>Python proxy implementing Deep Packet Inspection (DPI) evasion mechanisms. Demonstrates low-level understanding of network protocols, packet manipulation, and privacy-preserving transport techniques.</p>
      <p><sub>Skills: socket programming, protocol analysis, network security</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/raja611/task-management-web-app">Task Management Web App</a></h3>
      <p><code>HTML</code> <code>CSS</code> <code>JavaScript</code></p>
      <p>A clean task management application built with vanilla web technologies. Features task CRUD operations, organization, and a responsive UI.</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/raja611/CalHub">CalHub</a></h3>
      <p><code>JavaScript</code> <code>HTML/CSS</code> <code>Open Source</code></p>
      <p>Open-source calculator project — forked, enhanced, and contributed back to the community.</p>
    </td>
  </tr>
</table>

---

### Highlights

| | |
|---|---|
| **26M orders/sec** | Single-thread matching throughput on commodity hardware |
| **48 ns p50** | Median order-to-trade latency — faster than an L3 cache miss |
| **217x speedup** | Cancel throughput improvement through data structure redesign |
| **2 VS Code extensions** | Published developer tools for AI coding and dependency visualization |
| **NIT Puducherry** | B.Tech graduate |

---

<p align="center">
  <em>Open to opportunities in systems programming, low-latency infrastructure, trading systems, and performance engineering.</em>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rajkumarpendem/"><img src="https://img.shields.io/badge/Let's_Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>
