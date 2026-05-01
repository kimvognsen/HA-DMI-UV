# Home Assistant DMI UV

DMI UV forecast for Home Assistant using DMI's public UV endpoint.

Provides:
- Current UV index
- Today's max UV index
- Hourly UV forecast graph
- DMI-style color thresholds
- Optional conditional display when UV is relevant

## Requirements

- Home Assistant
- ApexCharts Card
- card-mod optional, not required

## Installation

1. Copy `packages/dmi_uv.yaml` to:

```yaml
/config/packages/dmi_uv.yaml
