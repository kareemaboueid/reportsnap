<p align="center">
  <img src="https://raw.githubusercontent.com/kareemaboueid/reportsnap/refs/heads/main/reportsnap-logo.png" alt="ReportSnap Logo" width="300"/>
</p>

<h1 align="center" dir="auto">reportsnap</h1>

<p align="center" dir="auto">A command-line tool for reporting snapshots for your Linux system</p>

Reportsnap displays information about your system snapshots, including the number of snapshots, their sizes, and the dates they were taken. It supports both Snapper and Timeshift snapshot tools.

## Install

```bash
git clone https://github.com/kareemaboueid/reportsnap.git
```

```bash
cd reportsnap
```

```bash
sudo make install
```

## Usage

```bash
reportsnap              # full report
reportsnap --compact    # condensed output
reportsnap --health     # only overall health line
reportsnap --no-color   # disable ANSI colors
reportsnap --json       # machine-readable summary
reportsnap --help       # show help message
reportsnap --version    # show version
```

## License

[MIT](./LICENSE)
