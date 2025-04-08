# releases

## Installation

To install Any's Trivy version, run the following command:

```bash
curl -sfL  https://raw.githubusercontent.com/buildecho/releases/main/install.sh | sudo sh -s -- -b /usr/local/bin latest
```

Available flags:

- `-d`: Enable debug mode
- `-b <path>`: Specify the path where the trivy binary should be installed (default: /usr/local/bin)
