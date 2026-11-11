
# VMware VM Troubleshooting

This is a basic checklist for common virtual machine issues in VMware vSphere.

## VM Not Powering On

- Check the error message in vCenter.
- Review VM events and alerts.
- Check available host resources.
- Verify datastore accessibility.

## Network Connectivity Issues

- Check the VM network adapter.
- Verify the correct port group is selected.
- Check the IP address, subnet mask and gateway.
- Test connectivity with other network devices.

## VM Performance Issues

- Check CPU and memory usage.
- Review disk usage and datastore performance.
- Check for active alerts.
- Verify VMware Tools status.

## ISO and Installation Issues

- Check whether the ISO is uploaded to the datastore.
- Verify the ISO is connected to the VM.
- Enable Connect at power on if needed.
- Check the VM boot settings.

## VMware Tools

VMware Tools helps improve guest OS integration and provides better VM management.

I check the VMware Tools status after deploying a virtual machine.

## Useful Checks

| Area | What I Check |
|---|---|
| VM Summary | Power state and alerts |
| Monitor | Events and performance |
| Edit Settings | CPU, RAM, disk and network |
| Datastore | Storage availability |
| Guest OS | Network settings and services |

## Note

These are general troubleshooting steps. The exact checks depend on the environment and issue.
