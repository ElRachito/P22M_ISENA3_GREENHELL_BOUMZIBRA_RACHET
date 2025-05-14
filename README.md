# P22M_ISENA3_GREENHELL_BOUMZIBRA_RACHET
Surveillance de l’environnement d’une plantation qui nous permettra de capter la température, l’humidité, la pression atmosphérique et de luminosité pour la météo afin de prévenir des différents besoins de la plantation. On pourra également utiliser un des boutons de la carte en butée pour savoir si la serre est bien déployée pour couvrir la zone.

Matériel :
  - Carte STM32 Nucleo-L152RE
  - Shield IKS01A3 (capteurs HTS221 & LPS22HB)
  - Câble micro-USB (ST-LINK intégré)
  - PC avec Windows/Linux/Mac (pour TeraTerm ou minicom)

Logiciel :
  - STM32CubeIDE 1.14.1 à 1.17.x (validé)
  - STM32CubeMX (intégré à CubeIDE)
  - X-CUBE-MEMS1 (BSP pour IKS01A3) : Téléchargé depuis https://www.st.com/en/embedded-software/x-cube-mems1.html
    Ajout via Help > Manage Embedded Software Packages > From Local File

Librairies : 
  Certaines librairies ont été ajoutées par chemin absolu donc leur chemin doit être édité.
