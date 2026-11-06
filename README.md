# SAÉ 2.2 · Mesurer un signal en téléphonie VoIP

> Mesure et comparaison des codecs audio dans un environnement VoIP : latence, quantification, bande passante et rapport signal sur bruit.

| | |
|---|---|
| **Formation** | BUT Réseaux et Télécommunications, Montbéliard |
| **Année** | 1<sup>re</sup> année, semestre 2 |
| **Organisation** | En équipe de 3 |
| **Outils et notions** | `VoIP` `FreePBX` `Linphone` `Raspberry Pi` `GNU Radio` `Codecs` `SNR` |

## Objectif

Étudier la numérisation du son en téléphonie sur IP et mesurer l’impact du codec sur la qualité perçue.

## Environnement de test

- Serveur **FreePBX** sur Raspberry Pi
- Clients **Linphone** sur machines virtuelles Linux
- Réseau local avec une borne Linksys

## Mesures réalisées

Latence, plage de tension de la carte son, quantification, fréquence d’échantillonnage, bande passante, rapport signal sur bruit (SNR) et évaluation de la qualité d’écoute, avec comparaison des valeurs théoriques et mesurées.

## Conclusion

- **Opus** offre le meilleur compromis : excellente qualité, faible latence et bon SNR.
- **Speex** est une bonne alternative quand le débit est limité.
- **PCMU / PCMA**, très répandus, consomment plus de bande passante pour une qualité perçue inférieure.

## Contenu du dépôt

| Fichier | Description |
|---|---|
| [`rapport/rapport-sae-2.2.pdf`](rapport/rapport-sae-2.2.pdf) | Rapport complet (méthodes, calculs, résultats) |
| [`presentation/presentation-linphone.odp`](presentation/presentation-linphone.odp) | Présentation |

---

<sub>Bastien Lorenzi · BUT Réseaux et Télécommunications, parcours cybersécurité · [Portfolio](https://bastien-lorenzi.netlify.app/#projets) · [Profil GitHub](https://github.com/LORENZI-Bastien)</sub>
