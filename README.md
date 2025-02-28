kubecraft/
└── argocd/
├── apps/ # Developer applications
│ └── nginx/
│ ├── base/ # Base configuration
│ │ ├── deployment.yaml
│ │ ├── service.yaml
│ │ └── kustomization.yaml
│ └── envs/ # Environment-specific overlays
│ ├── qa/
│ │ └── kustomization.yaml
│ ├── staging/
│ │ └── kustomization.yaml
│ └── production/
│ └── kustomization.yaml
├── infrastructure/ # Infrastructure applications
│ └── cnpg/ # CloudNative PostgreSQL
│ ├── base/
│ │ ├── kustomization.yaml
│ │ └── helm-release.yaml
│ └── envs/
│ ├── qa/
│ │ └── kustomization.yaml
│ ├── staging/
│ │ └── kustomization.yaml
│ └── production/
│ └── kustomization.yaml
├── appsets/ # ApplicationSets for each environment
│ ├── qa-appset.yaml
│ ├── staging-appset.yaml
│ └── production-appset.yaml
└── root-app.yaml # Root application
