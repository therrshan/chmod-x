# go - Quick Link Manager

Personal bookmark system that opens links from your terminal.

## Usage

Open a link:
```bash
go yt
```

Add new link:
```bash
go add reddit https://reddit.com
```

List all links:
```bash
go list
```

Remove link:
```bash
go remove reddit
```

## Configuration

Links are stored in `~/.config/go-links/aliases` as simple key-value pairs:
```
alias=url
```
