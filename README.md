# labspace-dmr-python-demo

## Start the Labspace

```bash
docker compose -f oci://philippecharriere494/labspace-dmr-python-demo up -d
```

<!--
### Start the local development mode:

```bash
# On Mac/Linux
CONTENT_PATH=$PWD docker compose -f oci://dockersamples/labspace-content-dev -f .labspace/compose.override.yaml up

# On Windows with PowerShell
$Env:CONTENT_PATH = (Get-Location).Path; docker compose -f oci://dockersamples/labspace-content-dev -f .labspace/compose.override.yaml up
```
-->
