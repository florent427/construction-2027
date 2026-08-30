# Projet Construction 2027

Application web de pilotage partagé d’un projet de création d’entreprise de construction.

## Fonctionnalités

- chronologie du projet
- points à décider
- statuts et priorités
- notes partagées
- tableau de bord
- synchronisation Supabase
- authentification par lien e-mail

## Sécurité

Le frontend utilise uniquement une clé Supabase **publishable**. Les droits réels sont contrôlés côté PostgreSQL via Row Level Security (RLS) et la table de membres du projet. Aucune adresse de membre n’est stockée dans le dépôt public.

## Hébergement

Prévu pour GitHub Pages.
