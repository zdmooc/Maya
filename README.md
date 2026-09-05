# Maya

Maya est une plateforme IA locale de **Maya Interlink Solutions** conçue autour de deux domaines principaux :

1. **Maya Architect** — assistant d’architecture solution pour banque, assurance et autres secteurs.
2. **Maya Trading** — assistant d’analyse de marché et de génération de signaux d’aide à la décision, sans exécution automatique d’ordres dans les premières versions.

## Objectif du prototype

La première cible d’exécution est un **HP ZBook 17 G3** avec 64 Go de RAM, GPU NVIDIA Quadro M3000M 4 Go et OpenShift Local / CRC. Le prototype doit mesurer les limites réelles de la machine avant de définir le cahier des charges du futur portable cible.

## Répartition des dépôts

- `zdmooc/Maya` : code produit, IA, agents, RAG, API, tests, benchmarks, documentation et livrables d’architecture.
- `zdmooc/Maya-gitops` : déploiement OpenShift, GitOps, Argo CD, manifests, overlays et configuration des environnements.

## Structure cible

```text
Maya/
├── apps/
│   ├── architect/
│   ├── trading/
│   └── web-ui/
├── services/
│   ├── ai-core/
│   ├── rag/
│   ├── document-parser/
│   ├── market-data/
│   └── portfolio/
├── docs/
│   ├── company/
│   ├── architecture/
│   ├── deliverables/
│   ├── adr/
│   └── benchmarks/
├── tests/
├── scripts/
└── README.md
```

## Principes

- Local-first.
- Aucune donnée client sensible dans le dépôt public.
- Séparation stricte entre code produit et configuration GitOps.
- Chaque itération doit être codée, testée, documentée et mesurée avant la suivante.
- Les signaux de trading sont des aides à la décision ; aucune exécution automatique d’ordre dans les premières itérations.
