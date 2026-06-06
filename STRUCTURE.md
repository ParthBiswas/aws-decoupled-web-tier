# Repository Structure

This document outlines the directory and file structure for the AWS Custom VPC project.

```text
AWS-Custom-VPC-Project/
│
├── README.md                                 # Main documentation and architecture overview
├── STRUCTURE.md                              # This file, detailing the repository layout
│
├── src/                                      # Source code for the application
│   └── index.html                            # The HTML file deployed on the EC2 web server
│
└── images/                                   # Directory containing architecture screenshots
    ├── Web_Apps.png                          # Server-side HTML configuration
    ├── Live_Webpage.png                      # Final rendered webpage via public IP
    ├── Ec2_Instance.png                      # EC2 running instance details
    ├── Security_Group.png                    # Inbound rules for port 80 and 22
    ├── S3_object.png                         # S3 object overview (Parth0.png)
    ├── S3_Bucket.png                         # S3 bucket configuration
    ├── VPC_Dash.png                          # Prod_vpc dashboard
    ├── Public_Subnet.png                     # Subnet configuration
    ├── Route_Table.png                       # Route table targeting the IGW
    └── Internet_Gateway.png                  # IGW attachment to VPC