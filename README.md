# Fedora-KDE-Debloat

This Bash script performs a Fedora KDE "debloat", uninstalling some of the pre-installed applications that are not needed by most users.

# Removed packages

```
akregator          kmail               kontact             libreoffice-draw
dragon             kmahjongg           korganizer          libreoffice-impress
elisa-player       kmines              kpat                libreoffice-math
kaddressbook       kmousetool          krdc                libreoffice-writer
kleopatra          kmouth              krfb                neochat
kolourpaint        konversation        ktnef               pim
kwalletmanager     kwalletmanager5     libreoffice-calc
```

>[!NOTE]
>If you use any of the listed packages, download the “fedora_kde_debloat.sh” file and remove them from the list.

# Installation

```wget -O - https://raw.githubusercontent.com/ericksousa32/Fedora-KDE-Debloat/main/fedora_kde_debloat.sh | bash```
