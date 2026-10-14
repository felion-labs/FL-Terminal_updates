<p align="center">
  <img src="images/banner.png" alt="Felion Terminal: local shells, SSH, SFTP, serial and tunnels in one window" width="100%">
</p>

<p align="center">
  <a href="https://github.com/felion-labs/FL-Terminal_updates/releases/latest"><img alt="Latest version" src="https://img.shields.io/github/v/release/felion-labs/FL-Terminal_updates?style=for-the-badge&label=latest&color=F97316&labelColor=0B0F14"></a>
  <img alt="Windows, macOS, Linux" src="https://img.shields.io/badge/runs_on-Windows_·_macOS_·_Linux-F97316?style=for-the-badge&labelColor=0B0F14">
  <img alt="SSH, SFTP, serial" src="https://img.shields.io/badge/SSH_·_SFTP_·_serial-one_window-F97316?style=for-the-badge&labelColor=0B0F14">
</p>

<p align="center">
  <b>Felion Terminal</b> is a fast, focused terminal for people who live on servers.<br>
  Your shells, SSH sessions, files, tunnels and serial consoles, side by side, in one calm window.
</p>

<p align="center">
  <a href="https://github.com/felion-labs/FL-Terminal_updates/releases/latest"><b>⬇&nbsp;&nbsp;Download the latest version</b></a>
</p>

<p align="center">
  <img src="images/workspace.png" alt="A production SSH session in two panes: commands with green and red command marks on the left, top on the right; the file panel follows the terminal and the status bar shows a tunnel" width="100%">
</p>

---

## Download

Open the **[latest release](https://github.com/felion-labs/FL-Terminal_updates/releases/latest)** and pick the file for your system:

| System | File |
|---|---|
| **Windows** 10 and 11 | `FelionTerminal-Setup-<version>.exe` installs it; `FelionTerminal-Portable-<version>.exe` runs without installing |
| **macOS**, Apple silicon (M1 and later) | `FelionTerminal-<version>-mac-arm64.dmg` |
| **macOS**, Intel | `FelionTerminal-<version>-mac-x64.dmg` |
| **Linux** | `FelionTerminal-<version>-linux-x86_64.AppImage` runs anywhere; `FelionTerminal-<version>-linux-amd64.deb` for Debian and Ubuntu |

<table>
  <tr>
    <td width="50%"><img src="images/dmg.png" alt="The macOS installer: drag Felion Terminal into Applications"></td>
    <td width="50%" valign="top">
      <b>Installing</b>
      <ul>
        <li><b>macOS</b>: open the <code>.dmg</code> and drag the lion into Applications.</li>
        <li><b>Windows</b>: run the installer; it adds a Start menu entry and can be removed from Settings → Apps.</li>
        <li><b>Linux</b>: make the AppImage executable (<code>chmod +x</code>) and run it, or <code>sudo apt install ./FelionTerminal-…deb</code>.</li>
      </ul>
      <b>First start</b>: until the builds carry a code-signing certificate, the system asks once.
      On Windows choose <b>More info → Run anyway</b>; on macOS open <b>System Settings → Privacy &amp; Security</b>
      and click <b>Open Anyway</b>.<br><br>
      <b>Checking a download</b>: every release has a <code>SHA256SUMS.txt</code>. Compare with
      <code>shasum -a 256 &lt;file&gt;</code> (macOS, Linux) or <code>Get-FileHash &lt;file&gt;</code> (PowerShell).
    </td>
  </tr>
</table>

---

## What you get

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Terminals</h3>
      <ul>
        <li>Tabs and split panes; tabs and splits reopen where you left them.</li>
        <li><b>Quick terminal</b>: a hotkey drops a shell from the top of the screen in any app.</li>
        <li><b>Host colours</b>: mark production in red and every tab and pane on it says so.</li>
        <li><b>Command marks</b>: a green or red mark by every command's result; jump between them.</li>
        <li>Search, multi-exec into every pane at once, notifications when a long command ends.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>Servers</h3>
      <ul>
        <li><b>SSH</b> with password, key, agent and two-factor prompts, jump hosts, agent and X11 forwarding.</li>
        <li>Host keys checked on first use; a changed key stops the connection with a clear warning.</li>
        <li>Port forwarding: local, remote and SOCKS.</li>
        <li><b>Serial</b> consoles and <b>Telnet</b> for network gear.</li>
        <li><b>rz / sz</b> (ZMODEM) file transfers right in the terminal.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>Files</h3>
      <ul>
        <li>A file panel next to the terminal that follows <code>cd</code>.</li>
        <li><b>SFTP, FTP and FTPS</b> sessions open a two-pane file manager with a transfer queue.</li>
        <li>A built-in editor: open a file on the server, save it back over the same connection.</li>
      </ul>
    </td>
    <td valign="top">
      <h3>Yours</h3>
      <ul>
        <li>Saved sessions in folders, snippets, and a command palette for everything.</li>
        <li>Four colour schemes, from dark to light.</li>
        <li>Passwords kept in your system keychain; export and import as one encrypted file.</li>
      </ul>
    </td>
  </tr>
</table>

---

## A closer look

<table>
  <tr>
    <td width="50%"><img src="images/files.png" alt="The file manager: this computer and the server side by side, a download in the transfer queue"></td>
    <td width="50%"><img src="images/editor.png" alt="The built-in editor with two files from the server open in tabs"></td>
  </tr>
  <tr>
    <td align="center"><sub><b>File manager</b>: this computer and the server side by side.</sub></td>
    <td align="center"><sub><b>Editor</b>: server files in tabs, saved back where they came from.</sub></td>
  </tr>
  <tr>
    <td><img src="images/sessions.png" alt="Saved sessions in folders with host colours"></td>
    <td><img src="images/palette.png" alt="The command palette over the workspace"></td>
  </tr>
  <tr>
    <td align="center"><sub><b>Sessions</b>: folders, colours, search and quick connect.</sub></td>
    <td align="center"><sub><b>Command palette</b>: every action, session and snippet, one search away.</sub></td>
  </tr>
  <tr>
    <td><img src="images/welcome-look.png" alt="The welcome tour: pick colours and a text size"></td>
    <td><img src="images/idle.png" alt="The idle screen: the lion above a clock"></td>
  </tr>
  <tr>
    <td align="center"><sub><b>Welcome tour</b>: colours, text size and your servers in under a minute.</sub></td>
    <td align="center"><sub><b>Idle screen</b>: the lion keeps watch while your sessions keep running.</sub></td>
  </tr>
</table>

---

## Updates

The app looks at the latest release in this repository shortly after it starts and every six hours.
When there is a newer version it tells you and offers the right file for your system; nothing is
downloaded or installed until you choose to. You can check by hand, or turn the checks off, in
**Settings → About**.

This repository holds the releases only. Each one is published here automatically when a new
version is built, with its notes and checksums.

---

<p align="center">
  <img src="images/felion-lion-assemble.gif" width="160" alt="The Felion lion assembling from its facets"><br>
  <sub>Felion Terminal · Felion Labs</sub>
</p>
