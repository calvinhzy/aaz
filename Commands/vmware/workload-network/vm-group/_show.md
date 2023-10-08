# [Command] _vmware workload-network vm-group show_

Get a vm group by id in a private cloud workload network.

## Versions

### [2022-05-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5hdnMvcHJpdmF0ZWNsb3Vkcy97fS93b3JrbG9hZG5ldHdvcmtzL2RlZmF1bHQvdm1ncm91cHMve30=/2022-05-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.avs/privateclouds/{}/workloadnetworks/default/vmgroups/{} 2022-05-01 -->

#### examples

- Get a VM Group by ID in a workload network.
    ```bash
        vmware workload-network vm-group show --resource-group group1 --private-cloud cloud1 --vm-group vmGroup1
    ```