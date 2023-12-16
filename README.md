# POC Crossplane

This repo keeps tracks of the little poc I've made with `Crossplane`.

## Note

Resources deployed :
* simple GCS
* dedicated VPC
* GKE with dedicated nodepool, running on a dedicated SA and using previously created VPC

## Working tree

```bash
.
├── README.md
├── cloudstorage
│   ├── README.md
│   └── cloudstorage.yaml
├── gke
│   ├── README.md
│   └── cluster.yaml
├── network
│   ├── README.md
│   └── vpc.yaml
└── provider
    ├── compute-provider.yaml
    ├── container-provider.yaml
    ├── ntw-provider.yaml
    ├── provider-cloudplateform.yaml
    ├── provider-config.yaml
    └── storage-provider.yaml

5 directories, 13 files

```

