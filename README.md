# Tooling Website

[![nginx 1.17.2](https://img.shields.io/badge/nginx-1.17.2-brightgreen.svg?&logo=nginx&logoColor=white&style=for-the-badge)](https://nginx.org/en/CHANGES) [![php 8.3](https://img.shields.io/badge/php--fpm-8.3-blue.svg?&logo=php&logoColor=white&style=for-the-badge)](https://www.php.net/releases/8_3_0.php)

## Introduction

This repository hosts the code for the StegTechHub tooling website. The website provides a centralized platform for accessing various development tools and resources.

## Technologies Used

The project leverages the following technologies:

- **Backend:**
  - PHP 8.3
  - MySQL
- **Web Server:**
  - Nginx 1.17.2
- **Frontend:**
  - HTML
  - CSS
  - Tailwind CSS (Utility-first CSS framework)
- **Other:**
  - Docker (For containerization)
  - Composer (For PHP dependency management)
 
### Contributors
  - StegHub (Author)
  - Chime Kingsley (onlinekingsley@gmail.com)

## Getting Started
1. Clone the repository
```bash
git clone https://github/Chimekinglsey/tooling-website.git
```

### Versioning

| Docker Tag | GitHub Release | Nginx Version | PHP Version | Ubuntu Version |
|-----|-------|-----|--------|--------|
| latest | master Branch |1.17.2 | 8.3 | Latest |

## License
This project is open-source and is licensed under the [MIT License](LICENSE).
### Docker Information
- **Docker Hub:** [steghub/tooling-website](https://hub.docker.com/r/steghub/tooling-website)

## Testing Publish Over SSH
1. Storing artifacts in a remote server
2. Testing the publish over SSH plugin with updated access rights
3. Configure a new NFS server after the old one root access was messed up 