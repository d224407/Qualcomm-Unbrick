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

## Note

- If the flash fail or disrupted don't panic, just replug (you don't even need to) and re-run the script, if you find any bugs please tell me
- BE CAREFUL!!! NEVER LET YOUR PC DOWN AND MAKE SURE THE BATTERY IS OVER 50%!!! IF THE PC IS DOWN AND DOESNT RECOGNIZE THE PHONE, UNPLUG THE DEVICE IMMEDIATEL, TURN OF THE PC COMPLETELY AND GIVE IT A 30-SECONDS REST. After that check if the phone is warm or cool, if it's cool then you can continue. What if you don't do this? Your hardware will die, that's it.
- Have a nice day!
