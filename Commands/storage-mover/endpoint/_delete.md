# [Command] _storage-mover endpoint delete_

Deletes an Endpoint resource.

## Versions

### [2022-07-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5zdG9yYWdlbW92ZXIvc3RvcmFnZW1vdmVycy97fS9lbmRwb2ludHMve30=/2022-07-01-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.storagemover/storagemovers/{}/endpoints/{} 2022-07-01-preview -->

#### examples

- endpoint delete
    ```bash
        storage-mover endpoint delete -g {rg} --storage-mover-name {mover_name} -n {endpoint_nfs}
    ```
