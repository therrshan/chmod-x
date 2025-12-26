# go

Fast URL bookmarking with path routing.

## Install

```bash
chmod +x go
sudo mv go /usr/local/bin/go
```

## Usage

```bash
go <alias> [path...]
go add <alias> <url>
go list
```

### Commands
- `go <alias>` - Open URL
- `go <alias> path segments` - Open URL with appended path
- `go add <alias> <url>` - Add new alias
- `go update <alias> <url>` - Update existing alias
- `go temp <url>` - Open a url without having to add alias
- `go list` - List all aliases
- `go search <term>` - Search aliases
- `go remove <alias>` - Remove alias

## Examples

```bash
# Add aliases (multiple aliases for same URL supported)
go add gh https://github.com
go add git https://github.com

# Open base URL
go gh
go temp htttps://www.github.com

# Open with path routing
go gh torvalds linux          # Opens github.com/torvalds/linux
go docs api auth              # Opens docs-url/api/auth

# Manage aliases
go list                       # Show all
go search github              # Find matching
go remove old-alias           # Delete
```