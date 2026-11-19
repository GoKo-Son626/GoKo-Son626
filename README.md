![GoKo at a Linux prompt, with a research satellite passing over Earth's night side](./assets/orbital-linux.webp)

# Embedded systems & flight software

I'm GoKo, an **RTOS developer based in Norway**. Recently I got the Software Bus from NASA's core Flight Executive (cFE) running in a standalone Linux process. With two tasks subscribed to the same message, I could follow a buffer from the publisher to each receiver and see when it was safe to release it.

I started with an STM32 board and the FreeRTOS scheduler. Later I spent a year on RISC-V SoC drivers, contributing small patches for I²C, I²S, the IOMMU, pin control, GPIO and clocks. These days I'm working on **ARMv7-A/Cortex-A9 porting** and exploring ARMv8 and CAN on RTOS.

<p>
  <img height="23" alt="C" src="https://img.shields.io/badge/C-203650?style=flat&amp;logo=c&amp;logoColor=white" />
  <img height="23" alt="Linux" src="https://img.shields.io/badge/Linux-193848?style=flat&amp;logo=linux&amp;logoColor=E8C57D" />
  <img height="23" alt="RTOS" src="https://img.shields.io/badge/RTOS-24544D?style=flat" />
  <img height="23" alt="RISC-V" src="https://img.shields.io/badge/RISC--V-263C61?style=flat&amp;logo=riscv&amp;logoColor=white" />
  <img height="23" alt="Arm" src="https://img.shields.io/badge/Arm-254558?style=flat&amp;logo=arm&amp;logoColor=white" />
</p>

## Engineering notes

I write in Chinese about the questions that send me back to the source code. [Visit my blog ↗](https://www.goku72.com/)

| Field note | What I traced |
| --- | --- |
| [Running cFE's Software Bus on Linux](https://www.goku72.com/post/cfs-sb-07-linux-port.html) | Which services does the bus need from cFE, and which can POSIX supply? |
| [Packing a message with EdsLib](https://www.goku72.com/post/eds-pus-02-edslib-pack-unpack.html) | How does an in-memory C object become a byte stream, and what comes back after unpacking? |
| [A timer interrupt on ARMv7-A](https://www.goku72.com/post/armv7a-06-gic-timers.html) | What happens between the timer expiring, the GIC acknowledging the interrupt and the task resuming? |
| [Reading time aboard a spacecraft](https://www.goku72.com/post/sois-time-access-service.html) | How does the SOIS Time Access Service relate an onboard counter to a time reference? |

## Featured work

**[Caffeinix](https://github.com/GoKo-Son626/caffeinix)** · C / RISC-V

My working fork of a small Unix-like kernel. It boots an unmodified, statically linked BusyBox from ext4 on QEMU `virt`. That gives me a real userspace program for exercising the kernel's Linux-compatible ABI.

**[SDF Translator](https://github.com/GoKo-Son626/sdf)** · Python / Linux

Select a term in a PDF datasheet and press `Super+Shift+T` to translate it without leaving the page. The same shortcut works in a browser or editor. SDF also runs in the terminal and can save vocabulary as Markdown.

<details>
<summary><strong>Platforms and tools</strong></summary>

| Area | Stack |
| --- | --- |
| Languages | C, C++, assembly, Python, Bash, Markdown |
| Targets & kernels | STM32, SpacemiT K1, RISC-V, ARMv7-A, ARMv8, Linux, FreeRTOS, RT-Thread |
| Board support | Device Tree, pinctrl, GPIO, clocks, IOMMU, I²C, I²S, CAN |
| Build & debug | Git, GitHub, Make, CMake, GDB, QEMU, Docker |
| Editors & environments | Vim, VS Code, PyCharm, Ubuntu, Windows, Android |

</details>

## GitHub activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GoKo-Son626/GoKo-Son626/output/github-contribution-grid-snake-dark.svg" />
  <img width="100%" src="https://raw.githubusercontent.com/GoKo-Son626/GoKo-Son626/output/github-contribution-grid-snake.svg" alt="Animated snake tracing GoKo's GitHub contributions over the past year" />
</picture>

[**↻ Refresh the snake**](https://github.com/GoKo-Son626/GoKo-Son626/actions/workflows/snake.yml) · Updates every four hours. Choose **Run workflow** for a manual refresh.

<details>
<summary>Public contribution and language charts</summary>

<p>
  <img width="396" alt="Public GitHub contribution statistics for GoKo" src="https://github-stats-extended.vercel.app/api?username=GoKo-Son626&amp;include_all_commits=true&amp;show_icons=true&amp;hide_rank=true&amp;disable_animations=true&amp;bg_color=0A1424&amp;title_color=9EDACF&amp;text_color=D5E4F1&amp;icon_color=E6BC76&amp;border_color=25384F&amp;border_radius=12" />
  <img width="323" alt="Language distribution across GoKo's selected public repositories" src="https://github-stats-extended.vercel.app/api/top-langs/?username=GoKo-Son626&amp;layout=compact&amp;langs_count=6&amp;disable_animations=true&amp;size_weight=0.5&amp;count_weight=0.5&amp;bg_color=0A1424&amp;title_color=9EDACF&amp;text_color=D5E4F1&amp;border_color=25384F&amp;border_radius=12&amp;exclude_repo=linux,RT-Thread,opensbi,input-leap,sing-box-yg,nvm,awesome-linux-software-cn,clash-rules" />
</p>

</details>
