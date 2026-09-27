# Vincent Dollois

Étudiant en systèmes électroniques embarqués, passionné par l'aérospatial et la défense.

---

## 🎓 Parcours

- **BUT Génie Électrique et Informatique Industrielle (GEII)** — diplômé
- **Cycle ingénieur Systèmes Électroniques Embarqués** à l'**ISTY** (Institut des Sciences et Techniques des Yvelines) — rentrée septembre 2026
- 🎯 Actuellement à la recherche d'un **contrat d'apprentissage de 3 ans** dans l'embarqué / aérospatial / défense pour accompagner ce cursus

## 💼 Expérience

**Stage — Collins Aerospace**
Mise en place de bancs de test, analyse de résultats, validation d'outils et rédaction de documentation technique.

## 🛠️ Compétences techniques

- **Langages** : C / C++, Python, MATLAB/Simulink
- **Microcontrôleurs / SoC** : STM32 (Nucleo), ESP32, cartes ALTERA DE1
- **Temps réel** : FreeRTOS (tâches, sémaphores, files de messages), notions AUTOSAR/RTOS certifiés
- **Communication / IoT** : MQTT (dont MQTT sécurisé via TLS), Node-RED, serveurs HTTP embarqués, UART/AT
- **Outils** : STM32CubeIDE / CubeMX, PlatformIO, VS Code, ESP-IDF
- **Autres** : RFID (MIFARE Classic), asservissement / correcteurs PID, rigueur documentaire et traçabilité

## 🚀 Projets phares

### 🔐 Communication MQTT sécurisée STM32 ↔ ESP32 ↔ Mosquitto
Mise en place d'une liaison MQTT sécurisée (TLS) entre une carte **STM32L476RG Nucleo** et un broker **Mosquitto**, via un **ESP32-WROOM-32** utilisé comme modem WiFi (firmware ESP-AT). Deux modes explorés : MQTT haut niveau via commandes AT, et transport TCP/TLS brut avec construction manuelle des trames MQTT côté STM32.

### 🧵 Multitâche temps réel avec FreeRTOS
Architecture à trois tâches sur **STM32L476RG Nucleo** (CMSIS-V2 / CubeMX) : clignotement LED, gestion de bouton par sémaphore binaire (interruption EXTI), journalisation UART par file de messages.

### 📡 Chaîne IoT RFID (SaÉ IoT)
Système complet de lecture/écriture sur badge **RFID MIFARE Classic** (ESP32 + module MFRC522), avec communication MQTT, pilotage via interface **Node-RED** et serveur web embarqué pour le monitoring.

### ⚙️ Autres projets BUT GEII
- Correcteur **PID** sous MATLAB/Simulink pour banc QUBE-Servo (servo-moteur)
- Construction et programmation d'un robot 4 roues motrices
- Transfert de données d'une sonde de température via MQTT
- Alarme sur carte didactique ALTERA DE1, pilotage de capteur ultrason (Roomba), hacheur pour vélo électrique, voiture radiocommandée

## 📫 Me contacter

N'hésitez pas à me contacter pour toute question ou opportunité !

---

⭐️ N'hésitez pas à explorer mes dépôts pour en savoir plus sur chacun de ces projets.
