# LAB 11 — Bypass de la Détection de Root Android avec Frida

**Cours :** Sécurité des applications mobiles  
**Analyste :** Omar Haouani  
**APK cible :** UnCrackable-Level1.apk  
**Outil :** Frida 17.9.1  
**Date :** Avril 2026

---

## Phase 1 : Installation de Frida Server

![](2.png)

## Phase 2 : Interface de l'application

![](3.png)

## Phase 3 : Analyse JADX - Code anti-root

![](7.png)

## Phase 4 : Script Frida - Hook des méthodes anti-root

![](5.png)

## Phase 5 : Script Frida - Hook de Runtime.exec

![](4.png)

## Phase 6 : Exécution du script Frida

![](6.png)

---

## Résultats

| Détection | Statut |
|-----------|--------|
| Méthode a() | Bypassée ✅ |
| Méthode b() | Bypassée ✅ |
| Méthode c() | Bypassée ✅ |

---

*Omar Haouani - 2026*
