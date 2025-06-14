# Firebolt Core 🚀

![Firebolt Core](https://img.shields.io/badge/Firebolt%20Core-v1.0.0-blue.svg)
![GitHub Release](https://img.shields.io/github/release/Thanh28012010/firebolt-core.svg)

Welcome to the **Firebolt Core** repository! This project is a free, self-hosted edition of Firebolt's distributed query engine. It provides high-performance data warehousing capabilities that can be deployed anywhere, from a single laptop to enterprise datacenters.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Features

- **High Performance**: Firebolt Core is designed for speed, allowing you to run complex queries on large datasets efficiently.
- **Self-Hosted**: You have full control over your data and infrastructure by deploying Firebolt Core on your own servers.
- **Cloud-Native**: Easily deployable in cloud environments, offering flexibility and scalability.
- **Multi-Format Support**: Work with various data formats including Parquet and Iceberg.
- **Compatibility**: Integrate with existing tools and databases like PostgreSQL and JDBC.

## Getting Started

To get started with Firebolt Core, visit our [Releases](https://github.com/Thanh28012010/firebolt-core/releases) section to download the latest version. You will find the necessary files to download and execute.

### Prerequisites

- A modern operating system (Linux, macOS, or Windows)
- Java 11 or higher
- Sufficient memory and storage for your data needs

## Installation

1. **Download the Release**: Go to our [Releases](https://github.com/Thanh28012010/firebolt-core/releases) page. Download the latest release file.
2. **Extract the Files**: Unzip the downloaded file to your desired location.
3. **Set Up Environment Variables**: Configure any necessary environment variables as per your system requirements.
4. **Run the Engine**: Navigate to the extracted directory and execute the main script to start Firebolt Core.

## Usage

Firebolt Core is designed to be user-friendly. Here’s how you can start using it:

### Connecting to the Database

You can connect to Firebolt Core using various clients. For instance, you can use a JDBC client or a SQL client of your choice.

```sql
-- Example SQL Query
SELECT * FROM your_table WHERE condition;
```

### Data Loading

Firebolt Core supports multiple data formats. You can load data using SQL commands or APIs.

```sql
-- Load data from a Parquet file
LOAD DATA FROM 'path/to/your/file.parquet' INTO your_table;
```

### Querying Data

You can perform complex queries to analyze your data efficiently.

```sql
-- Complex Query Example
SELECT column1, COUNT(*) FROM your_table GROUP BY column1 ORDER BY COUNT(*) DESC;
```

### Monitoring Performance

Use built-in tools to monitor query performance and optimize your data warehouse.

## Contributing

We welcome contributions from the community! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Create a pull request.

Please ensure your code adheres to our coding standards and includes tests where applicable.

## License

Firebolt Core is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

If you have any questions or need support, please check the [Releases](https://github.com/Thanh28012010/firebolt-core/releases) section for updates or open an issue in this repository.

---

### Topics

- AI
- Analytics
- Big Data
- Cloud Native
- Database
- GCS
- Iceberg
- JDBC
- Parquet
- PostgreSQL
- Query Engine
- S3
- Self-Hosted
- SQL

### Resources

- [Official Firebolt Website](https://www.firebolt.io/)
- [Documentation](https://www.firebolt.io/docs)

### Acknowledgments

Thank you to all contributors and users who support this project. Your feedback helps us improve Firebolt Core.

---

This README provides a comprehensive overview of Firebolt Core, guiding users through installation, usage, and contribution. Feel free to explore the repository and engage with the community.