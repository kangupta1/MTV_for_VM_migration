**The following steps guide you through a playbook that creates the MTV and OpenShift resources for a VM migration with RHV as the source hypervisor. The method is similar if you use another hypervisor, such as VMware.**

1. Create a Secret object for the source provider credentials.
2. Create the Provider object for the source provider.
3. Create the StorageMap object for mapping the source and the destination storage
4. Create the NetworkMap object for mapping the source and the destination networks
5. Create the Plan object to specify the VMs to migrate
6. Create the Migration object to run the plan that you created previously
