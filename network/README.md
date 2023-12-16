# Notes

## Requirements

To deploy this example you need `ntw-provider.yaml`

The crossplane SA need the permissions :

```bash
gcloud projects add-iam-policy-binding poc-crossplane-oge \
    --member=serviceAccount:crossplane-sa@poc-crossplane-oge.iam.gserviceaccount.com \
    --role='roles/network.admin'

````
