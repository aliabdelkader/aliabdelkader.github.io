---
title: "MLIR Learning Resources"
tags:
  - MLIR
---

In the past few months, I have been learning to use [MLIR](https://mlir.llvm.org/). MLIR stands for Multi level Intermidate Representation. It is a compiler infrastructure framework mainly used for creating domain specific compilers. It was originally created by Google and is part of LLVM. It has been used to build many machine learning compilers such as [IREE](https://iree.dev/), [OpenXLA](https://openxla.org/) and [Torch-MLIR](https://github.com/llvm/torch-mlir).

Unfortunately, MLIR has a steep learning curve. Here is a list of the resources that I have found helpful:

- A good introduction to MLIR and how it can be used can be found in the "MLIR Tutorial" by Mehdi Amini & River Riddle [link](https://youtu.be/Y4SvqTtOIDk?si=bSgOqbXJlUqF5zWK). 

- Another recommended introduction to MLIR was presented by Oleksandr "Alex" Zinenko in CGO Conference [link](https://youtu.be/C_MdJu70z2o?si=Pj_-xKSVbSj6iORI).

- I think Jeremy Kun's  “MLIR for Beginners” tutorial is the most accessible tutorial for beginners [link](https://github.com/j2kun/mlir-tutorial/tree/main).

- The toy tutorial in the MLIR repo provides a nice end to end example in which the toy language is lowered all the way to LLVMIR and executed. It also shows all the different components inside the MLIR framework [link](https://mlir.llvm.org/docs/Tutorials/Toy/).

- Alex Zinenko provided an excellent analysis and breakdown of the different dialects in this write up [link](https://discourse.llvm.org/t/codegen-dialect-overview/2723).

- Mehdi Amini provided an insightful presentation about the internal implementation of the mlir operations and attributes in this MLIR Open Design Meeting [slides](https://mlir.llvm.org/OpenMeetings/2023-02-09-Properties.pdf) [recording](https://youtu.be/7ofnlCFzlqg).

- Having a look at previous MLIR talks is also recommended [link](https://mlir.llvm.org/talks/).

I hope that was helpful. I will keep updating this list with resources as I progress more in my journey.

