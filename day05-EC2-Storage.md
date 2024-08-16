
<!--- Copyright (C) 2024 teslazonda --->

<!--- This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. --->

<!--- This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details. --->

<!--- You should have received a copy of the GNU General Public License along with this program.  If not, see https://www.gnu.org/licenses/ --->

# Day 5 Notes

## EBS Volumes

* Network drive.
* Locked to an availability zone
* Have a provisioned capacity (size in GBs and IOPS)
* Delete on termination attribute (can be deleted when instance terminates)
* Can have latency issues when compared with hardware drives

## EBS Snapshots

* Make a backup of your EBS volume at a point in time.
* Not necessary to detach, but recommended.
* Can copy snapshots across AZ or Regions.
* Archive tier is much cheaper. But it takes 24-72 hours to restore.
* Recycle bin for EBS
  - Can have rules to retain deleted snapshots.
  - Can set when snapshots are permanently deleted.

## AMI - Amazon Machine Image
* A customization of an EC2 instance
  - Add your own stuff (software, OS, etc).
  - AMI are built for a specific region.
  - Custom AMIs boot faster.
* Marketplace AMIs are available from vendors.

### EC2 Image Builder
* Automate the creation of Virtual machines or container images.

## EC2 Instance Store
* High-performance hardware disk.
* Ephemeral (loses storage if the EC2 instance is stopped).
* Good for buffer/cache/temp storage
* Backups and Replication are your resposibility

## EFS - Elastic File System
* Managed NFS that can be mounted to many different EC2 instances.
* Available to Linux EC2 instances.

### EFS-IA (EFS Infrequent Access)
* 92% lower cost
* Cost savings
