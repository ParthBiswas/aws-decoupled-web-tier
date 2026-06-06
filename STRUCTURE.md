# Repository Structure

This document outlines the directory and file structure for the AWS Custom VPC project.

```text
AWS-Custom-VPC-Project/
│
├── README.md                                 # Main documentation and architecture overview
├── STRUCTURE.md                              # This file, detailing the repository layout
├── SUGGESTIONS.md                            # Architectural improvements and next steps
│
├── src/                                      # Source code for the application
│   └── index.html                            # The HTML file deployed on the EC2 web server
│
└── images/                                   # Directory containing architecture screenshots
    ├── Screenshot 2026-06-06 105055.png      # Server-side HTML configuration
    ├── Screenshot 2026-06-06 105420.jpg      # Final rendered webpage via public IP
    ├── Screenshot 2026-06-06 111311.jpg      # EC2 running instance details
    ├── Screenshot 2026-06-06 111440.jpg      # Inbound rules for port 80 and 22
    ├── Screenshot 2026-06-06 111450.png      # S3 object overview (Parth0.png)
    ├── Screenshot 2026-06-06 111510.png      # S3 bucket configuration
    ├── Screenshot 2026-06-06 111607.jpg      # Prod_vpc dashboard
    ├── Screenshot 2026-06-06 111658.jpg      # Subnet configuration
    ├── Screenshot 2026-06-06 111749.png      # Route table targeting the IGW
    └── Screenshot 2026-06-06 111800.png      # IGW attachment to VPC