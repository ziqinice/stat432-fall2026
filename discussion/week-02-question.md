---
id: w02-ziqiz13-code-vs-permission-errors
title: "When Correct Code Still Fails"
author: "Ziqi Zhang (ziqiz13)"
---

During Week 2, I asked an AI tool to run a Python Quarto file. The Python code was correct, but rendering failed because Quarto did not have permission to write a log file. I recognized the cause from the `PermissionError` message and fixed it by allowing the required access. How can an AI distinguish between a coding error and an environment or permission error before changing the code?
