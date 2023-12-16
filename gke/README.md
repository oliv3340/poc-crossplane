# Notes

## Requirements

To deploy this example you need `compute-provider.yaml` and `provider-cloudplateform.yaml`

The crossplane SA need the permissions :

```bash
gcloud projects add-iam-policy-binding poc-crossplane-oge \
    --member=serviceaccount:crossplane-sa@poc-crossplane-oge.iam.gserviceaccount.com \
    --role='roles/iam.serviceaccountAdmin'


gcloud projects add-iam-policy-binding poc-crossplane-oge \
    --member=serviceaccount:crossplane-sa@poc-crossplane-oge.iam.gserviceaccount.com \
    --role='roles/compute.admin'


gcloud projects add-iam-policy-binding poc-crossplane-oge \
    --member=serviceaccount:crossplane-sa@poc-crossplane-oge.iam.gserviceaccount.com \
    --role='roles/container.admin'

````
