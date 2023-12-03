# Static Website Hosting on AWS S3 with Custom Domain

## Project Overview

This project demonstrates the process of hosting a simple static website on AWS S3 (Simple Storage Service) and configuring a custom domain using AWS Route 53. The website includes a basic HTML webpage and CSS styles.

## Table of Contents

- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Configuration](#configuration)
  - [S3 Bucket Configuration](#s3-bucket-configuration)
  - [Custom Domain Setup](#custom-domain-setup)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Project Structure

- **`/website/`**: Contains the HTML and CSS files for the static website.
- **`/docs/`**: Documentation files, including the project report.
- **`/screenshots/`**: Screenshots or images related to the project.

## Getting Started

### Prerequisites

Before starting, make sure you have the following installed:

- [AWS CLI](https://aws.amazon.com/cli/)
- [Git](https://git-scm.com/)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/static-website-aws-s3.git
    cd static-website-aws-s3
    ```

2. Set up AWS CLI with your credentials.

## Configuration

### S3 Bucket Configuration

1. Create an S3 bucket for website hosting.
2. Configure the bucket for static website hosting in the AWS S3 console.
3. Upload the contents of the `/website/` folder to the S3 bucket.
4. Set the appropriate bucket policy for public read access.

### Custom Domain Setup

1. Purchase or transfer a domain using AWS Route 53.
2. Create a record set in Route 53 to link the domain to the S3 bucket.

## Testing

Wait for DNS propagation, and then visit your custom domain in a web browser. Verify the accessibility of the static website.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

