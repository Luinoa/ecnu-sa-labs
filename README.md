# Labs for "Software Analysis, Testing and Verification"
This repository provides the lab sessions for the course "[Software Analysis, Testing and Verification (软件分析与验证前沿)](https://tingsu.github.io/files/courses/pa2024.html)" at East China Normal University.

We welcome any comments or contributions. Feel free to create issues and pull requests.

<br>

## Course (课程内容)

| Lectures                         |  Title                         |  Extended Readings                        |  Relevant Links                        |
|------------------------------|-----------------------------------|-----------------------------------|-----------------------------------|
| [lec1](https://tingsu.github.io/files/courses/slides/lec-1-course_introduction.pdf)      | Course Introduction: Program Analysis |  [soundiness](https://yanniss.github.io/Soundiness-CACM.pdf), [false positives/negatives](https://dl.acm.org/doi/10.1145/3660781)    |        |
| [lec2](https://tingsu.github.io/files/courses/slides/lec-2-llvm-framework-primer.pdf)       | The LLVM Framework   |      |   [LLVM](https://llvm.org/)   |
| [lec3](https://tingsu.github.io/files/courses/slides/lec-3-software_specifications_and_testing.pdf)       | Software Specifications          |  [oracle problem](https://ieeexplore.ieee.org/document/6963470), [programs, tests, and oracles](https://dl.acm.org/doi/10.1145/1985793.1985847), [code coverage effectiveness](https://dl.acm.org/doi/10.1145/2568225.2568271), [mutation testing effectiveness](https://dl.acm.org/doi/10.1145/2635868.2635929), [testing techniques](https://dl.acm.org/doi/10.1016/j.jss.2013.02.061)，[sanitizers](https://oaklandsok.github.io/papers/song2019.pdf)  |       |
| [lec4](https://tingsu.github.io/files/courses/slides/lec-4-random_fuzz_testing.pdf)       | Random (Fuzz) Testing | [classic fuzz testing](https://arxiv.org/pdf/2008.06537), [havoc](https://dl.acm.org/doi/abs/10.1145/3510003.3510174), [fuzzing book](https://www.fuzzingbook.org/), [Fuzzing101](https://github.com/antonio-morales/Fuzzing101)   |   [AFL](https://github.com/google/AFL), [AFL++](https://github.com/AFLplusplus/AFLplusplus), [LibFuzzer](https://llvm.org/docs/LibFuzzer.html)    | 
| [lec5]()       | Property-based Testing         |      |      |

<br>



## Lab Instructions （教程指引）

Before preceding the labs, you need to setup the lab environment. Checkout this [lab tutorial](lab_manual/course-vm.md). Later, you can access the lab tutorials for our labs in the following table.

### Quick Notes

- Get familar with using VScode, Git, Linux shell commands and Docker. If you are not familar with these stuffs, go and grab [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/).
- Always be patient and careful when reading the documentation (e.g., lab tutorial, instructions). 
- Before rasing questions to TAs, please double check with the documentation. 


| Labs                         | Lab Title                         |  Relevant Research Projects                       |
|------------------------------|-----------------------------------|-----------------------------------|
| [lab1](lab_manual/lab1.md)       | Introduction to Software Analysis |                               |
| [lab2](lab_manual/lab2.md)       | The LLVM Framework                |                               |
| [lab3](lab_manual/lab3.md)       | Random Testing / Fuzzing          |                              |
| [lab4](lab_manual/lab3.md)       | Property-based Testing            |  [Kea](https://github.com/ecnusse/Kea) |
| [lab5](lab_manual/lab4.md)       | Delta Debugging                   |                               |
| [lab6](lab_manual/lab5.md)       | Dataflow Analysis                 |                               |
| [lab7](lab_manual/lab6.md)       | Pointer Analysis                  |                               |
| [lab8](lab_manual/lab7.md)       | Taint Analysis                    | [BinPRE](https://github.com/ecnusse/BinPRE)                              |
| [lab9](lab_manual/lab8.md)       | Dynamic Symbolic Execution        |  [SmartRocket TestGrid]()                             |

<br>




## Troubleshooting (常见问题汇总)

- 第一次配置实验课环境([lab tutorial](lab_manual/course-vm.md))，由于需要下载docker image，请使用科学上网工具。Windows上的科学上网工具有：`Clash for windows`, `Clash Meta`, `V2rayN`（请打开tun模式实现接近于全局的代理）。
- 如果你的电脑系统是Mac，且使用的是Mac M芯片，可能需要安装[Rosetta](https://support.apple.com/en-us/102527) (Rosetta enables a Mac with Apple silicon to use apps built for a Mac with an Intel processor)。另外，确认Docker的`Settings` -> `General`里是否已经勾选上`Use Rosetta for x86_64/amd64 emulation on Apple Silicon`。

## Contributors （贡献者）

主讲老师：[苏亭](http://tingsu.github.io/)、[孙海英](https://faculty.ecnu.edu.cn/_s43/shy/main.psp)

We thanks the TAs and students who have contributed to this course design:

<a href="https://ml-ming.dev/">明孟立</a>,
<a href="https://apochens.github.io/">黄杉</a>,
<a href="">麻恩泽</a>,
徐瑞阳,
王祺昌,
方润渲,
<a href="https://xixianliang.github.io/resume/">梁锡贤</a>,
沈佳伟

林童奕凡、高雨宸


Acknowledgement: The lab sessions are currently developed based on the [cis547](https://software-analysis-class.org) course, and we are further designing and refining the materials based on our ideas.
