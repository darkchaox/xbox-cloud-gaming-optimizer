# Xbox Cloud Gaming Optimizer

> A userscript for Xbox Cloud Gaming that helps handle regional restrictions, displays streaming metrics, and provides visual and control experience adjustments.

<div align="center">

[简体中文](README.md) | **English**

</div>

<div align="center">

[**Install Latest Version**](https://raw.githubusercontent.com/darkchaox/xbox-cloud-gaming-optimizer/main/Xbox-Cloud-Gaming-Optimizer.user.js) | [**Greasy Fork**](https://greasyfork.org/zh-CN/scripts/588851-xbox-cloud-gaming%E4%BC%98%E5%8C%96%E6%95%B4%E5%90%88) | [**Report an Issue**](https://github.com/darkchaox/xbox-cloud-gaming-optimizer/issues)

</div>

This project is provided free of charge. Obtain the script only from this GitHub repository or Greasy Fork. Do not trust paid copies or unofficial reuploads.

## What does this script do?

- **Handle regional restrictions**: Provides direct connection without a proxy, server selection, and custom IP options to help address Xbox Cloud Gaming regional restrictions.
- **Monitor streaming status**: Displays frame rate, latency, bitrate, resolution, and other metrics for evaluating stream quality.
- **Adjust video and codec settings**: Provides 720p/1080p options, browser codec preferences, aspect ratio controls, and brightness, contrast, saturation, and sharpness adjustments.
- **Improve controls and usability**: Provides automatic fullscreen behavior and options to show or suppress touch controls.
- **Provide common advanced settings**: Includes game language, IPv6 preference, network diagnostics, and physical server options.

Available features may vary by account permissions, service region, browser, device, and network environment. Use the settings panel shown on the game page as the authoritative source.

## Settings panel preview

![Xbox Cloud Gaming Optimizer settings panel](assets/settings-panel.png)

## Quick start

### 1. Install a userscript manager

Install one compatible userscript manager in your browser:

- [Tampermonkey](https://www.tampermonkey.net/)
- [Violentmonkey](https://violentmonkey.github.io/)

### 2. Install the script

Click [**Install Latest Version**](https://raw.githubusercontent.com/darkchaox/xbox-cloud-gaming-optimizer/main/Xbox-Cloud-Gaming-Optimizer.user.js), then confirm installation in the userscript manager.

### 3. Open Xbox Cloud Gaming

Open either URL and start a game:

- `https://www.xbox.com/play`
- `https://play.xbox.com/`

After entering a game, open the script settings panel. Verify streaming and controls with the default settings before changing individual options.

## Usage recommendations

1. **Resolve regional availability first**: When regional restrictions occur, try direct connection without a proxy, server selection, and custom IP in that order.
2. **Change one option at a time**: After modifying resolution, codec preference, or image settings, check for changes to video, audio, input, and connectivity.
3. **Restore defaults after errors**: If you encounter a black screen, control problems, audio issues, or connection failures, revert the latest changes and reload the page.
4. **Keep a record of important settings**: Before updating the script, record any custom configuration you need to preserve.

## Important notes

- This script does not provide Xbox Game Pass, cloud gaming access, game content, or internet service.
- Regional availability, image quality, latency, and stability depend on the account, device, network, browser, service region, and Xbox service status. The script cannot guarantee that restrictions will be bypassed or performance will improve in every environment.
- Comply with applicable local laws and the Microsoft/Xbox terms of service.
- GitHub hosts the source code, documentation, and issue tracker. Greasy Fork is the official installation and automatic update channel.

## FAQ

### The script does not work after installation. What should I check?

Confirm the following in order:

1. Tampermonkey or Violentmonkey is enabled;
2. The script is enabled in the userscript manager;
3. The current page is `xbox.com/play` or `play.xbox.com`;
4. The Xbox Cloud Gaming page has been reloaded;
5. Other extensions that may modify Xbox web pages have been temporarily disabled.

### Why did latency or image quality not improve after changing settings?

Streaming performance depends on network quality, device performance, browser codec support, service region, and Xbox server status. The script provides configuration options and diagnostic information, but it cannot guarantee improvement on every network.

## Reporting issues

Report problems through [GitHub Issues](https://github.com/darkchaox/xbox-cloud-gaming-optimizer/issues) and include, where possible:

- Browser, operating system, and userscript manager versions;
- Steps to reproduce, expected behavior, and actual behavior;
- Error messages or screenshots that are safe to share publicly.

Do not submit passwords, cookies, tokens, personal data, or other sensitive information.

## Acknowledgements

This project is **not an original userscript built from scratch**. The current version is based on the Xbox Cloud Gaming optimization userscript consolidated and shared by **奈非天**, with subsequent maintenance and improvements.

Thanks to the **better-xcloud** project and to **奈非天** for prior development, consolidation, and sharing. Copyright and license notices for relevant upstream code are retained in the source. See [NOTICE.md](NOTICE.md) for details.

## Changelog

See [CHANGELOG.md](CHANGELOG.md).
