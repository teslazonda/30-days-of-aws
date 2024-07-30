
<!--- Copyright (C) 2024 teslazonda --->

<!--- This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. --->

<!--- This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details. --->

<!--- You should have received a copy of the GNU General Public License along with this program.  If not, see https://www.gnu.org/licenses/ --->

# Day 2 Notes

## Access Keys

`aws configure`

* Enter the AWS Access Key ID and AWS Secret Access Key into the command line.
* Choose the default region.
* Default output format

`aws iam list-users`
* List all the users associated with your AWS account

## AWS CloudShell

* A terminal in the cloud that is free to use. An alternative to using the CLI locally.
* Only available in certain regions.


## IAM Roles for Services

* You can assign permissions to AWS services. For example, an EC2 instance wants to access another resource.

* Common roles
  * EC2 Instance Roles
  * Lambda Function Roles

## IAM Best Practices

* Do not use the root account.
* One physical user = One AWS User.
* Assign users to groups.
* Create a strong password policy.
* Use MFA.
* Create and use Role for giving permissions to AWS services.
* Use Access Keys for CLI access.
* IAM Credentials Reports and IAM Accesss Advisor.

### Shared Responsibility Model for IAM

* AWS is responsible for Infra, compliance, and configuration
* You are responsible for keys, MFA, users groups etc., you are responsible for all access to your account.


