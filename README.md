# Proxies

## Introduction
This repository contains a regularly updated list of **HTTP/HTTPS/SOCKS4/SOCKS5 proxies** in CSV format. The list is refreshed randomly by, ensuring up-to-date proxy information.

### Current Features
- **HTTP/HTTPS/SOCKS4/SOCKS5 proxies**: The main focus is on SOCKS4 proxies, with details including IP, port, protocol, country, region, city, provider, and ISP.
- **Random Updates**: The list is updated randomly and checked by me manually..
  
### Coming Soon:
- **HTTPS proxies**
- **SOCKS5/SOCKS4 proxies**

## Data Format
The data is stored in a **CSV** file, which contains the following columns:
- `Proxy` - The main proxy with ip:port
- `Country` - The country of the proxy. May return unknown.
- `Region` - The region of the proxy. May return unknown.
- `City` - The city of the proxy. May return unknown.
- `Location` - The North and South estimated location.
- `Organization` - Whoever is hosting the proxy.
- `Error` - Not that important, just for errors with proxies.

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

