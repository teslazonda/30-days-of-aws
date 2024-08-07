<!--- Copyright (C) 2024 teslazonda --->

<!--- This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. --->

<!--- This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details. --->

<!--- You should have received a copy of the GNU General Public License along with this program.  If not, see https://www.gnu.org/licenses/ --->

# Day 4 Notes

## Security Groups

* A firewall on EC2 instances.
    - Regulate Access to ports
    - Control inbound and outbound traffic
    - Authorized IP ranges

Security groups are locked to ONE region

Good to maintain one separate security group for SSH access

## How to SSH into an EC2 instance

* Go to your instance on the EC2 dashboard. Ensure your security groups are setup properly.

* Download the corresponding .pem key file for your instance.

Use the command `ssh -i ec2-user@PUBLIC.IP.ADRESS` from within the directory with your .pem file.

You may have to change the permissions for the file.

## EC2 Instance Connect

* Connect to your instance through a terminal in your web browser.

## EC2 Purchasing Options

* On-Demand
    - Pay for what you use:
        * Linux or Windows - billing per second
        * No upfront payment

* Reserved
    - Long workloads
    - Convertible Reserved Instances
    - Up to 72% discount compared to On-demand

* Savings Plans - 1 or 3 year commitment to amount of usage.
    - Commit to a certain type of usage.
    - Usage beyond EC2 Savings plans are billed at the On-Demand price.

* Spot instances - short cheap workloads that are unreliable.
    - Can get a discount of up to 90%. Could be lost at anytime.
    - Good for workloads that are resilient to failure.

* Dedicated Hosts - an entire physical server.
    - Used for compliance requirements or software bound licenses.
    - Have more options for specific management than Dedicated Instances.

* Dedicated Instances - No other customers will share your hardware.

* Capacity Reservations - reserve capacity in a specific AZ for any duration.
