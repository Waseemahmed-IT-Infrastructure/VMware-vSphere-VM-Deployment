
# Windows Server VM Deployment in vSphere

## Overview

This document covers the basic steps for creating a Windows Server virtual machine using VMware vCenter.

## 1. Create the Virtual Machine

1. Log in to vCenter.
2. Select the required host or cluster.
3. Right-click and select **New Virtual Machine**.
4. Choose **Create a new virtual machine**.
5. Enter the VM name.
6. Select the compute resource and datastore.

## 2. Configure VM Resources

Set the required hardware based on the server requirements.

- CPU and memory
- Virtual hard disk
- Network adapter and port group
- Guest operating system version

## 3. Install Windows Server

1. Upload the Windows Server ISO to the datastore if needed.
2. Connect the ISO to the VM's CD/DVD drive.
3. Enable **Connect at power on**.
4. Power on the VM.
5. Open the VM console.
6. Follow the Windows Server installation steps.

## 4. After Installation

- Install VMware Tools.
- Configure the server network settings.
- Apply Windows updates.
- Check the VM hardware and network connectivity.
- Verify that the server is working as expected.

## 5. Basic Troubleshooting

| Issue | What to Check |
|---|---|
| VM does not start | VM events, available resources and host status |
| ISO not detected | CD/DVD settings and ISO connection |
| No network connection | Network adapter, port group and IP settings |
| Slow VM performance | CPU, RAM, disk and datastore performance |
| VMware Tools warning | Tools installation and service status |

## Note

These are general deployment steps. VM settings depend on the environment and server requirements.
