
<h1 align="center">Practical Crash Debugging Guide for Embedded RISC-V, First Edition</h1>

<p align="center">
  This is the code repository for
  <a href="https://www.packtpub.com/en-us/product/practical-crash-debugging-guide-for-embedded-risc-v-first-edition-9781806699353">Practical Crash Debugging Guide for Embedded RISC-V, First Edition</a>, published by Packt.
</p>

<h2 align="center">
  Debug kernel panics, exceptions, and system hangs using crash dumps and practical examples
</h2>

<p align="center">
  Austin Kim
</p>

<p align="center">
  <a href="https://www.amazon.com/Practical-Debugging-Embedded-RISC%E2%80%91V-RISCV-Based/dp/1806699354?crid=P11JESIF1W9P&dib=eyJ2IjoiMSJ9.1IGfwNLTMUcGU6-6vAU6KOsVYbNhx7_MwYLDIpDg26uUQ9O4kxdSz3JIfblXRIxrEC4dxmPC4WUVBAZZpcqCFrXLm3v422Fg4u3tbBsgTTcB2Q45tczEqC1142NmRj1AsV1Zj37hP7hhuak0VW0-wd_x-dQBXy397BX98zEmw-iLfcIsbiYXYgg-pe3-TZkS6HNys0UbgDNIjoQc09J9JjETenZqzkoOy6qixWnrc20.bUGPot5Rm1j5FNzhDt8RwxxsUJ7cy1AiyyYzHRGOLSk&dib_tag=se&keywords=Risc-V%2Bpractical%2Bdebugging%2Baustin%2Bkim&qid=1795075486&sprefix=risc-v%2Bpractical%2Bdebugging%2Baustin%2Bki%2Caps%2C500&sr=8-1&th=1">
    <img width="32px" alt="Amazon" title="Get your copy" src="https://cdn-icons-png.flaticon.com/512/15466/15466027.png"/>
  </a>
</p>

<details open>
  <summary><h2>About the book</h2></summary>

  <a href="https://www.packtpub.com/en-us/product/practical-crash-debugging-guide-for-embedded-risc-v-first-edition-9781806699353">
    <img src="https://content.packt.com/B36593/cover_image_small.jpg" alt="Practical Crash Debugging Guide for Embedded RISC-V, First Edition" height="256px" align="right">
  </a>

  When a RISC-V Linux system crashes, identifying the root cause can be challenging, especially when dealing with kernel panics, memory faults, or system hangs. Written by a Linux kernel engineer and author with over 15 years of industry experience, this book builds a strong foundation in crash debugging and guides you step by step through practical techniques for analyzing crash dumps and identifying the causes of system failures.

  This learning journey starts with the essentials of the crash debugging process, introducing common crash types, crash reproduction, and systematic troubleshooting steps. The subsequent parts walk you through the fundamentals of RISC-V and Linux kernel internals, including registers, exceptions, and virtual memory, necessary for crash debugging. The final part covers hands-on techniques for investigating kernel panics, exceptions, stack corruption, memory corruption, and system lockups using kernel logs, memory dumps, and debugging tools such as crash utility and GDB.

  By the end of this book, you'll have a structured approach to diagnosing RISC-V Linux crashes, with the practical skills to interpret crash signatures, analyze memory dumps, and identify root causes with confidence.

  *Email sign-up and proof of purchase required*

</details>

<details open>
  <summary><h2>Key Learnings</h2></summary>

  <ul>
    <li>Interpret RISC-V registers, exceptions, and crash signatures</li>
    <li>Analyze kernel logs to identify the causes of system crashes</li>
    <li>Examine kernel memory dumps using crash utility</li>
    <li>Investigate kernel panics, BUG conditions, and memory faults</li>
    <li>Diagnose stack corruption, overflows, and guard page faults</li>
    <li>Debug soft lockups, hard lockups, and hung kernel tasks</li>
    <li>Analyze crashes due to corrupted kernel data structures</li>
    <li>Debug user space crashes and core dumps using GDB</li>
  </ul>

</details>

<details open>
  <summary><h2>Chapters</h2></summary>

  <ol>
    <li>Fundamentals of Crash Debugging</li>
    <li>Practical Crash Debugging Workflow</li>
    <li>Understanding RISC-V for Crash Debugging (Part 1)</li>
    <li>Understanding RISC-V for Crash Debugging (Part 2)</li>
    <li>Linux Kernel Relevant to Crash Handling</li>
    <li>Debugging Tools and Features</li>
    <li>Software-Generated Crashes: panic() and BUG()</li>
    <li>Exception-Generated Crashes</li>
    <li>Stack-related Crashes</li>
    <li>Debugging Linux Kernel Lockups and Freezes</li>
    <li>Data Structure Crashes</li>
    <li>Understanding User Space Crashes in RISC-V Linux</li>
    <li>Triggering and Debugging RISC-V User Space Crashes with LUDTM</li>
  </ol>

</details>

<details open>
  <summary><h2>Requirements for this book</h2></summary>

  <p>
    To get the most out of this book, you should be familiar with C programming and basic Linux concepts. Prior knowledge of the RISC-V architecture, Linux kernel internals, and debugging tools will be helpful but is not essential.
  </p>

  <p>
    The examples in this book are based on <strong>Linux kernel versions (v6.6, v6.17)</strong> and the <strong>64-bit RISC-V (RV64)</strong> architecture with virtual memory support. The memory dumps used for the hands-on debugging exercises were collected from a <strong>VisionFive 2 board</strong>. These memory dump files are available in the book's GitHub repository (see the next section for access instructions), so you can follow along with the debugging examples.
  </p>

  <p>
    Note that the author acknowledges the use of cutting-edge AI, such as ChatGPT, with the sole aim of enhancing the language and clarity within the book, thereby ensuring a smooth reading experience for readers. It's important to note that the content itself has been crafted by the author and edited by a professional publishing team. Packt does not accept AI-generated content that replaces expert authorship.
  </p>

</details>

<details>
  <summary><h2>Get to know the author</h2></summary>

  *Austin Kim* is an embedded Linux BSP engineer with extensive experience in board bring-up, crash and performance troubleshooting, and bootloader development for the smartphone and automotive sectors. He has analyzed many memory dumps using TRACE32, crash utility, and ftrace. He has also resolved various kernel issues, including crashes, system lockups, and watchdog resets.

  He previously worked as a Linux kernel BSP engineer on the Open Source Team at LG Electronics. Currently, he works as a trainer, consultant, and open source developer. He is also the author of Reverse Engineering Armv8-A Systems and has experience with multiple CPU architectures.

  He enjoys sharing practical debugging skills, especially in RISC-V, Armv8-A, and Armv9-A architectures and Linux kernel crash analysis.

</details>

<details>
  <summary><h2>Other Related Books</h2></summary>

  <ul>
    <li>
      <a href="https://www.packtpub.com/en-us/product/risc-v-architecture-and-dsp-processor-design-first-edition-9781807600891">RISC-V Architecture and DSP Processor Design, First Edition</a>
    </li>
    <li>
      <a href="https://www.packtpub.com/en-us/product/practical-debugging-for-embedded-arm-systems-first-edition-9781806673117">Practical Debugging for Embedded ARM Systems, First Edition</a>
    </li>
  </ul>

</details>
