# DNS Switcher

A simple Bash script to quickly switch your system DNS servers to popular providers like Shecan, Radar, Electro, Google, and more — designed for gaming, reduced ping, bypassing censorship, and stable connections.

🇮🇷 Built for users in Iran and anyone looking for fast and reliable DNS switching.

## Features

* Interactive CLI to choose DNS providers
* Auto backup of `/etc/resolv.conf`
* Supports public and local DNS:

  * Shecan
  * Radar
  * Electro
  * DNS Pro
  * DynX
  * 403
  * Begzar
  * Google
  * Cloudflare
* Includes “Reset to Default” option (127.0.0.53)
* Preserves custom `options` and `search` lines

## Usage

```bash
git clone https://github.com/Linuxmaster14/dns-switcher.git
cd dns-switcher
chmod +x dns-switcher.sh
sudo ./dns-switcher.sh
```

⚠️ You must run the script with `sudo` or as root to update system DNS.

## Supported DNS Providers

This script includes a curated list of reliable DNS servers used widely in Iran for bypassing restrictions and improving latency:

| Provider        | Primary IP     | Secondary IP   |
| --------------- | -------------- | -------------- |
| Shecan          | 178.22.122.100 | 185.51.200.2   |
| Radar           | 10.202.10.10   | 10.202.10.11   |
| Electro         | 78.157.42.100  | 78.157.42.101  |
| Begzar          | 185.55.226.26  | 185.55.226.25  |
| DNS Pro         | 87.107.110.109 | 87.107.110.110 |
| DynX            | 10.70.95.150   | 10.70.95.162   |
| 403.            | 10.202.10.202  | 10.202.10.102  |
| Google          | 8.8.8.8        | 8.8.4.4        |
| Cloudflare      | 1.1.1.1        | 1.0.0.1        |

## License

MIT – free for personal and commercial use.
See [`LICENSE`](./LICENSE) for details.

## Author

Made with [Linuxmaster14](https://github.com/Linuxmaster14)
