# Roadmap Maya — Prototype ZBook vers plateforme cible

## Itération 0 — Baseline et cadre

- inventorier CPU/RAM/GPU/SSD du ZBook ;
- activer et valider la virtualisation ;
- valider CRC/OpenShift ;
- définir les métriques de benchmark ;
- documenter l’architecture initiale.

## Itération 1 — Socle IA local

- installer Ollama ou llama.cpp ;
- tester plusieurs petits modèles ;
- mesurer RAM, VRAM, CPU, latence et tokens/s ;
- exposer le modèle par API locale.

## Itération 2 — Maya Architect MVP

- API Maya ;
- premier agent Architecte Solution ;
- prompts structurés ;
- génération d’un premier dossier d’architecture fictif ;
- tests de qualité.

## Itération 3 — RAG Architecture

- ingestion de documents ;
- embeddings ;
- base vectorielle ;
- citations et traçabilité ;
- référentiel d’architecture.

## Itération 4 — Cycle complet Architecte Solution

- 15 livrables ;
- ADR ;
- diagrammes ;
- matrices ;
- comité d’architecture.

## Itération 5 — Maya Trading MVP

- collecte de données de marché ;
- portefeuille de démonstration ;
- analyses multi-timeframe ;
- moteur de scoring ;
- ACHAT / VENTE / ATTENDRE sans exécution automatique.

## Itération 6 — Backtesting et gestion du risque

- backtests reproductibles ;
- métriques de performance ;
- drawdown ;
- R/R ;
- journalisation des décisions.

## Itération 7 — Connecteurs courtiers

- étudier les interfaces réellement disponibles pour eToro, IG et courtiers de produits dérivés ;
- implémenter d’abord des connecteurs en lecture seule ;
- ne jamais stocker de secrets dans Git.

## Itération 8 — GitOps / OpenShift

- conteneuriser les services ;
- déployer sur CRC ;
- Argo CD ;
- configuration, secrets et observabilité.

## Itération 9 — Benchmark final ZBook

- charge simultanée Architect + Trading + CRC ;
- modèles 7B/8B, 14B puis plus grands selon faisabilité ;
- mesurer CPU/RAM/VRAM/SSD/tokens/s/latence ;
- identifier précisément le goulot d’étranglement.

## Itération 10 — Cahier des charges du nouveau portable

Le futur matériel sera dimensionné à partir des mesures réelles du prototype et non d’une estimation théorique.
