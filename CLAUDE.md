# Projectregels

## Regel 1: nooit mergen met het originele project

Deze repository (`Woofer-dev/Guindex`) is een zelfstandige afsplitsing van
`howardrj/Guindex`. Het is onze eigen versie en die blijft gescheiden van het origineel.

- Open nooit een pull request naar `howardrj/Guindex` of een andere repository
  buiten `Woofer-dev/Guindex`. De base van elke pull request is altijd
  `Woofer-dev/Guindex`.
- Voeg geen `upstream` remote toe die naar het originele project wijst en haal
  er geen wijzigingen uit op (geen `git pull`, `git fetch`, `git merge`,
  `git rebase` of `cherry-pick` vanuit het origineel).
- Gebruik de knop "Sync fork" op GitHub niet.
- De enige remote is `origin` (`https://github.com/Woofer-dev/Guindex`).
