# MAVEN

---

# 1. INTRODUZIONE A MAVEN

## Cos'è Maven?

- Cos'è Maven?
- Quali problemi risolve Maven?
- Perché usare Maven invece di compilare manualmente?
- Quali sono le principali caratteristiche di Maven?
- Quali sono i vantaggi rispetto ad Ant?
- Quali sono le differenze tra Maven e Gradle?
- Maven è un package manager o un build tool?
- Cosa significa Convention over Configuration?

---

# 2. STRUTTURA DI UN PROGETTO MAVEN

- Qual è la struttura standard di un progetto Maven?
- Perché Maven utilizza una struttura standard?
- Cosa contiene la cartella src/main/java?
- Cosa contiene src/main/resources?
- Cosa contiene src/test/java?
- Cosa contiene src/test/resources?
- Cosa viene generato nella cartella target?
- La cartella target va versionata su Git?

---

# 3. IL FILE pom.xml

- Cos'è il pom.xml?
- Cosa significa POM?
- Qual è lo scopo del pom.xml?
- Quali sono gli elementi principali del POM?
- Quali informazioni minime deve contenere?
- Cosa succede se manca il pom.xml?
- È possibile avere più pom.xml?

---

# 4. GROUP ID, ARTIFACT ID E VERSION

- Cos'è il groupId?
- Cos'è l'artifactId?
- Cos'è la version?
- Perché groupId e artifactId devono essere univoci?
- Cos'è una versione SNAPSHOT?
- Differenza tra SNAPSHOT e Release.
- Quando usare SNAPSHOT?
- Come vengono risolte le versioni?

---

# 5. LE DIPENDENZE

- Come si aggiunge una dipendenza?
- Dove Maven scarica le dipendenze?
- Cos'è Maven Central?
- Come funziona il download delle dipendenze?
- È possibile usare repository privati?
- Come aggiungere un repository custom?
- Come aggiornare una dipendenza?
- Come eliminare una dipendenza?

---

# 6. DEPENDENCY SCOPE

- Cos'è lo scope di una dipendenza?
- Differenza tra compile e provided.
- Differenza tra runtime e compile.
- Quando usare test?
- Quando usare system?
- Quando usare import?
- Quale scope usa Spring Boot Starter?
- Quale scope usare per Lombok?
- Quale scope usare per JUnit?

---

# 7. DIPENDENZE TRANSITIVE

- Cos'è una dipendenza transitiva?
- Come funzionano?
- Come vedere tutte le dipendenze transitive?
- Come escludere una dipendenza transitiva?
- Cosa succede se due librerie dipendono da versioni diverse della stessa libreria?
- Come risolve Maven il conflitto?

---

# 8. DEPENDENCY MANAGEMENT

- Cos'è dependencyManagement?
- Differenza tra dependencies e dependencyManagement.
- Quando usare dependencyManagement?
- Come funziona nei progetti multi-modulo?
- Perché Spring Boot usa dependencyManagement?

---

# 9. PARENT POM

- Cos'è un Parent POM?
- Come funziona l'ereditarietà in Maven?
- Cosa eredita un modulo dal Parent?
- Perché usare un Parent POM?
- Differenza tra Parent POM e Aggregator POM.
- Cos'è spring-boot-starter-parent?

---

# 10. PROGETTI MULTI-MODULO

- Cos'è un progetto multi-modulo?
- Quando conviene utilizzarlo?
- Come si configura?
- Come comunicano i moduli?
- Come si costruisce un progetto multi-modulo?
- Differenza tra modulo e dipendenza esterna.

---

# 11. BUILD LIFECYCLE

- Cos'è il Build Lifecycle?
- Quali sono i lifecycle di Maven?
- Differenza tra Default, Clean e Site.
- Cos'è una Phase?
- Cos'è un Goal?
- Qual è la differenza tra Goal e Phase?

---

# 12. LE PRINCIPALI PHASE

- validate
- compile
- test
- package
- verify
- install
- deploy

Domande:

- Cosa fa compile?
- Cosa fa package?
- Cosa fa install?
- Cosa fa deploy?
- Cosa fa verify?
- Qual è la differenza tra install e deploy?
- Quando viene eseguito test?
- Cosa succede se eseguo package?
- Package esegue compile?
- Install esegue package?
- Deploy esegue install?

---

# 13. COMANDI MAVEN

