# ZMK Configuration for 7skb

Generated from QMK info.json

## Keyboard Information
- Name: 7skb
- Type: Split
- Normalized Name: 7skb
- Board: bmp_boost

## Files Structure

### Split Keyboard Files
- boards/shields/7skb/7skb_left.overlay - Left side hardware definition
- boards/shields/7skb/7skb_right.overlay - Right side hardware definition
- boards/shields/7skb/7skb_left.conf - Left side configuration
- boards/shields/7skb/7skb_right.conf - Right side configuration

### Common Files
- boards/shields/7skb/layouts.dtsi - Physical layout definition
- boards/shields/7skb/Kconfig.defconfig - Default configuration
- boards/shields/7skb/Kconfig.shield - Shield configuration
- boards/shields/7skb/7skb.zmk.yml - ZMK metadata
- boards/shields/7skb/7skb.keymap - Shield keymap include
- config/keymap.keymap - Keymap definition
- config/info.json - Keyboard layout information for keymap editors
- config/west.yml - West manifest for ZMK dependencies
- build.yaml - Build configuration for ZMK
- zephyr/module.yml - Zephyr module configuration
- .github/workflows/build.yml - GitHub Actions workflow for building firmware

## Usage
1. Copy all files to your ZMK config repository
2. Customize the keymap in config/keymap.keymap as needed
3. Push to GitHub to trigger automatic firmware builds

## Board Information
This configuration is set up for bmp_boost. The board is from sekigon-gonnoc's repository.
