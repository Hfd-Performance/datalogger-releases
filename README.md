# HFD Datalogger — releases

Installers for the HFD Datalogger. Source lives in a separate private repository; nothing here
but published builds.

## Install

Download the latest `HFD-Datalogger-*.zip` from
[Releases](https://github.com/Hfd-Performance/datalogger-releases/releases), extract it, and run
`Install.bat`.

It installs for the current user only — no administrator, no UAC prompt — and writes its own
`Uninstall.bat`. Nothing else needs installing: no Python, no runtime. You do still need your
interface cable's own driver (Tactrix, Scanmatik or whatever you use); that is the
manufacturer's software, not ours.

## What is in it

| Program | What it does |
|---|---|
| **TDL Review** | Open a log — charts, gauges and the tuning histogram. Live logging off the car. |
| **PID Wizard** | Ask a car what it can tell us. Run this first on a vehicle nobody has scanned. |
| **Car Recorder** | One button. Records a drive and writes files to send back. |

## Updates

TDL Review checks here when it starts and tells you if a newer build exists. It never installs
anything by itself — it downloads when you say so, and you run the installer.

## Windows Defender

These builds are not code-signed yet, so SmartScreen may warn the first time. That is a reaction
to an unknown publisher rather than to anything found in the files.
