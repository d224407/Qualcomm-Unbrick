## Qualcomm EDL Tool
# What is this?
A command-line tool for flashing firmware onto SUPPORTED Qualcomm devices via EDL (Emergency Download Mode).

##  Requirements

- Windows 7/8/10/11
- .NET Framework 4.5 or later
- Git
- Full STOCK firmware of your phone (not custom firmware)
- A supported device [list](https://github.com/d224407/Qualcomm-Unbrick/blob/main/devices.txt)

##  Installation

Run the `edl_tool.bat` file; the script will automatically:
1. Clone the repository to the temp directory
2. Download the necessary tools
3. Guide you through the process step-by-step

## How does this work?
```bash
┌─────────────────────────────────────────────────────────────────┐
│                 XIAOMI AUTHORIZATION BYPASS                     │
└─────────────────────────────────────────────────────────────────┘

  Device requires            edl.exe sends             Device
  Xiaomi authorization  ──→  special XML command  ──→  accepts flashing
```
