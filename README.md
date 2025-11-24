## RL in Trackmania - Maturaarbeit

Soft Actor-Critic (SAC) Agent, trainiert für autonomes Fahren in TrackMania 2020 mithilfe des TMRL-Frameworks.

## Über dieses Projekt

Dieses Repository enthält die Implementierung und Konfigurationen meiner Maturaarbeit über Deep Reinforcement Learning in TrackMania. Das Projekt trainiert einen autonomen Agenten mit SAC basierend auf LIDAR-Beobachtungen & Streckenfortschritt.

## Basierend auf TMRL

Dieses Projekt basiert auf [TMRL (TrackMania Reinforcement Learning)](https://github.com/trackmania-rl/tmrl) mit minimalen Anpassungen:

- **Änderung 1:** tmrl/custom/tm/utils/control_gamepad.py Zeile 11 & 15
- **Änderung 2:** tmrl/__main__.py Zeile 37

## Repository-Struktur

- **Konfigurationen:** Config-Dateien befinden sich im TmrlData/config/Redundant
- **Trainierte Modelle:** Vortrainierte Agenten verfügbar unter https://eduzh-my.sharepoint.com/:f:/g/personal/zifum_wen_stud_edu_zh_ch/EviN19TlHOdIq8M32Ga75l4Br8hxZs1PbWT8RvTwBe0f1w?e=5FoyNc 
