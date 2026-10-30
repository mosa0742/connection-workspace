# Connection Workspace v1 Beta

Free Windows SSH, Telnet, and Serial client with saved connections and terminal tabs. An independent modified version of PuTTY 0.85.

## Download and run

Download the release ZIP, extract it, and run `connection-workspace-v1.exe`. Keep `LICENCE.txt` with redistributed copies.

## Features

- Clean light host table with search and a connection editor
- Multiple terminal tabs in one window
- Saved SSH usernames and optional passwords protected with Windows DPAPI
- Import SSH hosts from text and test password logins
- Telnet connections with interactive login (unencrypted)
- Serial COM line, baud rate, data bits, stop bits, parity, and flow control

## Beta status

Native configuration save/load and two local Telnet connections were tested. Physical Serial hardware has not been tested. The modifications have not had an independent security audit. The executable is unsigned.

Saved sessions use PuTTY's existing per-user session storage. Back up existing PuTTY profiles before editing them with this beta.

## Attribution and license

Based on PuTTY, copyright Simon Tatham and contributors. The original copyright and permission notices are retained in LICENCE.txt. This project is independent of the PuTTY team.

## Feedback

Report bugs through this repository's Issues. Include Windows version, steps to reproduce, and the application version. Do not include passwords, private keys, or sensitive connection information.
