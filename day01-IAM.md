<!--- Copyright (C) 2024 teslazonda --->

<!--- This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. --->

<!--- This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details. --->

<!--- You should have received a copy of the GNU General Public License along with this program.  If not, see https://www.gnu.org/licenses/ --->

# Day 1 Notes

## IAM: Users, Groups, Password Policy

* IAM = Identity and Access Management, **Global** service

### Users

* It is bad practice to use the `root` account, so we often create admin IAM users to interact with AWS.

### Groups

* Groups grant multiple permissions to users. Users of the same group will have the same permissions, making it easier manage access across many different users.

* Permissions can be granted through groups or directly, but using groups to grant permissions is recommended.


### Password Policy

* MFA (Multi Factor Authentication) is a must for all AWS accounts. Root and IAM users.
  * Password length and required characters.
  * Password expiration timeline.
