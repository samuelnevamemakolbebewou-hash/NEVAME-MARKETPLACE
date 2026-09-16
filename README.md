# NÉVAME Marketplace
Marketplace multi-vendeurs pensée pour le Togo.

Stack : HTML + CSS + JavaScript → GitHub → Vercel → Supabase.
Supabase : Auth + PostgreSQL + Storage + RLS.

Fonctionnalités prévues : boutiques vendeurs, photos produits, catalogue, recherche, villes, panier, commandes, suivi, marketing, tunnel de vente, communauté, WhatsApp, webhooks, administration et paiements Mobile Money.

Important : aucune Secret key Supabase dans le frontend. Les secrets, paiements et webhooks sensibles passeront par des Edge Functions/backend.