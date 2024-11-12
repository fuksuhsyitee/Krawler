### README.md

```markdown
# Web Crawler Application

This project is a web application for crawling the internet and gathering a large list of URLs. It is developed using Golang for the backend and Angular for the frontend, and it utilizes Docker for containerization. The application is designed to be scalable and secure, with support for deployment on Alibaba Cloud.
Was co-created with the help of gpt-4o. 

## Table of Contents
- [Features](#features)
- [Architecture](#architecture)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Features
- Crawl websites and collect URLs.
- Real-time progress updates.
- Export crawled URLs in various formats.
- Secure user authentication.
- Responsive dashboard interface.

## Architecture
- **Frontend**: Angular
- **Backend**: Golang
- **Database**: PostgreSQL
- **Containerization**: Docker

## Getting Started

### Prerequisites
- [Docker](https://www.docker.com/)
- [Node.js](https://nodejs.org/) (for Angular development)
- [Go](https://golang.org/) (for Golang development)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/web-crawler-app.git
   cd web-crawler-app
   ```

2. **Setup backend**:
   - Navigate to the `backend` directory and run:
   ```bash
   go mod download
   ```

3. **Setup frontend**:
   - Navigate to the `frontend` directory and run:
   ```bash
   npm install
   ```

### Usage

1. **Run Docker Compose**:
   ```bash
   docker-compose up --build
   ```

2. **Access the application**:
   - Frontend: `http://localhost:4200`
   - Backend API: `http://localhost:8080`

## Deployment

For deploying on Alibaba Cloud, refer to the [Alibaba Cloud Deployment Guide](./docs/alibaba-cloud-deployment.md).

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) file for guidelines on how to contribute to this project.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
```
