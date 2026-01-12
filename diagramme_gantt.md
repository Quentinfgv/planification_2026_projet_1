# Diagramme de Gantt - Projet Site Web Impulse

## Diagramme de Gantt Complet - Méthode en Cascade

```mermaid
gantt
    title Diagramme de Gantt - Projet Site Web Impulse (9 semaines)
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m
    
    section Phase 1: Cadrage et Analyse
    Analyse contexte et objectifs (UXPO-MKTI)     :crit, a1, 2026-01-01, 2d
    Identification cibles et besoins (UXPO)        :a2, after a1, 2d
    Analyse existant et concurrents (MKTI)        :a3, after a1, 2d
    Interviews utilisateurs (UXPO)                :a4, after a2, 2d
    Note de cadrage et synthèse                    :milestone, a5, after a4, 1d
    
    section Phase 2: Conception UX
    Architecture du site (arborescence) (DEV)     :b1, after a5, 2d
    Parcours utilisateurs (UXPO)                   :b2, after b1, 2d
    Wireframes pages principales (UXPO-WD)         :b3, after b2, 3d
    Validation wireframes                          :milestone, b4, after b3, 1d
    
    section Phase 3: Conception UI
    Maquettes graphiques (MD-WD)                   :c1, after b4, 3d
    Validation ergonomie et identité (UXPO-MKTI)   :c2, after c1, 2d
    Validation client (Impulse)                    :milestone, c3, after c2, 2d
    
    section Étape 3: Analyse Système
    Analyse hébergement                            :d1, after c3, 1d
    Certificat SSL/TLS                             :d2, after d1, 1d
    Installation WordPress                         :d3, after d2, 1d
    
    section Étape 3: Analyse Design
    Prototypage/Maquetage                          :d4, after d3, 2d
    
    section Phase 4: Développement
    Maquetage finale                               :e1, after d4, 2d
    Récupération images et logos                   :e2, after e1, 1d
    Création fichiers code                         :e3, after e2, 1d
    Estimation type de code                        :e4, after e3, 1d
    Développement code et plugin                   :crit, e5, after e4, 5d
    Tests code et plugin                           :e6, after e5, 2d
    Code final et plugin final                     :e7, after e6, 1d
    Développement back                             :crit, e8, after e7, 3d
    Tests back                                     :e9, after e8, 2d
    Test final back et front                       :e10, after e9, 2d
    Site fonctionnel test                          :milestone, e11, after e10, 1d
    
    section Phase 5: Contenus & SEO
    Messages clés et structuration (MKTI)          :f1, after e11, 2d
    Rédaction contenus conversion (MKTI)            :f2, after f1, 2d
    Optimisation SEO (MKTI-DEV)                    :f3, after f2, 2d
    Fiche Google Business (MKTI)                   :f4, after f3, 1d
    Site optimisé SEO                              :milestone, f5, after f4, 1d
    
    section Phase 6: Tests et Ajustements
    Tests techniques et fonctionnels (DEV)         :g1, after f5, 2d
    Tests utilisateurs (UXPO)                      :g2, after g1, 2d
    Corrections graphiques, UX et techniques       :g3, after g2, 3d
    Site corrigé                                    :milestone, g4, after g3, 1d
    
    section Phase 7: Mise en ligne
    Mise en production (DEV)                       :h1, after g4, 2d
    Formation CMS (DEV-UXPO)                       :h2, after h1, 2d
    Validation finale et clôture                    :milestone, h3, after h2, 1d
    
    section Étape 5: Rendu Projet
    Vérification fonctionnement                    :i1, after h3, 1d
    Vérification timing                             :i2, after i1, 1d
    Validation satisfaction client                 :i3, after i2, 1d
    Vérification coûts                              :milestone, i4, after i3, 1d
```

## Diagramme de Gantt Simplifié par Phase

```mermaid
gantt
    title Vue d'ensemble par Phase - Projet Impulse
    dateFormat  YYYY-MM-DD
    axisFormat  Semaine %U
    
    section Phase 1
    Cadrage et Analyse                              :p1, 2026-01-01, 7d
    
    section Phase 2
    Conception UX                                   :p2, after p1, 7d
    
    section Phase 3
    Conception UI                                   :p3, after p2, 7d
    
    section Étape 3
    Analyse Système & Design                        :p3b, after p3, 5d
    
    section Phase 4
    Développement                                   :crit, p4, after p3b, 21d
    
    section Phase 5
    Contenus & SEO                                  :p5, after p4, 7d
    
    section Phase 6
    Tests et Ajustements                            :p6, after p5, 7d
    
    section Phase 7
    Mise en ligne                                   :p7, after p6, 7d
    
    section Étape 5
    Rendu Projet                                    :p8, after p7, 4d
```

## Légende

- **Critique** (rouge) : Tâches critiques du projet
- **Milestone** (diamant) : Jalons importants et livrables
- **Durée totale** : 9 semaines (63 jours)

## Responsabilités par Phase

| Phase | Responsables | Durée |
|-------|-------------|-------|
| Phase 1 | UXPO, MKTI | 1 semaine |
| Phase 2 | DEV, UXPO, WD | 1 semaine |
| Phase 3 | MD, WD, UXPO, MKTI | 1 semaine |
| Étape 3 | DEV, UXPO, WD | 5 jours |
| Phase 4 | DEV | 3 semaines |
| Phase 5 | MKTI, DEV | 1 semaine |
| Phase 6 | DEV, UXPO, WD | 1 semaine |
| Phase 7 | DEV, UXPO | 1 semaine |
| Étape 5 | Tous | 4 jours |
