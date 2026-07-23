# 🌍 PANAFRIKA E-COMMERCE PLATFORM
## Célébrer la Culture et l'Innovation Panafricaine

[![Django](https://img.shields.io/badge/Django-5.0-green)](https://www.djangoproject.com/)
[![React](https://img.shields.io/badge/React-18.0-blue)](https://react.dev/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-336791)](https://www.postgresql.org/)
[![Docker](https://img.shields.io/badge/Docker-Supported-2496ED)](https://www.docker.com/)

## 🎯 Vue d'ensemble

Plateforme e-commerce premium dédiée aux produits artistiques panafricains avec :
- 🤖 Chat IA intelligent pour support client
- 💰 Paiements multiples (Stripe, PayPal, Wave, Orange Money, MTN)
- 📊 Dashboard administrateur stratégique
- 🔐 Authentification JWT + AES-256
- 📱 Interface responsive et interactive
- 🌐 Multilingue & Multi-devises
- 📈 Analytics en temps réel
- 🎨 AR/3D pour visualisation produits

## 📋 Fonctionnalités

### Pour les Clients
- ✅ Authentification SSO + JWT
- ✅ Catalogue interactif avec filtres avancés
- ✅ Moteur de recherche intelligent
- ✅ Chat IA pour recommandations
- ✅ Panier et paiement sécurisé
- ✅ Historique d'achats
- ✅ Wishlist personnalisée
- ✅ Avis et évaluations
- ✅ Programme de fidélité

### Pour les Administrateurs
- ✅ Dashboard avec analytics
- ✅ Gestion des produits (CRUD)
- ✅ Gestion des commandes
- ✅ Gestion des utilisateurs
- ✅ Rapports financiers
- ✅ Gestion des promotions
- ✅ Emails marketing
- ✅ Notifications en temps réel

## 🚀 Architecture Technique

```
Backend: Django 5.0 + DRF
Frontend: React 18 + Redux
Database: PostgreSQL 15
Cache: Redis
Queue: Celery
Storage: AWS S3 / Local
Payments: Stripe, PayPal, Wave API
Chat IA: OpenAI / Claude / LLaMA
```

## 📂 Structure du Projet

```
panafrika-ecommerce/
├── backend/
│   ├── core/                 # Configuration Django
│   ├── apps/
│   │   ├── users/           # Authentification
│   │   ├── products/        # Produits & Artistes
│   │   ├── orders/          # Commandes
│   │   ├── payments/        # Paiements
│   │   ├── chat/            # Chat IA
│   │   ├── recommendations/ # IA recommandations
│   │   ├── analytics/       # Analytics
│   │   └── shipping/        # Logistique
│   ├── static/
│   ├── media/
│   └── manage.py
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── admin/
│   │   └── store/
│   └── package.json
├── docker-compose.yml
├── .env.example
└── docs/
```

## 📖 Démarrage Rapide

```bash
# Cloner le repository
git clone https://github.com/Bienvenu12-dev/panafrika-ecommerce.git
cd panafrika-ecommerce

# Avec Docker
docker-compose up -d

# Créer un super utilisateur
docker-compose exec backend python manage.py createsuperuser
```

## 🌐 Accès à l'application

- **Frontend**: http://localhost:3000
- **Backend API**: http://localhost:8000/api
- **Admin Django**: http://localhost:8000/admin
- **Documentation API**: http://localhost:8000/api/docs

## 📚 Documentation

Voir le dossier `/docs` pour :
- Guide d'installation détaillé
- Documentation API
- Guide d'utilisation Admin
- Architecture système

## 🔒 Sécurité

- ✅ JWT Token + Refresh Token
- ✅ AES-256 Encryption
- ✅ CORS configuré
- ✅ Rate limiting
- ✅ SQL Injection protection
- ✅ XSS prevention

## 💳 Paiements Intégrés

- Stripe
- PayPal
- Wave (Sénégal)
- Orange Money
- MTN Mobile Money

## 🤖 Chat IA

Assistant intelligent pour :
- Recommandations produits
- Support client 24/7
- Questions générales
- Multilingue

---

**Développé avec ❤️ pour célébrer la culture panafricaine** 🌍🎨
