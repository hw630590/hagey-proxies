# Proxies
- VPS IS A BIT SLOW SORRY YALL

## Introduction
This repository contains a regularly updated list of **SOCKS4 proxies** in CSV format. The list is refreshed every 10 minutes using a VPS, ensuring up-to-date proxy information.

### Current Features
- **SOCKS4 proxies**: The main focus is on SOCKS4 proxies, with details including IP, port, protocol, country, region, city, provider, and ISP.
- **Automatic Updates**: The list is automatically fetched and updated every 10 minutes.
  
### Coming Soon:
- **HTTP/HTTPS proxies**
- **SOCKS5 proxies**

## Data Format
The data is stored in a **CSV** file, which contains the following columns:
- `IP`: The proxy server's IP address.
- `Port`: The port number used by the proxy.
- `Protocol`: The protocol used by the proxy (currently only `socks4`).
- `Country`: The country where the proxy is located.
- `Region`: The region of the proxy server.
- `City`: The city where the proxy is located.
- `Provider`: The name of the provider hosting the proxy.
- `ISP`: The ISP providing the proxy service.
- `Last Checked`: The timestamp of the last time the proxy list was updated.

## How It Works
1. **Proxy Scraping**: The list of SOCKS4 proxies is fetched from a public proxy source.
2. **Geolocation**: Each proxy is processed to obtain its country, region, city, and provider details using the [ip-api](http://ip-api.com).
3. **Update Frequency**: The CSV file is updated every 10 minutes to keep the list current.

## Future Updates
We are working on adding support for other proxy types, including:
- **HTTP proxies**
- **HTTPS proxies**
- **SOCKS5 proxies**

## Contributions
Feel free to contribute by suggesting new proxy sources or improvements. We also welcome contributions to expand the list of supported proxy types.

## License
This project is open-source and available under the MIT License.

