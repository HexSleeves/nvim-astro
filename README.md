# 🚀 HexSleeves' AstroNvim Configuration

My personal AstroNvim configuration, crafted for maximum productivity and a seamless development experience. This setup leverages the power of AstroNvim v4+ with carefully selected plugins and AI-powered tools.

## ✨ Features

### 🎨 UI & Appearance

- **Custom Dashboard**: Beautiful ASCII art header with AstroNvim branding
- **Modern Icons**: Carefully selected icons throughout the interface
- **Optimized Colorscheme**: Clean and readable color scheme configuration

### 🤖 AI Integration

- **Augment.vim**: Advanced AI-powered coding assistance
- **CodeCompanion**: Intelligent code completion and suggestions
- **Aider**: AI pair programming with automatic context management

### 🛠️ Development Tools

- **LSP Integration**: Full Language Server Protocol support via AstroLSP
- **Mason**: Automatic LSP server, DAP server, linter, and formatter management
- **Treesitter**: Advanced syntax highlighting and code understanding
- **None-ls**: Additional linting and formatting capabilities

### 📝 Code Enhancement

- **Discord Presence**: Show your coding activity on Discord
- **LSP Signature**: Function signature help while typing
- **Auto Pairs**: Smart bracket and quote pairing with custom rules
- **LuaSnip**: Powerful snippet engine with custom configurations

### ⚡ Performance

- **Lazy Loading**: Optimized plugin loading for fast startup times
- **Efficient Configuration**: Modular setup for easy maintenance and customization

## �️ Installation

### Prerequisites

- **Neovim 0.9.0+** (recommended: latest stable)
- **Git** for cloning repositories
- **A Nerd Font** for proper icon display
- **Node.js** (for some LSP servers)
- **Python 3** (for some tools and formatters)

### Quick Setup

1. **Backup your existing Neovim configuration** (if any):

   ```bash
   mv ~/.config/nvim ~/.config/nvim.backup
   mv ~/.local/share/nvim ~/.local/share/nvim.backup
   mv ~/.local/state/nvim ~/.local/state/nvim.backup
   mv ~/.cache/nvim ~/.cache/nvim.backup
   ```

2. **Clone this configuration**:

   ```bash
   git clone https://github.com/HexSleeves/nvim-astro.git ~/.config/nvim
   ```

3. **Start Neovim**:

   ```bash
   nvim
   ```

4. **Wait for plugins to install** - AstroNvim will automatically install all plugins on first launch.
