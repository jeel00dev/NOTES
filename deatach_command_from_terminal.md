# Running Commands in the Background on Linux

When working remotely via SSH, it’s often useful to **run long-running commands ** without keeping your SSH session open. This guide explains how to do that effectively.

---

## 1. Using `nohup` to detach commands

`nohup` stands for _no hang-up_. It allows a command to continue running even after you close your terminal or SSH session.

### Syntax

```bash
nohup <command> &
```
