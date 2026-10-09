# eval-hub-test-jupyternb

RHOAI Red Hat OpenShift AI version 3.5.1

Once RHOAI is up and running:
1. Enable trustyai and mlflow in datasciencecluster
    ```
    trustyai:
      managementState: Managed
    mlflowoperator:
      managementState: Managed
    ```
2. Apply mlflow server CRD - In mlflow folder
3. Apply Postgres database, TrustyAIservice, and Evalhub CRD - In evalhub folder