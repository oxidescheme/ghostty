<div align="center">

# oxide

</div>

<h6 align="center">
Where function meets form.
</h6>

<p align="center">
  <a href="https://github.com/oxidescheme/ghostty/stargazers"><img src="https://img.shields.io/github/stars/oxidescheme/ghostty?colorA=161616&colorB=00a6ff&style=for-the-badge"></a>
  <a href="https://github.com/oxidescheme/ghostty/issues"><img src="https://img.shields.io/github/issues/oxidescheme/ghostty?colorA=161616&colorB=ff5655&style=for-the-badge"></a>
  <a href="https://ghostty.org/"><img src="https://img.shields.io/badge/Made%20for%20Ghostty-9588ff?style=for-the-badge&logo=ghostty&logoColor=white"></a>
  <a href="https://discord.gg/p8GcbBH5MR"><img src="https://img.shields.io/discord/1450777325267456097?style=for-the-badge&color=00baaa&labelColor=161616&logo=discord&logoColor=white"></a>
</p>

<p>
<b>oxide</b> for Ghostty brings the oxide colorscheme to your terminal with OKLCH precision.
A minimalist dark theme built around clarity and restraint, using a deep near-black background, crisp white foregrounds, and soft pastel accents to emphasize structure without visual noise.
</p>

## Design Philosophy

oxide is built on three core principles:

- **Function first**: If a color does not serve a purpose, it does not belong
- **Visual silence**: High contrast is reserved for data that matters; everything else recedes
- **Calculated colors**: Built with OKLCH color space so all colors have consistent brightness and work well together

The full design philosophy and color system are documented in the [main oxide repository](https://github.com/oxidescheme/oxide).

## Installation

### Built-in Theme (Recommended)

The simplest way to use oxide is with Ghostty's built-in theme support:

```toml
theme = oxide
```

### Manual Installation

To use the exact theme from this repository:

1. Download the `Oxide` file from this repository
2. Copy it to your Ghostty themes directory: `~/.config/ghostty/themes/`
3. Set the theme in your Ghostty configuration:

```toml
theme = Oxide
```

4. Reload or restart Ghostty

## Configuration

### Basic Usage

Add this line to your Ghostty configuration file (`~/.config/ghostty/config`):

```toml
theme = oxide
```

### Light/Dark Mode Support

oxide works great as a dedicated dark theme, or combined with a light theme:

```toml
theme = dark:oxide,light:your-light-theme
```

Ghostty will automatically switch based on your system appearance.

## Color Palette

oxide uses OKLCH color space for precise, perceptually uniform colors:

- **Background**: Deep void-like `#161616` for optimal readability
- **Foreground**: Crisp `#cecece` text that doesn't strain your eyes
- **Accents**: 9 semantic colors with consistent lightness values
- **ANSI Colors**: Full 16-color palette optimized for terminal applications

## Contributing

We follow the same philosophy as the main oxide project: minimalism doesn't mean stagnation.

- Report issues through [GitHub Issues](https://github.com/oxidescheme/ghostty/issues)
- PRs that improve clarity and consistency are welcome
- Ensure changes align with oxide's functional aesthetic

## License

MIT License - see [LICENSE](LICENSE) for details.

<p align="center">
Copyright &copy; 2025-present oxidescheme
</p>

