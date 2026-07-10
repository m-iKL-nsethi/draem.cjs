![build](https://img.shields.io/badge/build-passing-brightgreen)

# domo-core
The automation engine you can actually program

- Radio drivers included for powerline, mesh, and serial buses
- Runs entirely on the local network, no vendor cloud involved
- Scripting layer with a fluent API, usable from `csharp`, `javascript` or `python`
- Scheduler that understands extended cron syntax: variables, conditions and boolean operators
- Voice commands and text messages as inputs
- Interface translations
- Dashboards, groups, configuration export, package repository, and a good deal more
- One responsive interface that scales from a phone up to a wall-mounted panel
- Visual scenario builder for people who do not write code
- Saved client profiles that can be recalled from the UI at any time


![Dashboards and widgets](https://cdn.example.dev/shots/domo-dashboard.jpg)


## Handbook

The manual, API notes and examples are published on the project site.

## Installing

Grab the archive that matches the machine you are targeting:

**Windows**
- `domo_*_win-x64.zip`

**Mac**
- `domo_*_osx-x64.zip`

**Linux**
- `domo_*_linux-x64.zip`

**ARM board, 32 bit**
- `domo_*_linux-arm.zip`

**ARM board, 64 bit**
- `domo_*_linux-arm64.zip`

Downloads sit on the release page of the repository.

Unpack it and a single folder appears.

### Starting from a shell

Move into that folder and start the binary:

```shell
cd domo-core
./DomoCore
```

### Related work

- the package feed for this engine
- the service daemon that ships alongside it
- the Android companion app
- the Android client library
- the Android front end
- the Windows Phone front end
- the trimmed-down board build
- the scripting helper library used inside the engine

------

### Warranty

The software is supplied without warranty of any kind. The authors accept no liability for damages arising from its use, whether direct or indirect.