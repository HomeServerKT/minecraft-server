# coumentation importeren maps op server met /mv

🛠️ 2. Fix de rechten (AccessDeniedException oplossen)
Open een terminal (SSH) of de console van je Docker-container via CasaOS.

📍 Ga naar de map van de Minecraft-server:

```
cd /crafty/servers/<jouw-server-naam>
```

🔓 Zet de juiste rechten:
```
chmod -R 755 (wereldnaam)
```
```
chown -R 1000:1000 (wereldnaam)
```
✳️ 1000:1000 is de standaard UID:GID in Docker/CasaOS. Als je een andere UID gebruikt in je container, pas dit dan aan.
