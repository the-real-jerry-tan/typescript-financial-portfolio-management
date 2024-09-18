# Financial Portfolio Management System with TypeScript and Node.js

## Project Description

This project demonstrates a financial portfolio management system using Node.js and TypeScript. It provides a REST API to create, manage, and optimize financial portfolios, and integrates with real-time financial data for portfolio tracking and optimization.

## Features

- **Portfolio Management**: Create and manage portfolios with assets like stocks and crypto.
- **Portfolio Optimization**: Implement algorithms like Markowitz Efficient Frontier (future).
- **API Integration**: Pull real-time stock and crypto data from external APIs (future).
- **REST API**: Expose endpoints for creating, managing, and optimizing portfolios.
- **Dockerized**: The application is containerized for easy deployment and scaling.

## Setup Instructions

### Prerequisites
- **Docker**: To run the application in containers.
- **Node.js**: Version 14 or later.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/the-real-jerry-tan/typescript-financial-portfolio-management.git
   cd typescript-financial-portfolio-management
   ```

2. Build and run the Docker container:
   ```bash
   cd docker
   docker build -t ts-financial-portfolio .
   docker run -p 3000:3000 ts-financial-portfolio
   ```

3. The REST API will be available at [http://localhost:3000](http://localhost:3000).

## Future Enhancements

- **Portfolio Optimization Algorithms**: Implement advanced algorithms for risk and performance.
- **Integration with Real-Time Data**: Connect to APIs like Alpha Vantage for real-time stock data.
- **Advanced Risk Metrics**: Add risk metrics like Sharpe ratio, VaR, etc.

## Author

This project is maintained by [Jerry Tan](https://github.com/the-real-jerry-tan).

## License

© 2024 Jerry Tan. All Rights Reserved. Unauthorized use or distribution is prohibited.
