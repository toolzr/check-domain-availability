# Check Domain Availability

A JavaScript-based open-source utility designed to check the availability of domain names across multiple TLDs. This tool is useful for developers, businesses, and individuals who need a quick and reliable way to verify domain availability without relying on registrar lookups.

## Features

- **Supports Multiple TLDs**: Automatically checks common TLDs like `.com`, `.net`, `.org`, `.io`, `.cc`, `.me`, `.info`, `.top`, `.online`, `.xyz`.
- **Direct TLD Input**: Allows users to check domains with any existing TLD, e.g., `example.de`.
- **RDAP Lookup**: Uses RDAP (Registration Data Access Protocol) to query domain registration records.
- **Fallback DNS Check**: If RDAP is inconclusive, the tool verifies whether the domain resolves.
- **Simple and Fast**: Easy-to-use interface for quick availability checks.

## Usage

The online version can be found at [toolzr.com/domain-availability](https://toolzr.com/domain-availability).

This tool is open-source and licensed under the MIT License. You can use it online or locally by cloning this repository and opening `check-domain-availability.html` in your browser.

```bash
git clone https://github.com/toolzr/check-domain-availability.git
```

## Contributing

Contributions are welcome! If you find bugs or have ideas for improvements, feel free to open an issue or submit a pull request.

## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE.md) file for details.

## About

This tool was created as an alternative to TLD-List.com, which is often down. While alternatives like DomComp.com and TLDES.com exist for price comparisons, they lack a comprehensive domain availability checker. Our tool fills that gap by providing an accurate and efficient way to check domain availability.
