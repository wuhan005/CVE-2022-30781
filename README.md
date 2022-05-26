# 🍵 CVE-2022-30781
Gitea repository migration remote command execution exploit.

## How to use

1. Run an HTTP filesystem server with the files in this repository.
2. Edit the command to be exeucted in `api/v1/repos/e99/exp/pulls/1/index.html L96`.
3. Migrate remote repository with URL `http://<your_host>/e99/exp` on the Gitea instance.
4. Pwnned!

## Reference

https://tttang.com/archive/1607/  (Chinese)

## Credit

[@wuhan005](https://github.com/wuhan005) [@Li4n0](https://github.com/li4n0) from Vidar-Team

**This repository is only for security researches/teaching purposes, use at your own risk!**
