# PlatPingLib
https://pypi.org/project/platPingLib/

A simple Python library to perform ping operations across platforms. `PlatPingLib` provides an easy-to-use function `ping_ip` that allows you to check the reachability of a given IP address in your network.

## Features

- Cross-platform support (Windows, Linux, macOS)
- Simple interface to ping IP addresses
- Customizable timeouts

## Installation

To install `PlatPingLib`, simply use pip:

```bash
pip install PlatPingLib
```
Usage

Here is a quick example of how to use PlatPingLib:

```python

from PlatPingLib import ping_ip

# Ping an IP address
ip_address = "8.8.8.8"
if ping_ip(ip_address):
    print(f"Successfully pinged {ip_address}")
else:
    print(f"Failed to ping {ip_address}")
```
Requirements

    Python 3.6+

Contributing

Contributions are welcome! Please feel free to submit a pull request.
Support

If you have any issues or questions, please open an issue on the GitHub repository.


    Caleb Finigan - Initial work - CalebFin

