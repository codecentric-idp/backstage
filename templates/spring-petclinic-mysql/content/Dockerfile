FROM eclipse-temurin:17

COPY ${{ values.name }}-*.jar ${{ values.name }}.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "/${{ values.name }}.jar"]
