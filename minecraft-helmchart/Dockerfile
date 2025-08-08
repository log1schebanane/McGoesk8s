# 🧱 Basis-Image mit Java 17
FROM eclipse-temurin:21-jdk

# 📂 Arbeitsverzeichnis im Container
WORKDIR /minecraft

# 📦 Server-JAR ins Container-Dateisystem kopieren
COPY server.jar .

# ✅ EULA akzeptieren
RUN echo "eula=true" > eula.txt

# 🔓 Minecraft-Port freigeben
EXPOSE 25565

# 🚀 Startbefehl für den Server
CMD ["java", "-jar", "server.jar"]
