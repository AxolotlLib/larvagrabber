# Larva Grabber

**Larva Grabber** is a tool built using HTML and JavaScript that retrieves the IP information of a user and sends it to a specified Discord webhook. This tool is created for **educational purposes** to demonstrate how web requests can interact with APIs and webhooks.

## Features

- Retrieves detailed IP address information such as:
  - IP Address
  - Location (City, Region, Country, Latitude, Longitude, ZIP)
  - Internet Service Provider (ISP)
  - Additional device and network info (User Agent, Screen Resolution, Timezone, etc.)
- Sends the collected data to a Discord webhook for logging

## Example of Grabbed IP Information

Larva Summary Larva Grabbed. IP Address: [REDACTED] Location: [REDACTED], [REDACTED], [REDACTED], Lat: [REDACTED], Lon: [REDACTED], ZIP: [REDACTED] Provider: [REDACTED], ASN: [REDACTED]

Additional Info:

Time Zone: [REDACTED] Proxy/VPN: [REDACTED] Hostname: [REDACTED] Organization: [REDACTED] Mobile Carrier: [REDACTED]

Device Info:

Screen Resolution: [REDACTED] User Agent: [REDACTED] Platform: [REDACTED] Language: [REDACTED] Timezone: [REDACTED] Cookies Enabled: [REDACTED] Plugins: [REDACTED]

## Usage

1. Clone or download the repository.
2. Update the `index.html` file with your Discord webhook URL by replacing `'DISCORD_WEBHOOK_URL'` in the script section.
3. Open the `index.html` file in any web browser.
4. The IP information will be sent to the specified Discord webhook.

## Disclaimer

This tool is designed for **educational purposes only**. The creator is not responsible for any misuse, such as attacks, doxxing, or unauthorized data collection. Ensure you have the **consent** of the user before retrieving and sending their IP information. Use this tool responsibly and comply with all applicable laws and regulations.

