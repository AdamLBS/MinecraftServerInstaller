MinecraftServerInstaller :

# French Version

# Script d'installation automatique de serveur minecraft
Ce script permet d'installer automatiquement un serveur minecraft sur un VPS linux. Le script installe automatiquement l'environnement Java 8 requis pour le bon fonctionnement du serveur. 

# Versions supportées 
Spigot 1.7.2, 1.9.4, 1.8.8, 1.11.2, 1.12.2 et 1.10.2

# Téléchargement
En root : 
```bash
wget -P /usr/bin https://uploads.laabase.ovh/minecraftinstall && chmod 0777 /usr/bin/minecraftinstall

```

Si vous n'êtes pas en root : 
```bash
sudo wget -P /usr/bin https://uploads.laabase.ovh/minecraftinstall && chmod 0777 /usr/bin/minecraftinstall
```
Si vous avez un problème lors du téléchargement référez vous à la section "Résolution de problèmes"

# Utilisation
Exécutez la commande suivante :
(Si vous êtes connecté avec root ) 
```bash
minecraftinstall
```

(Si vous n'êtes pas connecté avec root )

```bash
sudo minecraftinstall
``` 
# Résolution de problèmes :

Si vous avez une erreur du type  
```bash
Erreur : le certificat de « uploads.laabase.ovh » n'est pas de confiance.
Erreur : le certificat de « uploads.laabase.ovh » n'est pas d'un émetteur connu.
``` 
Réalisez la commande suivante (root): 

```bash
wget -P --no-check-certificate /usr/bin https://uploads.laabase.ovh/minecraftinstall && chmod 0777 /usr/bin/minecraftinstall
``` 

Si vous n'êtes pas root : 
```bash
sudo wget -P --no-check-certificate /usr/bin https://uploads.laabase.ovh/minecraftinstall && chmod 0777 /usr/bin/minecraftinstall
``` 

# English Version

# Auto-Install Minecraft server Script
This script automatically installs a minecraft server on a linux VPS. The script automatically installs the java 8 environment required for the proper functioning of the server.

# Supported Minecraft Versions : 

Spigot 1.7.2, 1.9.4, 1.8.8, 1.11.2, 1.12.2 and 1.10.2

# Download
If you are root : 
```bash
wget -P /usr/bin https://uploads.laabase.ovh/en/minecraftinstall && chmod 0777 /usr/bin/minecraftinstall

```

If you are not root : 

```bash
sudo wget -P /usr/bin https://uploads.laabase.ovh/en/minecraftinstall && chmod 0777 /usr/bin/minecraftinstall

```

# Use the script : 

if you are root
```bash
minecraftinstall
```

If you are not root : 

```bash
sudo minecraftinstall
``` 
# Problem solving

If you have an error of the type
```bash
Error: the certificate of "uploads.laabase.ovh" is not trusted.
Error: The certificate of "uploads.laabase.ovh" is not from a known issuer.
```
Make the following command (root):
```bash
wget -P --no-check-certificate /usr/bin https://uploads.laabase.ovh/minecraftinstall && chmod 0777 /usr/bin/minecraftinstall
``` 
If you are not root : 

```bash
sudo wget -P /usr/bin https://uploads.laabase.ovh/minecraftinstall && chmod 0777 /usr/bin/minecraftinstall
```
# Support

If you got any trouble you can contact me at : adam@laabase.ovh
