# 🎮 Game & Chill — Bot d'Administration Professionnel pour Serveurs Discord

![Discord Bot](https://img.shields.io/badge/Discord-Bot-blue?style=for-the-badge&logo=discord)

> Un bot Discord sécurisé, certifiable et entièrement public, conçu pour les serveurs de +500 membres.  
> **Aucune commande dangereuse. Aucun accès propriétaire. Tout est basé sur les permissions natives de Discord.**

---

## ⚠️ CONDITIONS D’UTILISATION (ToU) — LIRE AVANT D’INVITER LE BOT

En invitant ce bot sur votre serveur, vous acceptez automatiquement les conditions suivantes :

### 1. 🔐 **Pas d’accès privilégié**
- Ce bot **n’a pas accès** à vos données personnelles, mots de passe, comptes bancaires ou fichiers externes.
- Il ne peut **pas** lire vos messages privés (DM), sauf si vous l’invitez dans un salon où il est mentionné.
- **Aucun ID d’owner, staff ou co-owner n’est hardcodé** → Le bot est **100% public** et fonctionne uniquement avec les permissions de Discord.

### 2. 🛡️ **Sécurité renforcée**
- Toutes les commandes sensibles (**ban, kick, mute, lockdown, etc.**) nécessitent que **vous ayez les permissions Discord correspondantes**.
- Le bot **ne peut pas** exécuter de code externe (`eval`, `exec`, `shell`) — ces commandes sont **absentes**.
- Aucune commande de type `massdm`, `nuke`, `backup`, `restore` ou `deleteallchannels` n’est présente → **Zéro risque de destruction de serveur**.

### 3. 📊 **Logs opt-in uniquement**
- Le système de logs (`/setuplogs`) est **entièrement contrôlé par vous**.
- Vous choisissez **le salon** où les actions seront enregistrées.
- **Aucun log n’est envoyé à un serveur externe** — tout est stocké localement sur l’hébergeur du bot (Replit/Railway/etc.).

### 4. 💬 **Respect des règles de Discord**
- Ce bot respecte strictement les [Conditions d’utilisation de Discord](https://discord.com/terms).
- Il **bloque automatiquement** les liens d’invitation Discord et les mentions `@everyone`/`@here` non autorisées.
- Il **ne collecte aucune donnée personnelle** au-delà des IDs Discord nécessaires au fonctionnement (conforme au RGPD).

### 5. 🚫 **Interdiction d’abus**
Vous ne devez pas :
- Utiliser ce bot pour harceler, spammer, ou bannir abusivement des membres.
- Tenter de contourner les permissions de Discord (ex: utiliser une autre personne comme "admin" sans ses droits réels).
- Réutiliser ce code pour créer un bot malveillant, voleur de compte ou ransomware.
- Faire passer ce bot pour un outil officiel de Discord.

> **Toute violation de ces conditions entraînera la suppression immédiate du bot de votre serveur et le blocage de votre IP/domaine d’hébergement.**

---

## ✅ Fonctionnalités principales (100% sûres)

| Catégorie | Commandes |
|----------|-----------|
| **🛠️ Administration** | `/setuplogs`, `/lockdown`, `/unlockdown`, `/slowmodeall`, `/nickall`, `/resetnickall`, `/syncperms`, `/checkperms` |
| **🛡️ Modération** | `/ban`, `/kick`, `/mute`, `/unmute`, `/warn`, `/listwarns`, `/clearwarns`, `/clear`, `/lock`, `/unlock`, `/slowmode` |
| **👥 Rôles & Membres** | `/addrole`, `/removerole`, `/setnick`, `/resetnick`, `/createrole`, `/deleterole` |
| **📄 Salons** | `/createchannel`, `/deletechannel`, `/renamechannel`, `/clonechannel`, `/archive` |
| **📊 Informations** | `/ping`, `/uptime`, `/botinfo`, `/avatar`, `/servericon`, `/channelinfo` |
| **💡 Fun (sans danger)** | `/8ball`, `/coinflip`, `/roll`, `/rps`, `/joke`, `/quote`, `/ship` |

> ✅ Toutes les commandes sont **testées et validées pour la certification Discord**.

---

## 🚀 Comment installer ce bot sur votre serveur ?

1. **Vérifiez que vous avez les permissions :**
   - ✅ `Manage Channels`
   - ✅ `Manage Messages`
   - ✅ `Ban Members`
   - ✅ `Kick Members`

2. **Invitez le bot via ce lien sécurisé :**  
   👉 [Cliquez ici pour inviter Game & Chill](https://discord.com/api/oauth2/authorize?client_id=1417332707876274358&permissions=268443712&scope=bot+applications.commands)

   > 🔐 Permissions accordées : **Toutes les permissions nécessaires pour les commandes ci-dessus, rien de plus.**

3. **Sur votre serveur, utilisez :**
   ```bash
   /setuplogs #votre-salon-de-logs
