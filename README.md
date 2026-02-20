# Google-Home-Script-Editor

Automation Examples Library

A curated collection of 22 ready-to-use YAML automation scripts for the 
Google Home Script Editor. This library covers a wide range of common 
smart home scenarios, from basic switch control to safety alerts and 
presence-based routines.

## Contents

| # | Automation | Description |
|---|-----------|-------------|
| 1 | Switch-Controlled Light | Turn on a light via a switch |
| 2 | Nighttime Dim Lights and Close Blinds | Schedule lights and blinds at 10pm |
| 3 | Person Detection Cameras | Disable cameras when someone arrives home |
| 4 | Empty Home Vacuum | Run vacuum when home is unoccupied |
| 5 | Nighttime Lights and Blinds | Dim lights and close blinds when TV turns on after dark |
| 6 | Cool Weather Heating | Adjust heating when temperature drops below 18°C |
| 7 | Warm Weather Ventilation | Adjust cooling when temperature exceeds 25°C |
| 8 | Scheduled Lighting | Multi-time lighting schedule tied to sunset |
| 9 | Synchronize Two Lights | Mirror the on/off state of two lights |
| 10 | Smoke Detector Lights | Flash lights red and blue when smoke is detected |
| 11 | Low Air Quality Air Purifier | Run purifier at high speed when air quality is poor |
| 12 | Nighttime Unlocking Lights | Turn on lights at full brightness when door unlocks at night |
| 13 | Carbon Monoxide Detection Lights | Pulse lights when CO is detected |
| 14 | Motion Detection Lights | Lights on with motion, off after 5 minutes of stillness |
| 15 | Occupancy Sensor Lights | Lights controlled by occupancy sensor |
| 16 | Occupancy Sensor Cameras | Enable cameras when home is empty |
| 17 | Doorbell Light Alert | Pulse lights when doorbell rings and room is occupied |
| 18 | Movie Night Scene | Voice-triggered blinds, lights, and appliance control |
| 19 | Home and Away Lighting | Presence-based lighting for arrival and departure |
| 20 | Package Delivered | Notification alert when a package is detected |
| 21 | Open Blinds | Open blinds on first morning motion, suppressed for 20 hours |
| 22 | Motion at Home | Weekday motion notification from multiple sensors |

## Usage

1. Open the [Google Home app](https://home.google.com)
2. Navigate to **Automations → Script Editor**
3. Copy and paste any script from this library
4. Replace device names and room names to match your own setup
   - Format: `Device Name - Room Name`
5. Save and activate the automation

## Customization

Each script uses placeholder device names. Before deploying, update:
- Device names to match your Google Home device list
- Room names to match your home structure
- Thresholds (temperature, brightness, time) to your preferences
- Email addresses in notification actions

## Requirements

- A Google account with Google Home set up
- Compatible smart home devices linked to Google Home
- Access to the Script Editor (available in the Google Home app)

## Contributing

Contributions are welcome! If you have a useful automation to add, please 
open a pull request with your YAML script and a short description.

## License

This project is licensed under the MIT License. See `LICENSE` for details.
