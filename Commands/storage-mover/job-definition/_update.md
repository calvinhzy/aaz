# [Command] _storage-mover job-definition update_

Update properties for a Job Definition resource. Properties not specified in the request body will be unchanged.

## Versions

### [2022-07-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5zdG9yYWdlbW92ZXIvc3RvcmFnZW1vdmVycy97fS9wcm9qZWN0cy97fS9qb2JkZWZpbml0aW9ucy97fQ==/2022-07-01-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.storagemover/storagemovers/{}/projects/{}/jobdefinitions/{} 2022-07-01-preview -->

#### examples

- job-definition update
    ```bash
        storage-mover job-definition update -g {rg} -n {job_definition} --project-name {project_name} --storage-mover-name {mover_name} --copy-mode Mirror --agent-name {agent_name} --description JobDefinitionDescription2
    ```
