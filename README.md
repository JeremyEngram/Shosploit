# Shosploit
Shosploit uses the shodan cli for vulnerability visualization 🔥

# Installation Requirements:
* git
* python3
* pip3
* The official Python library for Shodan
* Shodan API-Key

# Installation Commands
1. Step


(Path Variable für Python der PATH Variable hinzufügen, siehe https://stackoverflow.com/questions/11530090/adding-a-new-entry-to-the-path-variable-in-zsh)

2. Step
shodan init API KEY (API KEY findet man auf Shodan Website unter Account)

3. Step (Download u. Suche)

shodan download --limit 200 ergebnisse.json.gz asn:ASN000 http.component:"sap"

4. Step (KOnvertierung nach Excel)

shodan convert ergebnisse.json.gz xlsx

5. Step (Excel File im System finden)

im Finder nach "Ergebnisse" suchen und dann findet man schnell ergebnisse.xlsx
# User Disclaimer
* It is recommended to use and have some experience with the shodan search engine using a web-browser before using the script.
* Read more about shodan and their services at shodan.
