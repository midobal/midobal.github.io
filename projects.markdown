---
layout: page
title:
---

## Software projects
**[Prefix-based IMT](https://github.com/midobal/pb-imt)** <br />
Extension of [Barrachina et al.](https://aclanthology.org/J09-1002.pdf) implementation of the prefix-based interactive machine translation protocol. Taken a [Moses](https://github.com/moses-smt/mosesdecoder) search graph as an input, this software generates a word graph compatible with Barrachina et al. software and runs a user simulation. It was built in Python.
{: .justify}

**[Segment-based IMT](https://github.com/midobal/sb-imt)** <br />
Implementation of the segment-based interactive machine translation protocol from *[Segment-based Interactive-Predictive Machine Translation](https://riunet.upv.es/bitstream/handle/10251/103640/Author%20Version.pdf?sequence=3&isAllowed=y)*. It was built in Python profiting from [Moses](https://github.com/moses-smt/mosesdecoder)' XML scheme.
{: .justify}

**[Statistical dictionary](https://github.com/midobal/sd)** <br />
Given a parallel data set, this software trains an statistical dictionary for translating documents. It was built in Python and makes use of [mgiza](https://github.com/moses-smt/mgiza) for computing *IBM model 1* alignments.
{: .justify}

**[Active learning](https://github.com/midobal/OpenNMT-py/tree/OnlineLearning)** <br />
Implementation of the active learning protocol from *[A User Study of the Incremental Learning in NMT](https://www.aclweb.org/anthology/2020.eamt-1.34.pdf)* based on the toolkit [OpenNMT-py](https://github.com/OpenNMT/OpenNMT-py). It was built in PyTorch.
{: .justify}

**[Online demonstrator](https://github.com/midobal/mthd)** <br />
Online demonstrator of several applications of machine translation for the processing of historical documents. The server is based on [NMT-Keras](https://github.com/lvapeab/nmt-keras).
{: .justify}

## Other utilities
**[Dockerfiles](https://github.com/midobal/dockerfiles)** <br />
A collection of custom Dockerfiles for several tasks.
{: .justify}

**[MT scripts](https://github.com/midobal/mt-scripts)** <br />
A collection of several scripts useful for research in machine translation.
{: .justify}
