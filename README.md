# SAFE VR: Simulate And Feel Emergencies

SAFE VR è un'applicazione in realtà virtuale (VR) progettata per la simulazione, l'addestramento e l'ottimizzazione delle procedure di evacuazione all'interno di strutture ed edifici complessi in stato di emergenza.

---

## Overview del Progetto

Il software è stato ingegnerizzato per essere altamente scalabile e adattabile. 

L'attuale istanza include la mappatura dettagliata dell'istituto I. S. Archimede di Trevigio (BG), ma l'architettura è predisposta per scalare rapidamente. 
Il sistema è progettato per importare ed elaborare **qualsiasi modello 3D architettonico** (es. aziende, ospedali, centri commerciali, scuole). 
Una volta inserito il modello tridimensionale, gli algoritmi proprietari di navigazione e gestione dell'ambiente si adattano automaticamente alla nuova planimetria. 

---

## Feature Principali

Il framework si divide in macro-moduli funzionali e configurabili in base alle esigenze della simulazione: 

*   **Sistema VR Core**: Implementazione del sistema di movimento, tracciamento della visuale e interazione base in ambiente Virtual Reality.
*   **Algoritmo Pathfinder**: Sistema di navigazione intelligente per il calcolo delle vie di fuga ottimali, implementato tramite **Algoritmo A***.
*   **Supporto Multi-Piano**: Gestione verticale della navigazione per strutture disposte su più livelli con indicatori di piano in tempo reale.

---

## Stack Tecnologico

*   **Game Engine**: Unity
*   **Tecnologia VR**: XR Interaction Toolkit / OpenXR (Compatibilità estesa con i principali visori sul mercato)
*   **Linguaggio di Programmazione**: C#
*   **Architettura Logica**: Algoritmo di Pathfinding A* custom / Unity NavMesh Integration
