# Aqua Flower ESPHome Configuration

This repository contains ESPHome configuration files for the Aqua Flower project. These configurations include a custom card and a custom dashboard that users can copy and paste into their Home Assistant setup.

## Prerequisites

Before using the custom card and dashboard, ensure that you have the following Home Assistant Community Store (HACS) Frontend Integrations and HACS Integrations installed:

### HACS Frontend Integrations:
- **[custom:layout-card](https://github.com/thomasloven/lovelace-layout-card)**: A custom layout card for Lovelace that allows for flexible card layouts.
- **[custom:mushroom-number-card](https://github.com/piitaya/lovelace-mushroom)**: Part of the Mushroom UI collection, this card is used for number displays in the dashboard.
- **[custom:mini-graph-card](https://github.com/kalkih/mini-graph-card)**: A minimalistic and customizable graph card for Lovelace.

### HACS Integrations:
- **[Card Mod](https://github.com/thomasloven/lovelace-card-mod)**: This integration allows you to apply custom styles to Lovelace cards.
- **[Theme: ios-dark-mode-light-blue-alternative](https://github.com/basnijholt/lovelace-ios-dark-mode-theme)**: A custom theme that enhances the visual appearance of your Home Assistant dashboard.

## Installation

1. **Install Required Integrations:**
   - Use HACS in Home Assistant to install the required frontend integrations and themes mentioned above.

2. **Copy YAML Files:**
   - Download or copy the YAML files from this repository and paste them into your Home Assistant's Lovelace configuration.

3. **Add Custom Card and Dashboard:**
   - Open Home Assistant and navigate to the `Configuration` → `Lovelace Dashboards`.
   - Create a new dashboard or edit an existing one.
   - Paste the content of the YAML files into the appropriate Lovelace dashboard configuration.

4. **Save and Reload:**
   - Save your configuration and reload your Home Assistant dashboard to see the changes.

## Usage

Once everything is set up, the custom card and dashboard will provide enhanced control and visualization for your Aqua Flower system within Home Assistant.

## Troubleshooting

If you encounter any issues, ensure that all the required integrations and frontend cards are installed and up to date. Refer to the respective GitHub repositories for further instructions or troubleshooting tips.

## Contributions

Feel free to contribute to this project by submitting pull requests or opening issues on GitHub. Your feedback and improvements are always welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
