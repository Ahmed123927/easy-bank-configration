# Easy Bank Configuration

## Overview
This repository contains the configuration setup for the Easy Bank application. This documentation provides a detailed guide on how to configure and set up the application for development and production environments.

## Table of Contents
1. [Installation](#installation)
2. [Configuration Files](#configuration-files)
3. [Environment Variables](#environment-variables)
4. [Usage](#usage)
5. [Troubleshooting](#troubleshooting)

## Installation
To install the Easy Bank application, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/Ahmed123927/easy-bank-configration.git
cd easy-bank-configration
npm install  # or use yarn install
```

## Configuration Files
- **config.json**: This is the main configuration file located in the root of the project. It contains all the essential parameters for the application.
- **database.json**: This file contains database configuration settings such as host, user, password, and database name.

## Environment Variables
Make sure to set the following environment variables before starting the application:
- `DB_HOST`: Database host
- `DB_USER`: Database username
- `DB_PASS`: Database password
- `APP_PORT`: Port on which the application will run

## Usage
To run the application in development mode, use the following command:

```bash
npm run dev
```

For production, build the application and run:

```bash
npm run build
npm start
```

## Troubleshooting
- If you face issues connecting to the database, ensure that your credentials in `database.json` are correct.
- For any errors during the startup, check the logs for detailed messages.

## Conclusion
This documentation should help you set up the Easy Bank configuration effectively. For further questions, please refer to the issues section of the repository or raise a new issue.