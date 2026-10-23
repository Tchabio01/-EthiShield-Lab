# EthiShield Lab

**Apprends à détecter. Comprends comment protéger.**

EthiShield Lab est une plateforme francophone d'apprentissage de la cybersécurité éthique. Elle propose un tableau de bord, des cours, des exercices de sensibilisation et des ressources pour apprendre à sécuriser des systèmes dans un cadre légal et autorisé.

## Fonctionnalités

- Interface responsive en français
- Inscription et connexion par e-mail avec Supabase Auth
- Catalogue de cours récupéré depuis Supabase
- Liens vers des environnements pédagogiques légaux (OverTheWire Bandit et OWASP Juice Shop)
- Rappels de sécurité et bonnes pratiques

## Technologies

- HTML, CSS et JavaScript
- Supabase (authentification et données)
- Hébergement statique compatible avec Vercel

## Démarrage

1. Ouvre `index.html` dans un navigateur, ou déploie le dépôt sur Vercel.
2. Configure les paramètres Supabase dans `index.html` si tu utilises un autre projet.
3. Dans Supabase, vérifie que l'authentification e-mail est activée et que les politiques RLS des tables sont correctement configurées.

## Sécurité

- Ne place jamais une clé Supabase **service_role** dans le navigateur ni dans GitHub.
- La clé publishable est destinée au frontend, mais elle ne remplace pas les politiques Row Level Security (RLS).
- Les fonctionnalités de quiz notées, l'attribution de XP et les audits actifs nécessitent une logique côté serveur sécurisée. Elles ne sont pas simulées ici.
- N'effectue des tests de sécurité que sur des systèmes que tu possèdes ou pour lesquels tu as une autorisation explicite. Cette application est destinée à l'apprentissage défensif.

## Déploiement sur Vercel

Importe ce dépôt dans Vercel et utilise les paramètres par défaut pour un site statique. Le fichier `index.html` est la page d'accueil.

## Licence

À définir par le propriétaire du projet.
