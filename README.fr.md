[English](README.md) | **Français**

# Sofien Nefzi

Je conçois des produits data et IA de bout en bout : le pipeline qui alimente les données, le modèle ou l'agent qui les exploite, et l'application que les utilisateurs ont réellement entre les mains.

Data & AI Solutions Engineer, basé à Tunis.

## Sur quoi je travaille

- **Systèmes multi-agents** avec LangGraph : les agents préparent le travail, un humain le valide avant que quoi que ce soit ne sorte du système.
- **Tester les fonctionnalités LLM en CI :** du text-to-SQL vérifié sur ses résultats et la sécurité des données avant la mise en production, pas sur l'apparence du SQL.
- **L'IA au cœur des sessions en direct :** un accompagnement en temps réel pendant les appels vidéo (LiveKit + LLM).
- **Le reporting en tant que code :** des tableaux de bord Grafana versionnés dans Git et provisionnés automatiquement, alimentés par des vues PostgreSQL qui excluent les données personnelles.

## Dépôts publics

| Dépôt | Description |
| --- | --- |
| [querywarden](https://github.com/NefziSofien/querywarden) | Garde-fou CI pour les fonctionnalités text-to-SQL sur PostgreSQL : exécute le SQL généré sur une base de test avec un rôle en lecture seule, compare les résultats à des requêtes de référence et bloque le build en cas de baisse de précision ou de fuite de données. Python, GitHub Action, publié sur PyPI sous le nom `querywarden-cli`. Exemple : [querywarden-example](https://github.com/NefziSofien/querywarden-example). |
| [claude-code-orchestra](https://github.com/NefziSofien/claude-code-orchestra) | Orchestrateur pour les grosses tâches de code : découpe le travail, lance de 0 à 4 agents en parallèle, suit l'état dans un seul fichier compact et vérifie le résultat final. Python, testé sur Linux, macOS et Windows. |
| [Ai-Agency](https://github.com/NefziSofien/Ai-Agency) | Système multi-agents auto-hébergé pour une agence marketing : agents spécialisés (stratégie, contenu, SEO, analytics...), contrôle de cohérence de marque et validation humaine avant publication. FastAPI, Next.js, n8n, pgvector, Langfuse. |

L'essentiel de mon travail pour mes clients et employeurs se trouve dans des dépôts privés. Je présente volontiers l'architecture et le code lors d'un échange.

## Ma façon de construire

- Une petite version en production vaut mieux qu'une grande version en attente sur une branche.
- Les parties ingrates sont faites correctement : migrations, CI/CD, supervision, retours arrière.
- Un agent IA n'envoie jamais rien hors du système sans validation humaine.
- Les données personnelles restent hors du reporting : les tableaux de bord lisent des vues, pas les tables brutes.

## Mes outils

- **IA :** API de LLM, LangGraph, n8n, Langfuse, pgvector
- **Data :** Python, SQL, Pandas, MongoDB, Power BI, Grafana
- **Applications :** TypeScript, React, React Native/Expo, Node.js, NestJS, FastAPI, Supabase, LiveKit
- **Infrastructure :** PostgreSQL, Docker, GitHub Actions, Azure

## Me contacter

Ouvert aux collaborations sur des projets data et IA, ainsi qu'aux postes en télétravail ou avec relocalisation.

[nefzisofien.sn@gmail.com](mailto:nefzisofien.sn@gmail.com) · [LinkedIn](https://linkedin.com/in/sofien-nefzi-) · [Portfolio](https://sofien-nefzi.web.app)
