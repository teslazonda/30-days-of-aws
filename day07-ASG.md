<!--- Copyright (C) 2024 teslazonda --->

<!--- This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. --->

<!--- This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details. --->

<!--- You should have received a copy of the GNU General Public License along with this program.  If not, see https://www.gnu.org/licenses/ --->

# Day 7 Notes

## ASG - Auto Scaling Groups

Auto Scaling Groups can be used to automatically increase the number of active instances serving requests.

Setting a maximum number of instances/use limit is very important.

### Scaling Strategies

* Manual scaling - Update manually
* Dynamic Scaling
	* Simple - when more than % of CPU is used
	* Target Tracking Scaling
	* Predictive scaling - based on Machine Learning analysis
