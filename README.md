# Nginx Proxy Manager

This repository is based on [`nginx-proxy-manager`](https://nginxproxymanager.com/) and allows easy forwarding to websites with free SSL, requiring minimal knowledge of Nginx or LetsEncrypt.

## 📌 Table of Contents
- [Quick Start](#-quick-start)
- [Features](#-features)
- [Installation](#-installation)
- [License](#-license)
- [Contributors](#-contributors)
- [Support](#-support)

## 🚀 Quick Start

### Clone the repository
```shell
git clone https://github.com/focela/npm.git \
    && cd npm \
    && cp .env.example .env
```

### Start the service
```shell
docker-compose up -d
```

## 🛠 Features

- User-friendly admin interface
- Simple domain forwarding, redirections, and 404 hosts
- Free SSL via Let's Encrypt or custom certificates
- Access control and HTTP authentication
- Advanced Nginx configuration for power users
- User management and audit logs

## 🔧 Installation

1. Install Docker & Docker-Compose:
    - [Docker Install](https://docs.docker.com/install/)
    - [Docker-Compose Install](https://docs.docker.com/compose/install/)

2. Edit `.env` file with your configuration.

3. Start the service:
```shell
docker-compose up -d
```

## 📄 License

NPM is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

## 🤝 Contributors

Thanks to our [contributors](https://github.com/focela/npm/graphs/contributors). Contributions are welcome!

## 💬 Support

If you encounter any issues, please open an issue in the repository:  
[GitHub Issues](https://github.com/focela/npm/issues)