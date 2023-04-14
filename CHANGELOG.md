# Changelog

## 2023.1.3 - 2023-04-14

We've improved stability, fixed many bugs and resolved eight tickets for this release. The most notable ones are listed below.

* Opening a huge multi-modal project no longer causes a cache error – SBU-1261
* Creating a Spring Security configuration in a multi-module project no longer throws an IncorrectOperationException – SBU-1192
* The "Already disposed" error when opening a module has been resolved – SBU-1258
* The PluginException "Incorrect CachedValue" has been fixed – SBU-1274

## 2023.1.2 – 2023-03-30

For this release, we've made significant improvements to enhance stability and eliminate numerous bugs and exceptions. We've successfully resolved more than 10 tickets, with the following being the most notable:

* The correct REST API endpoints are now displayed – SBU-1245
* The server port is now displayed properly in the inspector – SBU-1246
* Autocompletion no longer freezes in big projects – SBU-1270
* IntelliJ IDEA 2023.1 has been supported – SBU-1238
* The "Ignore" button for Spring Dev Tools notification now works properly – SBU-583

## 2023.1.1 – 2023-03-15

**This is the first release of the Spring Buddy plugin. It includes the following features:**

- Spring Boot application create wizard (for the IntelliJ IDEA Community)
- Project Navigator that displays
  - Project configurations
  - REST and MVC endpoints
  - Security roles
  - Data sources and JPA structure
  - Application events producers and consumers
- Application setup and configuration wizards:
  - Spring Web
  - Spring Data JPA
  - Spring Security
  - DB Versioning tools: Flyway and Liquibase
  - Spring Actuator
- Palettes and inspectors for beans, controllers and properties
- Smart method delegation feature: create controllers and services from repositories easily!
- Smart code assistance: bean injections are available while you're typing
- Profiles and profile-specific run configurations
- All [JPA Buddy](https://jpa-buddy.com) features for JPA support
- Dev Tools support

...and [more](http:..spring-buddy.com)!
