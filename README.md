<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:141B2D,100:C8963E&height=180&section=header&text=Parrva%20Shah&fontSize=58&fontColor=EFEAE1&animation=fadeIn&fontAlignY=40&desc=Systems%20software%20%E2%80%A2%20CSE%20%40%20IIT%20Jodhpur&descAlignY=62&descSize=16" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Space+Mono&size=16&pause=1200&color=C8963E&center=true&vCenter=true&width=760&lines=Rollback+engines%2C+event+schedulers%2C+SIMD+kernels;C%2B%2B20+%2B+AVX2+%7C+Postgres+%2B+Kafka+%7C+Flex+%26+Bison;Open+to+Summer+2027+SWE+%26+quant+internships)](https://git.io/typing-svg)

<a href="https://parrva-shah.github.io"><img src="https://img.shields.io/badge/Portfolio-C8963E?style=flat-square&logo=githubpages&logoColor=141B2D"/></a>
&nbsp;
<a href="https://www.linkedin.com/in/parrva-shah-547169323/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
&nbsp;
<a href="https://codeforces.com/profile/ParrvaShah"><img src="https://img.shields.io/badge/Codeforces-Specialist-1F8ACB?style=flat-square&logo=codeforces&logoColor=white"/></a>
&nbsp;
<a href="https://leetcode.com/u/Parrva_Shah/"><img src="https://img.shields.io/badge/LeetCode-200%2B%20solved-FFA116?style=flat-square&logo=leetcode&logoColor=black"/></a>
&nbsp;
<a href="mailto:pcshah2006@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>

</div>

---

<table>
<tr>
<td width="60%" valign="top">

### about

Third-year CSE at **IIT Jodhpur**, drawn to the unglamorous half of a system.

I build the layer other code depends on being correct: a rollback engine that makes writes to a live PostgreSQL database reversible, a system design tester that runs your architecture under load and injected failures before you build it, and a C++20 quant finance library whose hot loop has no branches in it at all.

That usually means writing the interesting part myself rather than importing it — my own scheduler, my own inverse-query generation, my own AVX2 kernels. Slower than reaching for a framework, and the only way I've found to learn where a design actually breaks.

Currently coordinating the **Quant Club** and building with **DevlUp Labs**.

</td>
<td width="40%" valign="top">

### at a glance

| | |
|:--|--:|
| CGPA | **9.40 / 10** |
| Codeforces | **Specialist** |
| LeetCode | **200+ solved** |
| Inter IIT 14.0, quant | **8 / 23** |
| JEE Advanced 2024 | **AIR 2720** |
| Class 12, CBSE | **97%** |

**Looking for** a Summer 2027 internship — software engineering or quantitative development.

**Reach me** at [pcshah2006@gmail.com](mailto:pcshah2006@gmail.com)

</td>
</tr>
</table>

---

### tech stack

<div align="center">

**languages**

<img src="https://skillicons.dev/icons?i=cpp,c,python,ts,bash&theme=dark"/>
<br/><br/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/STL-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>

<br/>

**backend and infra**

<img src="https://skillicons.dev/icons?i=django,fastapi,postgres,docker,git,linux,react,tailwind&theme=dark"/>
<br/><br/>
<img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS%20S3-FF9900?style=for-the-badge&logo=amazons3&logoColor=white"/>
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white"/>
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white"/>
<img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>

<br/>

**low level and quant**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow&theme=dark"/>
<br/><br/>
<img src="https://img.shields.io/badge/AVX2%20intrinsics-141B2D?style=for-the-badge&logo=intel&logoColor=C8963E"/>
<img src="https://img.shields.io/badge/Flex%20%26%20Bison-141B2D?style=for-the-badge&logoColor=C8963E"/>
<img src="https://img.shields.io/badge/nanobind-141B2D?style=for-the-badge&logo=python&logoColor=C8963E"/>
<img src="https://img.shields.io/badge/Struct--of--arrays-141B2D?style=for-the-badge&logoColor=C8963E"/>
<br/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>

</div>

### projects

**[ONITRO](https://github.com/devlup-labs/ONITRO)** &nbsp;·&nbsp; `C++20` `AVX2` `nanobind`
Quant finance library closing the gap between QuantLib and ad-hoc Python. Branch-free, allocation-free kernels over struct-of-arrays; four doubles per instruction. Converged SIMD lanes are masked off instead of dropping to scalar. *Architected it, lead-mentoring the team.*

**[SimRUN](https://github.com/devlup-labs/simrun)** &nbsp;·&nbsp; `C++` `DSL` `Discrete-event`
Draw a system architecture, run it under load with failures injected, watch how it degrades before building any of it. 20-opcode component model over a timestamp-ordered scheduler. *Built the simulation core and the topology DSL.*

**[WEAVE-DB](https://github.com/IshatV412/dbworkbench)** &nbsp;·&nbsp; `Django` `FastAPI` `Kafka`
Version control for a live PostgreSQL database. Inverse-query generation makes writes reversible; anchoring on the nearest snapshot either side of the target halves worst-case replay. *Backend lead, team of four.*

**[Custom Language & Interpreter](https://github.com/IshatV412/ICS_Project)** &nbsp;·&nbsp; `C` `Flex` `Bison`
A language with its own syntax and datatypes. *I wrote the lexer and the parser that builds the AST; the team wrote the tree-walking interpreter.*

**[Maze Pathfinding Visualiser](https://github.com/Parrva-Shah/Maze_Pathfinding_Algorithms)** &nbsp;·&nbsp; `C++17` `SFML`
Five search algorithms raced across generated mazes, with a benchmark screen comparing runtime, nodes explored and path length.

**[The Hive](https://github.com/divyansh-1009/The-Hive)** &nbsp;·&nbsp; `Node` `pgvector` `Kotlin`
Browser extension that classifies your current tab by vector search into a productivity score, with idle and minimum-time checks so the score can't be farmed.

---

<div align="center">

[**Portfolio**](https://parrva-shah.github.io) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/parrva-shah-547169323/) &nbsp;·&nbsp; [Codeforces](https://codeforces.com/profile/ParrvaShah) &nbsp;·&nbsp; [LeetCode](https://leetcode.com/u/Parrva_Shah/) &nbsp;·&nbsp; [pcshah2006@gmail.com](mailto:pcshah2006@gmail.com)

</div>
