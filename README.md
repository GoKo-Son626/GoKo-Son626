<div align="center">
  <img src="./assets/profile-banner.svg" width="100%" alt="GoKo — RTOS, RISC-V and ARM systems developer" />

  <a href="https://github.com/GoKo-Son626">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=2F81F7&center=true&vCenter=true&width=760&lines=RTOS+Developer+%7C+C+%2F+C%2B%2B;RISC-V+K1+Platform+Experience;ARMv7+Porting+%7C+ARMv8+Learning;From+interrupts+and+drivers+to+schedulers" alt="RTOS developer, RISC-V K1 platform experience, and ARM porting" />
  </a>

  <p>
    <a href="https://github.com/GoKo-Son626"><img src="https://img.shields.io/badge/GitHub-GoKo--Son626-181717?style=flat-square&logo=github" alt="GitHub profile" /></a>
    <a href="https://goku72.com"><img src="https://img.shields.io/badge/Website-goku72.com-0A66C2?style=flat-square&logo=googlechrome&logoColor=white" alt="Personal website" /></a>
    <img src="https://komarev.com/ghpvc/?username=GoKo-Son626&style=flat-square&color=2f81f7&label=Profile+views" alt="Profile views" />
    <img src="https://img.shields.io/github/followers/GoKo-Son626?style=flat-square&color=238636&label=Followers" alt="GitHub followers" />
  </p>
</div>

## About me

I am an **RTOS developer in China** focused on the boundary between processor architecture, operating-system kernels, and hardware peripherals. I enjoy following a system from reset and exception entry through interrupt handling, context switching, scheduling, and driver integration.

- 💼 **Current work:** RTOS development, architecture adaptation, and low-level platform work.
- 🛰️ **RISC-V experience:** During a year-long internship in my senior year, I contributed to platform and driver development for the **SpacemiT K1 RISC-V SoC**. My work touched **I²C (IIC), I²S (IIS), IOMMU, pinctrl, GPIO, and clock** subsystems, with focused patches across the stack.
- 🎓 **Foundations:** Studied **STM32 development** and read RTOS kernel source code to understand scheduling, synchronization, interrupts, and context switching from the implementation level.
- 🧭 **Current learning:** Studying **ARMv7-A/Cortex-A9** while preparing and implementing an RTOS port; learning **ARMv8** with the longer-term goal of porting RTOS systems and integrating **CAN bus** support.
- 🤝 **Interests:** RTOS kernels, BSP/SoC bring-up, device drivers, CPU architecture, Linux internals, and embedded open source.

## Engineering focus

| Area | Experience and direction |
| --- | --- |
| **RTOS & kernels** | Scheduling, context switching, interrupts/exceptions, synchronization, timers, and source-level study |
| **Architectures** | RISC-V; ARMv7-A/Cortex-A9 porting; ARMv8 learning |
| **Platforms** | SpacemiT K1, STM32F103, STM32MP157, Zynq-7020 |
| **Subsystems** | I²C/IIC, I²S/IIS, IOMMU, pinctrl, GPIO, clocks, Device Tree, CAN |
| **Bring-up & debug** | Cross-compilation, QEMU, GDB, boot flow, GIC, timers, and board-level debugging |

## Current porting roadmap

```mermaid
flowchart LR
    A[ARMv7-A fundamentals] --> B[Exceptions and GIC]
    B --> C[Timer and context switch]
    C --> D[Preemptive RTOS port]
    E[ARMv8 architecture] --> F[RTOS adaptation]
    F --> G[CAN bus integration]
```

## Technology stack

