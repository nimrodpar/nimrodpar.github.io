---
title: Python R2 script(s)
author: Nimrod Partush
date: Oct 10, 2020
categories: [Projects]
tags: [reverse-engineering, python, radare2]
math: false
---

I wrote a python script for disassembling an executable *with radare2* (find all procedures & blocks locations and
extract binary and disassembly), since I (was surprised that I) couldn't find one.

You can find it [here](https://github.com/nimrodpar/radare2-python), along with a comparison to [IDA](https://www.hex-rays.com/products/ida/) (which shows R2 is on par):

![Desktop View](https://github.com/nimrodpar/radare2-python/raw/master/IDA%20v%20R2%20-%20Bytes.png){: width="600" }
_R2 v IDA - Recovered Bytes_

![Desktop View](https://github.com/nimrodpar/radare2-python/raw/master/IDA%20v%20R2%20-%20Runtime.png){: width="600" }
_R2 v IDA - Extraction Time_
