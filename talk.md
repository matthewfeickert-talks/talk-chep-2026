class: middle, center, title-slide
count: false

# HEP Packaging Coordination:<br>Distributing the HEP software ecosystem<br>on conda-forge

.huge.blue[Matthew Feickert], .huge[Chris Burr, Lindsey Gray, Giordon Stark]<br>
.huge[(University of Wisconsin-Madison)]

.large[
[CHEP 2026](https://indico.cern.ch/event/1471803/contributions/6966833/)<br>
May 27th, 2026
]

<!--
# Abstract

The packaging of high energy physics software with robust, yet flexible, distribution methods is a complicated problem that has been met with multiple approaches by the community. The [HEP Packaging Coordination](https://github.com/hep-packaging-coordination) community project expands packaging of the HEP software ecosystem through building and distributing language-agnostic conda packages on the conda-forge package index. Through use of the conda-forge community build cyberinfrastructure, computing platform specific optimized builds of packages can be created for selections of Linux, macOS, and Windows across x86-64, AArch64/ARM64, and ppc64le architectures. In addition to supporting [builds of ROOT](https://github.com/conda-forge/root-feedstock), this work provides multi-platform packaging of a wide array of [low-level-language phenomenology tools](https://github.com/conda-forge/collier-feedstock), the [broader simulation stack](https://github.com/conda-forge/pythia8-feedstock), [end-user-analysis tools](https://github.com/conda-forge/awkward-feedstock) and [statistical frameworks](https://github.com/conda-forge/cms-combine-feedstock), and the [reinterpretation ecosystem](https://github.com/conda-forge/rivet-feedstock). Ongoing work is also supporting builds of LHCb experiment software and distributions of community software with experiment-specific patches applied for use in LHC physics analyses.

This process significantly lowers technical barriers across tool development by providing automatic packaging systems with source code, distribution through secure and transparent build cyberinfrastructure, and enables use through multi-platform optimized binary builds. When combined with next generation scientific package management and manifest tools, the creation of fully specified, portable, and trivially reproducible multi-language software environments becomes easy and fast, even with the use of development platforms for hardware accelerators (e.g. CUDA on NVIDIA GPUs). This talk provides an overview of the work, gives practical recommendations for adoption and best practices for both software maintainers and end-user analysts, and demonstrates examples of new distribution methods that are complementary to existing community technologies, such as [CernVM-FS](https://cernvm.cern.ch/fs/).
-->

---
# Notes

* https://indico.cern.ch/event/1471803/contributions/6966833/
* 18 minutes
   - 15 talk
   - 3 questions

---
# Due for a packaging update talk

<p style="text-align:center;">
   <a href="https://indico.cern.ch/event/773049/contributions/3473243/">
      <img src="figures/chep-2019-title-slide.png"; width=80%>
   </a>
</p>

.center.large[[Chris Burr, CHEP 2019](https://indico.cern.ch/event/773049/contributions/3473243/)]

---
# Software distributions

.kol-1-2[
.large[
In HEP we already have multiple forms of software distribution (different solutions for different kinds of software)

* [CernVM-FS](https://cernvm.cern.ch/fs/)
* Source distribution ([Spack](https://spack.io/))
* Operating system specific distributions (`.rpm`, `.deb`)
* Linux container images (Docker, Apptainer)
* Python packages (PyPI, private indexes, sdist)
* Conda packages
]
]
.kol-1-2[
.large[
Focus on .bold[end-users]

* One package format across all computing systems
   - cluster and local machine are the same
* One package format across all software types
   - arbitrary software packaging
* Multi-platform
   - Target for Linux (x86_64, aarch64), macOS (x86_64, arm64), Windows
* Give declarative specification
* Scientific software environment reproducibility
]
]

---
# What is a [conda package](https://prefix.dev/blog/what-is-a-conda-package)?

.kol-2-3[
.large[
* Fundamentally, a compressed archive containing:
   - metadata
   - files, platform-specific binaries, symlinks
]
]
.kol-1-3.center[
<p style="text-align:center;">
   <a href="https://pixi.prefix.dev/">
      <img src="figures/paxton-small.png"; width=80%>
   </a>
</p>

.center["Paxton" the conda package (prefix.dev GmbH)]
]

---
# Overview

.huge[
* Start
]

---
# Summary

.huge[
* Ze end
]

---
class: end-slide, center

.large[Backup]

---
# Backup

backup

---

class: end-slide, center
count: false

The end.
