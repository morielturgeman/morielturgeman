<p align="center">
  <img src="assets/hero.svg" alt="Moriel Turgeman — Agentic AI · Deep Learning · Computer Vision" width="880">
</p>

<p align="center">
  <a href="https://github.com/morielturgeman/Upscale"><b>UPscale</b></a>
  &nbsp;·&nbsp;
  <a href="#featured-work">Featured Work</a>
  &nbsp;·&nbsp;
  <a href="#tech-stack">Stack</a>
  &nbsp;·&nbsp;
  <a href="#education">Education</a>
  &nbsp;·&nbsp;
  <a href="#contact">Contact</a>
</p>

---

## About

Computer Science **B.Sc. graduate** with a specialization in Deep Learning, and an
**M.Sc. in Computer Science student at Ben-Gurion University of the Negev**.

I work on **Agentic AI and LLM systems**, **Deep Learning** and **Computer Vision** — and I build
them as production systems. That means the whole path: data and degradation modeling, architecture
and training, evaluation harnesses, then serving it behind a real API with persistence, tool
calling and retrieval underneath.

<p align="center"><img src="assets/divider.svg" alt="" width="880"></p>

## Featured Work

### UPscale — Deep Learning Video Restoration & 4× Super-Resolution

Recurrent video super-resolution built from the ground up in **PyTorch**: a BasicVSR-style
network with **SPyNet** optical-flow alignment and **bidirectional recurrent feature
propagation** over a **15-frame temporal window**, trained on **REDS** with synthetic
degradation modeling and fine-tuned on **H.264 codec-aware** degradations (V4) to close the
gap to real-world compressed footage.

<p align="center">
  <a href="https://github.com/morielturgeman/morielturgeman/raw/main/assets/upscale-demo.mp4">
    <img src="assets/upscale-demo.gif" alt="UPscale: 144p source versus ×4 restored output, side by side" width="880">
  </a>
</p>

<p align="center">
  <sub>Real 256×144 input · real 1024×576 model output — <a href="https://github.com/morielturgeman/morielturgeman/raw/main/assets/upscale-demo.mp4">watch the full clip in HD</a></sub>
</p>

<p align="center">
  <img src="assets/metrics.svg" alt="PSNR 28.87 dB versus 25.87 dB bicubic; SSIM 0.7986 versus 0.6918" width="880">
</p>

<sub>Evaluated on REDS4 over 430 evaluation windows. V3 → V4 codec fine-tuning adds +0.36 dB on compressed video.</sub>

**Stack** &nbsp;
`PyTorch` `BasicVSR` `SPyNet` `OpenCV` `FastAPI` `NumPy`

➜ &nbsp;**[View the repository](https://github.com/morielturgeman/Upscale)**

<br>

### LLM / RAG & Agentic Systems

Production-shaped AI systems beyond vision — retrieval pipelines and tool-using agents
served behind real APIs.

<table>
  <tr>
    <td valign="top" width="50%">
      <b>Retrieval</b><br>
      <sub>Document chunking · embeddings · semantic search over <code>PostgreSQL</code> + <code>pgvector</code></sub>
    </td>
    <td valign="top" width="50%">
      <b>Agents</b><br>
      <sub><code>LangGraph</code> state machines · tool calling · structured outputs</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>Serving</b><br>
      <sub><code>FastAPI</code> services · <code>Docker</code> · evaluation harnesses and regression tests</sub>
    </td>
    <td valign="top">
      <b>Applied</b><br>
      <sub>Multi-source incident triage · correlation and clustering · structured reports</sub>
    </td>
  </tr>
</table>

➜ &nbsp;**[AI Security Investigator](https://github.com/morielturgeman/Ai-Security-Investigator)** — multi-source incident correlation and triage with structured LLM outputs and an evaluation harness.

<p align="center"><img src="assets/divider.svg" alt="" width="880"></p>

## Tech Stack

<table>
  <tr>
    <td valign="top"><b>ML / AI</b></td>
    <td><code>PyTorch</code> <code>TensorFlow</code> <code>OpenCV</code> <code>LangGraph</code> <code>LangChain</code> — CNNs, GANs, RAG, LLMs, Computer Vision, Image Signal Processing (ISP)</td>
  </tr>
  <tr>
    <td valign="top"><b>Algorithms</b></td>
    <td>Conventional image processing · algorithm design · research &amp; analysis</td>
  </tr>
  <tr>
    <td valign="top"><b>Web &amp; Full-Stack</b></td>
    <td><code>FastAPI</code> <code>Node.js</code> <code>React</code> <code>PostgreSQL</code> <code>pgvector</code> <code>MongoDB</code> <code>REST APIs</code></td>
  </tr>
  <tr>
    <td valign="top"><b>Languages</b></td>
    <td><code>Python</code> <code>Java</code> <code>C++</code> <code>C</code> <code>JavaScript</code> <code>TypeScript</code> <code>SQL</code> <code>HTML</code> <code>CSS</code></td>
  </tr>
  <tr>
    <td valign="top"><b>Tooling</b></td>
    <td><code>Git</code> <code>Docker</code> <code>MCP</code></td>
  </tr>
</table>

<p align="center"><img src="assets/divider.svg" alt="" width="880"></p>

## Current Focus

`Deep Learning` &nbsp;`Computer Vision` &nbsp;`Video Restoration / Super-Resolution` &nbsp;`Generative Models` &nbsp;`LLM · RAG · Agentic Systems` &nbsp;`Production ML Engineering`

<p align="center"><img src="assets/divider.svg" alt="" width="880"></p>

## Education

**M.Sc. Computer Science** — Ben-Gurion University of the Negev · in progress

**B.Sc. Computer Science** — College of Management Academic Studies · 2023–2026 · GPA 92

<sub>Specialization in Deep Learning · Relevant coursework: Machine Learning · Deep Learning · Computer Vision</sub>

<sub>Colman Dev Club — collaborative full-stack projects with React, Node.js, Express and Git.</sub>

<p align="center"><img src="assets/divider.svg" alt="" width="880"></p>

## Contact

[LinkedIn](https://www.linkedin.com/in/morielturgeman) &nbsp;·&nbsp; [GitHub](https://github.com/morielturgeman) &nbsp;·&nbsp; [Email](mailto:morieltorgeman@gmail.com)

<sub><b>Build. Train. Evaluate. Ship.</b></sub>
