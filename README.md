# IT-Project-3
## Installing and Configuring the Network
### Objective
To create and configure a small network of computers to be used for practicing system administration activities in subsequent projects. 

### Description
Install and configure several different virtual computers into a network that will be used in subsequent projects for practicing various system administration activities.

### Virtualization Software Used
**Oracle VM VirtualBox.**

------------------------------------------------------------------------------------------------------------------------------------------
## Executive Summary

### Scenario
- Build a virtual demonstration network named **SAVN.local** for a fictitious company, System Administration
Virtual Network Company (SAVN).
- SAVN is a virtual (fictitious) company. In the past, the company has relied on several independent desktop computers to manage their assets. SAVN has grown, and management has come to realize that the company could benefit by implementing a network.
- As the IT manager for SAVN, implementing the network will be your responsibility.
- As a user of Microsoft software, SAVN will build its network around **Microsoft Windows Server 2019**. SAVN utilizes **Microsoft Windows 10** as its desktop operating system of choice.

### Steps
1. Designing the network configuration.
2. Verifying IP configurations.
3. Implementing centralized, secure management of the network.
4. Carlos-S19-S1 and Carlos-S19-S2 are virtual machines running **Windows Server 2019.**
5. Carlos-W10-C1 is a virtual desktop computer running **Microsoft Windows 10.**
- These machines will communicate with one another over a local virtual network.

### Roles
1. **_Carlos-S19-S1_** is the virtual machine that is the _domain controller_, the server that responds to security authentication requests within the Windows Server 2019 domain, and manages the savn.local domain.
2. **_Carlos-S19-S2_** will serve as a _file server._ It is the computer system responsible for the central storage and management of data files so that other computers on the savn.local network can access these files.
3. **_Carlos-W01-C1_** is a _desktop client_ that will use software applications to access various system resources, including folders, and files on the network file server (Carlos-S19-S2).
- Carlos-S19-S1, with AD DS and DNS, helps locate network resources and controls security access to these network resources.
- Carlos-S19-S2 holds the data that Carlos-W10-C1’s applications require.

### Screenshots
1. Illustrate each of your three VMs IP configuration.
2. Illustrate a successful pinging of each VM to all other VMs.

------------------------------------------------------------------------------------------------------------------------------------------

## License

    Copyright [2022] [Carlos Fuentes]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
