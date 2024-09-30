# Les 04: Werken met Git en GitHub

Deze repository bevat een samenvatting van les 4 over het werken met Git en GitHub. We zullen enkele belangrijke stappen en concepten behandelen die nodig zijn voor softwareversiebeheer.

## Inhoud

- [Introductie tot Git](#introductie-tot-git)
- [Repository Aanmaken](#repository-aanmaken)
- [Commando's voor Git Basisgebruik](#commando-s-voor-git-basisgebruik)
- [GitHub Instellen](#github-instellen)
- [Markdown Overzicht](#markdown-overzicht)

### Introductie tot Git

Git is een populair versiebeheersysteem dat ontwikkelaars helpt bij het beheren van de veranderingen in de codebase. Met Git kun je verschillende versies van je code opslaan en samenwerken met anderen.

### Repository Aanmaken

Om een nieuwe Git repository te creëren, volg je deze stappen:

1. **Navigeren naar de juiste folder**:
    ```shell
    mkdir c:\users\jouwnaam\skill\les4
    cd c:\users\jouwnaam\skill\les4
    ```
2. **Initialiseer een nieuwe Git repository**:
    ```shell
    git init
    ```

### Commando's voor Git Basisgebruik

Hier zijn enkele veelgebruikte Git-commando's:

- **Bestanden toevoegen aan de staging area**:
    ```shell
    git add .
    ```
- **Een commit maken**:
    ```shell
    git commit -m "Bericht van de commit"
    ```
- **De status van de repository bekijken**:
    ```shell
    git status
    ```
- **De geschiedenis van commits bekijken**:
    ```shell
    git log --oneline
    ```

### GitHub Instellen

Volg deze stappen om je repository naar GitHub te uploaden:

1. Maak een account op [GitHub](https://github.com).
2. Maak een nieuwe repository aan genaamd "les04".
3. Voeg de remote repository toe:
    ```shell
    git remote add origin https://github.com/jouwgebruikersnaam/les04.git
    ```
4. Push de lokale repository naar GitHub:
    ```shell
    git branch -M main
    git push -u origin main
    ```

### Markdown Overzicht

Markdown is een eenvoudige opmaaktaal die je kunt gebruiken om gemakkelijk documenten te formatteren. Hier zijn enkele nuttige Markdown elementen:

#### Kopjes

- Gebruik `#` voor kopjes:
    ```markdown
    # Dit is een titel
    ## Dit is een subtitel
    ### Dit is een kopje van niveau 3
    #### Dit is een kopje van niveau 4
    ```

#### Lijsten

- **Ongeordende lijst**:
    ```markdown
    - Punt 1
    - Punt 2
      - Subpunt 2.1
    ```
- **Geordende lijst**:
    ```markdown
    1. Stap 1
    2. Stap 2
    ```

#### Codeblokken

- Voor een stuk code:
    ```markdown
    ```shell
    git status
    ```
    ```

#### Tekst Stijlen

- **Vet**: `**Dit is vetgedrukt**`
- *Schuin*: `*Dit is schuingedrukt*`

### Markdown en GitHub Leren

Markdown is een krachtige manier om je projectdocumentatie op GitHub aantrekkelijk te maken. Experimenteer met de verschillende mogelijkheden om een duidelijke documentatie te maken voor je projecten.

## Conclusie

Dit README.md-bestand biedt een samenvatting van de belangrijkste punten die je hebt geleerd in les 4 over Git en GitHub. Gebruik deze kennis om je eigen repositories te beheren en je vaardigheden met versiebeheer verder te ontwikkelen.

