# Homebrew Tap for Indie Ventures

Homebrew tap for [Indie Ventures](https://github.com/atropical/indie-ventures) - a self-hosted Supabase manager for running multiple isolated projects.

## Installation

```bash
# Tap this repository
brew tap atropical/indie-ventures

# Install Indie Ventures
brew install indie-ventures
```

## Usage

After installation:

```bash
indie init    # Initialize
indie add     # Add a project
indie list    # List projects
```

## What's Included

- `indie` CLI tool
- Dependencies: gum, docker, docker-compose, jq

## Note

⚠️ This Homebrew installation is for **local development only**.

For production servers, use the direct installation:
```bash
curl -fsSL https://raw.githubusercontent.com/atropical/indie-ventures/main/install.sh | sudo bash
```

## Documentation

See [Indie Ventures](https://github.com/atropical/indie-ventures) for full documentation.

## License

OSL-3.0

