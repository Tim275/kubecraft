kubecraft/
└── argocd/
    ├── apps/
    │   └── nginx/
    │       ├── base/
    │       │   ├── deployment.yaml
    │       │   ├── service.yaml
    │       │   ├── namespace.yaml
    │       │   └── kustomization.yaml
    │       └── envs/
    │           ├── qa/
    │           │   └── kustomization.yaml
    │           ├── staging/
    │           │   └── kustomization.yaml
    │           └── production/
    │               └── kustomization.yaml
    ├── infrastructure/
    │   └── cnpg/
    │       ├── base/
    │       │   ├── release.yaml
    │       │   ├── repository.yaml
    │       │   ├── namespace.yaml
    │       │   └── kustomization.yaml
    │       └── envs/
    │           ├── qa/
    │           │   └── kustomization.yaml
    │           ├── staging/
    │           │   └── kustomization.yaml
    │           └── production/
    │               └── kustomization.yaml
    ├── appsets/
    │   ├── qa-appset.yaml
    │   ├── staging-appset.yaml
    │   └── production-appset.yaml
    └── root-app.yaml