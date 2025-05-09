---
layout: default
---

# GPUJake

## Biography
Born in 1993 in the hills of eastern Tennessee, James "Jake" Wynne III is currently an HPC Storage Systems Engineer at Oak Ridge National Laboratory's National Center for Computational Sciences. While interning at Oak Ridge National Laboratory early in his career, while developing tutorials for using the Titan supercomputer's GPU's, one of his mentors and dear friends gave him the nickname 'GPUJake', and that title has stuck ever since.

## Whitepapers
### [Data Transfer Study for HPSS Archiving](https://cug.org/proceedings/cug2015_proceedings/includes/files/pap103.pdf)
This is a whitepaper that I coauthored early in my career, summarizing months of data transfer studies I performed on ORNL's HPSS file system. I had the opportunity to present this paper at the Cray User Group conference in April of 2015. 

### [Toward an End-to-end Framework for Modeling, Monitoring and Anomaly Detection for Scientific Workflows](https://www.es.net/assets/pubs_presos/paper-LSPP16-Final.pdf)
I co authored this paper at the end of my internship in the ORNL Future Technologies Group, where I studied compiler design and implemented the ‘Black-box modeling’ feature in the ASPEN performance modeling compiler. Section II was the result of my own work and writing and illustrates the ‘black-box modeling’ algorithm that I contributed to ASPEN. This algorithm uses a Non-Linear Optimization library to better predict performance of applications based upon historical, real-world performance data.

## Projects
### [jNix (or, Just another uNix clone)](https://github.com/JRWynneIII/jnix-cpp)
jNix is a personal project of mine that I have been using to explore and learn more about kernel development. About 10 years ago, I wrote a very simple 32-bit x86 kernel in C/asm as I followed various tutorials. Similarly, I did the same about 5 years ago as well, but with Rust this time. Finally, this iteration of my project is written in C++ targeting x86_64, and is not based upon any existing tutorials or procedures. I took what I learned from previous projects, and am developing this completely independently. It's still a work in progress

### [GLS (GPFS aware ls)](https://github.com/olcf/gls)
GLS was a tool I developed at ORNL/NCCS that was designed to be a drop-in replacement for GNU ls. While performing the standard functions that ls provides, it also ties into the GPFS filesystem in order to provide annotations for storage-tier locality within its output. In short: it will annotate/color files red, if the file data exists on the slow, tape-based tier, yellow if the data is duplicated on both the disk and tape tier, and green if the data is stored on the fast, GPFS disk tier.

### [hsi_xfer](https://github.com/olcf/hsi_xfer)
hsi_xfer was born out of a need to provide users of ORNL's/NCCS' soon-to-be-decommissioned HPSS filesystem with a data transfer tool that ensures better data integrity, provides a checkpointing mechanism, and orders transfers in such a way that resources are shared fairly, and aging tape components are not unduly stressed. This tool wraps an existing FTP-like client for HPSS, called `hsi`, hence the name.


## Certifications and degrees
- Bachelors of Science and Information Technology and Software Development
- RedHat Linux Certified Engineer
- RedHat Linux Certified System Administrator 
- ITIL v4
- Amateur Radio General License

## Connect:
* [LinkedIn](https://linkedin.com/in/gpujake)
* [GitHub](https://github.com/JRWynneIII)
* [ORCID](https://orcid.org/0000-0003-3706-1328)
* [Email](mailto:wynnejr@gpujake.com)

