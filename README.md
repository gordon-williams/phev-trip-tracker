# PHEV Trip Tracker

A web-based trip tracking application for Plug-in Hybrid Electric Vehicles (PHEVs) and Battery Electric Vehicles (BEVs). Track fuel stops, charging sessions, and analyse trip economics including cost comparisons and carbon footprint calculations.

## Features

- **Trip Management**: Create and manage multiple trips with waypoints
- **Fuel & Charging Tracking**: Log fuel stops and EV charging sessions (AC/DC)
- **Vehicle Profiles**: Configure multiple vehicles with custom specifications
- **Trip Economics**: Compare DC charging costs vs ICE generation costs
- **Carbon Footprint**: Calculate and compare CO₂ emissions between charging and ICE
- **HEV Equivalent**: View combined fuel+electric consumption as L/100km
- **Camp Mode**: Track Power-to-Load (PTL) usage while camping
- **Offline Support**: Works without internet connection
- **Cloud Sync**: Optional Dropbox backup and sync
- **Data Export**: Export trip data as CSV

## Versions

- **`index.html`** - Desktop/tablet version with full-width layout
- **`index-mobile.html`** - Mobile-optimised version with iOS-style interface

## Quick Start

1. Download or clone this repository
2. Open `index.html` (desktop) or `index-mobile.html` (mobile) in a web browser
3. Create a new trip and start logging entries

No server or installation required - runs entirely in the browser using localStorage.

## Vehicle Configuration

The app supports configurable vehicle profiles including:

- Battery capacity and degradation
- Fuel tank size and reserve
- Engine thermal efficiency
- Home charging cost
- Fuel gauge calibration curve

Default values are provided for the BYD Shark 6, but any PHEV or BEV can be configured.

## Trip Economics

The economics analysis compares:

- **For PHEVs**: DC charging cost vs what the ICE would have cost to generate the same energy
- **For BEVs**: DC charging cost vs home charging cost

Includes break-even price calculation and carbon footprint comparison.

## Data Storage

- **Local**: All data stored in browser localStorage
- **Cloud**: Optional Dropbox integration for backup and cross-device sync

## Browser Support

Modern browsers with ES6+ support:
- Chrome/Edge (recommended)
- Firefox
- Safari

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgements

- Built with assistance from Claude (Anthropic)
- Inspired by the need to track real-world PHEV efficiency and costs
