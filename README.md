#  OptiStock-AI — Agent Intelligent de Gestion de Stock

OptiStock-AI est une solution d'automatisation intelligente combinant un **Agent IA** et un moteur d'orchestration **n8n** connecté directement à une base de données PostgreSQL cloud hébergée sur **Supabase**.

---

##  Aperçu du Projet

### 1. Architecture du Workflow n8n
![Workflow n8n](Optistock%20image.png)

### 2. Démos & Réponses en Langage Naturel
![Démo Chat IA](optistock%20reponse.png)

### 3. Exécution & Communication Temps Réel (Supabase API)
![Exécution du Workflow](optistock%20execute.png)

---

##  Fonctionnalités
- **Requêtes en langage naturel** : Posez des questions sur l'état des stocks, les emplacements ou les réapprovisionnements.
- **Interrogation en direct** : Communication temps réel avec Supabase via des requêtes HTTP REST sécurisées.
- **Production-Ready** : Architecture modulaire et déployée sans dépendances lourdes.

---

##  Stack Technique
- **Orchestration** : n8n Cloud
- **Base de données** : Supabase (PostgreSQL Cloud)
- **API** : REST API / HTTP Nodes
- **IA** : Agent LLM avec mémoire conversationnelle

---

##  Comment réimporter le workflow ?
1. Téléchargez le fichier `OptiStock-AI.json` présent sur ce dépôt.
2. Dans votre instance n8n, allez dans **Workflows** > **Import from File**.
3. Configurez vos identifiants Supabase dans les nœuds HTTP REST.
