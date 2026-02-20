# Google Home YAML Automation Collection

A collection of 22 original, ready-to-use YAML automation scripts for the
Google Home Script Editor. Covers everyday smart home scenarios including
lighting, climate control, security, presence detection, and more.

> **Note:** All device and room names are illustrative placeholders.
> Replace them with your own before deploying (`Device Name - Room Name`).

## Scripts Included

| # | File | Automation |
|---|------|-----------|
| 1 | `01-switch-controlled-light.yaml` | Bedside switch controls lamp |
| 2 | `02-nighttime-dim-lights-close-blinds.yaml` | Wind-down routine at 9pm |
| 3 | `03-person-detection-cameras.yaml` | Disable cameras on arrival |
| 4 | `04-empty-home-vacuum.yaml` | Auto-vacuum when nobody is home |
| 5 | `05-nighttime-lights-and-blinds.yaml` | Cinema mode when TV turns on at night |
| 6 | `06-cool-weather-heating.yaml` | Cold morning comfort routine |
| 7 | `07-warm-weather-ventilation.yaml` | Hot day cooling routine |
| 8 | `08-scheduled-lighting.yaml` | Evening porch light schedule |
| 9 | `09-synchronize-two-lights.yaml` | Mirror hallway and staircase lights |
| 10 | `10-smoke-detector-lights.yaml` | Strobe alert on smoke detection |
| 11 | `11-low-air-quality-purifier.yaml` | Boost air purifier on poor air quality |
| 12 | `12-nighttime-unlocking-lights.yaml` | Entry light on nighttime unlock |
| 13 | `13-carbon-monoxide-detection-lights.yaml` | Pulse lights on CO alert |
| 14 | `14-motion-detection-lights.yaml` | Garage motion-activated light |
| 15 | `15-occupancy-sensor-lights.yaml` | Bathroom occupancy light |
| 16 | `16-occupancy-sensor-cameras.yaml` | Activate cameras when home is empty |
| 17 | `17-doorbell-light-alert.yaml` | Doorbell flash alert for home office |
| 18 | `18-movie-night-scene.yaml` | Game night voice scene |
| 19 | `19-home-and-away-lighting.yaml` | Arrival and departure lighting |
| 20 | `20-package-delivered.yaml` | Parcel delivery alert |
| 21 | `21-open-blinds-morning-motion.yaml` | Open blinds on first morning movement |
| 22 | `22-motion-at-home-weekday.yaml` | Unexpected weekday motion alert |

## Usage

1. Open the [Google Home app](https://home.google.com)
2. Go to **Automations → Script Editor**
3. Copy and paste any script from the `automations/` folder
4. Replace all placeholder device and room names with your own
5. Save and activate

## Customization

Before deploying, update:
- Device and room names to match your Google Home setup
- Temperature thresholds, brightness levels, and time schedules
- Email addresses in notification actions
- `suppressFor` durations to suit your routine

## Requirements

- A Google account with Google Home configured
- Compatible smart home devices linked to Google Home
- Access to the Google Home Script Editor

## Contributing

Pull requests are welcome. Add new `.yaml` files to the `automations/`
folder using the `##-short-description.yaml` naming convention.

## License

Licensed under the MIT License. See `LICENSE` for details.
