<!--- Copyright (C) 2024 teslazonda --->

<!--- This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. --->

<!--- This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details. --->

<!--- You should have received a copy of the GNU General Public License along with this program.  If not, see https://www.gnu.org/licenses/ --->

# Day 8 Notes

## S3 buckets

A Storage service that many other AWS services are built on.

* Versioning
* Security
    * Can set permissions at the account or bucket level. Permissions are granted if the permission is provided by the Account OR bucket rule AND there is no explicit Deny policy in place.

## S3 Storage Classes

* Durability
    * 11 9's of durability.
    * Same for all storage classes.
* Availability
    * Measures how much uptime a service has.
    * S3 standard has 99.99% availability.

### S3 Standard - General Purpose
* Frequently accessed data.
* Low latency and high throughput.
* Use cases: mobile and gaming apps, content distribution, data analytics.

### S3 Standard - Infrequent Access
* Lower cost than S3 Standard.
* 99.9% availability.
* Use case: backups.

### S3 Standard - Glacier Storage

#### Instant

* Low cost object storage meant for archiving/backup.
* Millisecond retrieval.
* Minimum storage duration of 90 days.

#### Flexible Retrieval
* Expedited (1-5 min).
* Standard (3-5 hours).
* Bulk (5-12 hours) - free.
* Minimum storage duration of 90 days.

#### Deep Archive
* Standard (12 hours).
* Minimum storage duration of 180 days.

### Intelligent-tiering
* Moves objects automatically between Access Tiers based on usage.


