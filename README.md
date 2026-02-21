<div align="center">
  <h1>🧹 Windows Cleaner</h1>
  <p><strong>A lightweight console utility for cleaning temporary files in Windows</strong></p>
  
  <p>
    <img src="https://img.shields.io/badge/platform-Windows-blue?style=flat-square" alt="Platform Windows">
    <img src="https://img.shields.io/badge/framework-.NET%20Framework%204.8-purple?style=flat-square" alt=".NET Framework">
    <img src="https://img.shields.io/badge/language-C%23-green?style=flat-square" alt="Language C#">
    <img src="https://img.shields.io/badge/license-MIT-orange?style=flat-square" alt="License MIT">
  </p>
</div>

---

## 📋 Overview

Windows Cleaner is a console-based application that helps free up disk space by safely removing temporary files and system junk. Built with C# and .NET Framework, it provides an efficient way to maintain your system's performance.

<div align="center">
  <table>
    <tr>
      <td align="center">🗑️</td>
      <td><b>Temp Files Cleaning</b></td>
      <td>User TEMP folder and system Windows\Temp</td>
    </tr>
    <tr>
      <td align="center">⚡</td>
      <td><b>Prefetch Cleanup</b></td>
      <td>Safely removes prefetch cache</td>
    </tr>
    <tr>
      <td align="center">📊</td>
      <td><b>System Information</b></td>
      <td>Disk usage, OS version, computer name, user info</td>
    </tr>
    <tr>
      <td align="center">📂</td>
      <td><b>Open TEMP Folder</b></td>
      <td>Quick access via File Explorer</td>
    </tr>
  </table>
</div>

---

## 🛠️ Key Features

<div align="center">
  <table>
    <tr>
      <td width="50%" valign="top">
        <h3>📁 File System Operations</h3>
        <ul>
          <li>Recursive directory scanning with <code>Directory.GetFiles()</code> and <code>Directory.GetDirectories()</code></li>
          <li>Safe file deletion with exception handling (<code>try-catch</code>)</li>
          <li>File size calculation with <code>FileInfo.Length</code></li>
        </ul>
      </td>
      <td width="50%" valign="top">
        <h3>💻 System Integration</h3>
        <ul>
          <li>Drive information via <code>DriveInfo</code> class</li>
          <li>System data from <code>Environment</code> class</li>
          <li>Launch Explorer with <code>Process.Start()</code></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td width="50%" valign="top">
        <h3>🎨 User Interface</h3>
        <ul>
          <li>Colored console menu (<code>ConsoleColor</code>)</li>
          <li>Byte formatting for human-readable output (<code>FormatBytes()</code>)</li>
          <li>Interactive menu navigation</li>
        </ul>
      </td>
      <td width="50%" valign="top">
        <h3>🛡️ Error Handling</h3>
        <ul>
          <li>Continues operation when files are inaccessible</li>
          <li>Error counting and user feedback</li>
          <li>Protects system file <code>layout.ini</code> during Prefetch cleanup</li>
        </ul>
      </td>
    </tr>
  </table>
</div>

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/windows-cleaner.git

# Open in Visual Studio and build
# Or download the latest release