- mvn clean
- mvn compile
- mvn test
- mvn package
- mvn install
- mvn deploy
- mvn clean install
- mvn dependency:tree
- mvn dependency:analyze
- mvn help:effective-pom
- mvn versions:update-properties

Domande:

- Quale comando usi quotidianamente?
- Perché usare clean install?
- Quando usare dependency:tree?
- Quando usare dependency:analyze?

---

# 14. REPOSITORY MAVEN

- Cos'è Maven Central?
- Cos'è il repository locale?
- Dove si trova il repository locale?
- Come cambiare il repository locale?
- Cos'è un repository remoto?
- Cos'è Nexus?
- Cos'è Artifactory?
- Come pubblicare una libreria?

---

# 15. PLUGIN

- Cos'è un Plugin?
- A cosa servono?
- Come si configurano?
- Quali plugin usi normalmente?
- Cos'è maven-compiler-plugin?
- Cos'è surefire-plugin?
- Cos'è failsafe-plugin?
- Cos'è spring-boot-maven-plugin?
- Cos'è jacoco-maven-plugin?
- Cos'è shade-plugin?
- Cos'è assembly-plugin?

---

# 16. MAVEN E SPRING BOOT

- Come Maven lavora con Spring Boot?
- Cos'è spring-boot-starter-parent?
- Cos'è spring-boot-dependencies?
- Cosa fanno gli Starter?
- Perché Spring Boot usa gli Starter?
- Come creare un jar eseguibile?
- Come funziona spring-boot-maven-plugin?
- Differenza tra jar normale e fat jar.

---

# 17. GESTIONE DELLE VERSIONI

- Come aggiornare una libreria?
- Come bloccare una versione?
- Come evitare incompatibilità?
- Cos'è il Version Range?
- Come Spring Boot gestisce le versioni?

---

# 18. CONFLITTI TRA DIPENDENZE

- Come Maven risolve un conflitto?
- Cos'è il "Nearest Definition"?
- Come risolvere versioni incompatibili?
- Come escludere una libreria?
- Come diagnosticare un conflitto?
- Come leggere dependency:tree?

---

# 19. SETTINGS.XML

- Cos'è settings.xml?
- Dove si trova?
- Quando viene utilizzato?
- Come configurare un proxy?
- Come configurare credenziali?
- Come configurare repository aziendali?
- Come configurare mirror?

---

# 20. PROFILI MAVEN

- Cos'è un Profile?
- Quando usarlo?
- Come attivarlo?
- Come attivarlo tramite variabile?
- Come attivarlo tramite sistema operativo?
- Come attivarlo tramite property?

---

# 21. TEST CON MAVEN

- Come Maven esegue i test?
- Differenza tra Surefire e Failsafe.
- Come saltare i test?
- Differenza tra -DskipTests e -Dmaven.test.skip=true.
- Come eseguire un solo test?

---

# 22. MAVEN NELLE AZIENDE

- Come viene usato Maven in CI/CD?
- Come integra Maven con Jenkins?
- Come integra Maven con GitLab CI?
- Come integra Maven con GitHub Actions?
- Come pubblicare un artefatto?
- Come gestire repository aziendali?
- Come gestire versioni condivise?

---

# 23. DOMANDE AVANZATE

- Come funziona il Super POM?
- Cos'è l'Effective POM?
- Come visualizzarlo?
- Cos'è inheritance?
- Cos'è aggregation?
- Qual è la differenza?
- Come funzionano gli archetype?
- Cos'è un BOM (Bill of Materials)?
- Come funziona il dependency mediation?
- Come Maven costruisce il grafo delle dipendenze?
- Come Maven decide quale versione utilizzare?
- Perché Maven scarica continuamente una SNAPSHOT?
- Perché un clean install può fallire?
- Come velocizzare una build Maven?
- Quali problemi hai risolto usando Maven?

---

# 24. DOMANDE DA COLLOQUIO SENIOR

- Come organizzeresti un progetto enterprise con Maven?
- Come divideresti un progetto in moduli?
- Come gestiresti un BOM aziendale?
- Come pubblicheresti librerie interne?
- Come gestiresti le versioni condivise?
- Come imposteresti una pipeline Maven?
- Hai mai creato un plugin Maven?
- Hai mai utilizzato repository Nexus o Artifactory?
- Hai mai risolto un dependency hell?
- Raccontami un problema reale risolto con Maven.
