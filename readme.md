You need have Azure Cli installed on your machine. This script is designed for using az cli interaction mode so no client secret or other info needed, you only need provide subscription.

```powershell
>packer build -var subscription=<your_subscription_id> ./azure-ubuntu.json
```

Then please follow instruction printed by output to finish authentication.