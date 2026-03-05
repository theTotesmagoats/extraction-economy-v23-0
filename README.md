# Extraction Economy v23.0 - Fixed Version

[View Live Game](https://github.com/theTotesmagoats/extraction-economy-v23-0) | [Report Issues](https://github.com/theTotesmagoats/extraction-economy-v23-0/issues)

## Overview

A startup simulation game about platform economics, extraction protocols, and fiduciary pressure. You play as the CEO of Cander Creative, a venture-backed startup trying to balance growth with shareholder expectations.

## Bug Fixes Applied (v23.1)

This fixed version addresses several critical bugs from the original:

### 1. **Fixed Missing DOM Element References** 
- **Issue**: Code referenced non-existent `threat_label` element
- **Fix**: Updated all references to use `g_thr_val` instead
- **Impact**: Eliminates JavaScript errors in init() and acquire_competitor() functions

### 2. **Added Trend Arrows to Threat Gauge**
- **Enhancement**: Added visual trend indicators (▲▼) to the threat gauge
- **Fix**: Now shows whether competitor threat is increasing or decreasing, consistent with other gauges

### 3. **Improved Error Handling**
- **Enhancement**: Better null checks and element validation throughout the codebase
- **Impact**: More robust gameplay experience with fewer unexpected crashes

## How to Play

1. **Clone this repository** or download `index.html`
2. **Open in your browser** - no server needed!
3. **Balance growth vs extraction** - Early open-market protocols build TAM, later lock-in protocols maximize profits
4. **Manage board patience** - Miss targets too often and you'll be fired
5. **Watch for competitor threats** - Build dependency before competitors break your lock-in

## Game Mechanics

- **Market Expansion Phase**: Use universal interoperability, privacy, and transparent billing to grow TAM
- **Lock-in Phase**: Deploy cloud subsidies, proprietary formats, and SaaS transitions to build dependency
- **Extraction Phase**: Implement algorithmic pricing, cancel friction, hidden fees, and telemetry brokering
- **Political Capital**: Lobby for regulatory moats while managing public perception

## Key Changes from Original

| Feature | Original | Fixed Version |
|---------|----------|---------------|
| Threat Label Display | ❌ Crashes | ✅ Working |
| Threat Trend Arrows | ❌ Missing | ✅ Added |
| DOM Element Safety | ⚠️ Basic | ✅ Enhanced |

## Repository Structure

```
extraction-economy-v23-0/
├── index.html          # Main game file (all-in-one)
└── README.md           # This documentation
```

## Technical Details

- **Language**: HTML5 + Vanilla JavaScript
- **No external dependencies** - runs entirely client-side
- **LocalStorage support** for high scores
- **Responsive design** with mobile support

## Credits

Original game concept and implementation by theTotesmagoats.

Fixed version developed to resolve critical bugs affecting gameplay stability.

## License

This project is provided as-is for educational and entertainment purposes.