### Languages and formats

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-6E4C13?style=for-the-badge&logo=assemblyscript&logoColor=white)
![Android](https://img.shields.io/badge/Android-34A853?style=for-the-badge&logo=android&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

### Architectures, kernels, and platforms

![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=for-the-badge&logo=riscv&logoColor=white)
![Arm](https://img.shields.io/badge/ARMv7%20%7C%20ARMv8-0091BD?style=for-the-badge&logo=arm&logoColor=white)
![RTOS](https://img.shields.io/badge/RTOS-Kernel%20%26%20Porting-7B42BC?style=for-the-badge)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-2F8D46?style=for-the-badge&logo=freertos&logoColor=white)
![RT-Thread](https://img.shields.io/badge/RT--Thread-1C75BC?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![SpacemiT K1](https://img.shields.io/badge/SpacemiT-K1-00A86B?style=for-the-badge)

### Drivers and interfaces

![I2C](https://img.shields.io/badge/I%C2%B2C%20%2F%20IIC-00599C?style=for-the-badge)
![I2S](https://img.shields.io/badge/I%C2%B2S%20%2F%20IIS-6F42C1?style=for-the-badge)
![CAN](https://img.shields.io/badge/CAN-Bus-E34F26?style=for-the-badge)
![GPIO](https://img.shields.io/badge/GPIO-555555?style=for-the-badge)
![IOMMU](https://img.shields.io/badge/IOMMU-8A2BE2?style=for-the-badge)
![pinctrl](https://img.shields.io/badge/pinctrl-0969DA?style=for-the-badge)
![Device Tree](https://img.shields.io/badge/Device%20Tree-3A7D44?style=for-the-badge)
![Clock](https://img.shields.io/badge/Clock%20Subsystem-B8860B?style=for-the-badge)

### Build, debug, and workflow

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![GNU Bash](https://img.shields.io/badge/GNU%20Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D00CC?style=for-the-badge&logo=cmake&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![QEMU](https://img.shields.io/badge/QEMU-FF6600?style=for-the-badge&logo=qemu&logoColor=white)
![GDB](https://img.shields.io/badge/GDB-Debugging-A42E2B?style=for-the-badge&logo=gnu&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white)
![Vim](https://img.shields.io/badge/Vim-019733?style=for-the-badge&logo=vim&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=for-the-badge&logo=windows11&logoColor=white)

## Selected work

| Project | What it represents |
| --- | --- |
| [**Caffeinix**](https://github.com/GoKo-Son626/caffeinix) | A RISC-V Unix-like system project for exploring kernel construction, cross-compilation, QEMU, and root filesystems. |
| [**xv6 Chinese Comments**](https://github.com/GoKo-Son626/xv6-chinese-comments) | Source-level study of xv6-riscv, including boot, traps, spinlocks, virtual memory, scheduling, and context switching. |
| [**STM32F103**](https://github.com/GoKo-Son626/STM32F103) | STM32/Cortex-M3 learning notes, reference material, and board-level experiments. |
| [**Kernel Way**](https://github.com/GoKo-Son626/kernel-way) | Notes on Linux, Device Tree, kernel workflows, and Banana Pi F3/K1 platform work. |
| [**LAVA for RISC-V**](https://github.com/GoKo-Son626/lava-webserver-riscv) | LAVA and KernelCI-oriented boot/deployment automation for RISC-V boards, including Banana Pi F3. |

<div align="center">
  <a href="https://github.com/GoKo-Son626/caffeinix"><img width="49%" src="https://github-stats-extended.vercel.app/api/pin/?username=GoKo-Son626&repo=caffeinix&theme=transparent&hide_border=true" alt="Caffeinix repository card" /></a>
  <a href="https://github.com/GoKo-Son626/xv6-chinese-comments"><img width="49%" src="https://github-stats-extended.vercel.app/api/pin/?username=GoKo-Son626&repo=xv6-chinese-comments&theme=transparent&hide_border=true" alt="xv6 Chinese comments repository card" /></a>
</div>

## GitHub activity

<div align="center">
  <img width="49%" src="https://github-stats-extended.vercel.app/api?username=GoKo-Son626&show_icons=true&include_all_commits=true&rank_icon=github&theme=transparent&hide_border=true" alt="GoKo's GitHub statistics" />
  <img width="49%" src="https://github-stats-extended.vercel.app/api/top-langs/?username=GoKo-Son626&layout=compact&langs_count=8&theme=transparent&hide_border=true&exclude_repo=linux,RT-Thread,opensbi,input-leap,sing-box-yg,nvm,awesome-linux-software-cn,clash-rules" alt="GoKo's most-used languages" />
</div>

<div align="center">
  <img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=GoKo-Son626&theme=github-compact&hide_border=true&area=true&custom_title=Recent%20Contribution%20Activity" alt="Recent GitHub contribution activity" />
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GoKo-Son626/GoKo-Son626/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/GoKo-Son626/GoKo-Son626/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub contribution grid snake animation" src="https://raw.githubusercontent.com/GoKo-Son626/GoKo-Son626/output/github-contribution-grid-snake.svg" />
</picture>

<div align="center">
  <sub>Building upward from registers, interrupts, and context switches.</sub>
</div>

