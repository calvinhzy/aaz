# [Command] _storage-mover update_

Updates a top-level Storage Mover resource.

## Versions

### [2022-07-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5zdG9yYWdlbW92ZXIvc3RvcmFnZW1vdmVycy97fQ==/2022-07-01-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.storagemover/storagemovers/{} 2022-07-01-preview -->

#### examples

- storage-mover update
    ```bash
        storage-mover update -g {rg} -n {mover_name} -l eastus2 --tags {{key2:value2}} --description ExampleDesc2
    ```
