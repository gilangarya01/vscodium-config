# VSCodium Configuration

This repository contains my custom configuration for VSCodium and installed extensions. By storing these configurations here, I can easily set up VSCodium on any new system and ensure a consistent development environment.

## Installation

To use this configuration, follow the steps below:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/vscodium-config.git
   cd vscodium-config
   ```

2. **Copy Configuration Files**

   Copy the configuration files to your VSCodium user settings directory.

   ```bash
   cp -r settings.json ~/.config/VSCodium/User/
   ```

3. **Install Extensions**

   Install the extensions listed in `vscodium-extensions.txt`.

   ```bash
   cat vscodium-extensions.txt | xargs -L 1 codium --install-extension
   ```
