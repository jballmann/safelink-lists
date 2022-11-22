# Safelink Lists

Lists for the [Safelink extension](https://github.com/jballmann/safelink-extension)

## Current lists

### Trusted

| Name                              | Description                                                     |
| --------------------------------- | --------------------------------------------------------------- |
| [safelink-default](lists/trusted) | Includes international organizations with corresponding domains |
| [safelink-de](lists/trusted_de)   | Includes popular German banks and other organizations           |

### Redirects

| Name                                | Description                                         |
| ----------------------------------- | --------------------------------------------------- |
| [safelink-redirect](lists/redirect) | Includes known dereferrers and link shorter domains |

## Contributing

In the following you will learn how to contribute to the existing lists and how to create a new list. Safelink has the intention to protect internet users against harmful web activities like fake news, phishing and malware spreading. Therefore please consider only popular international organizations and attractive lures for such activities like websites of banks, news, shops and often used web services in all lists. The intention is not to provide a complete register of all existing organizations and domains.

### Contribute to the lists above

To make suggestions for existing lists please file an issue. Before you suggest an organization or domain please check whether the information are included in another list.

### Create a new list

To create a new list you must only create a JSON file that is public available. The schema for the file you can find in the [schema directory](./schema). Please do not define an organization twice instead import external dependencies with the help of the external property. Every assigned organization id must be unique and may not be exist in any other list.

## Licence

All lists are licensed under GPLv3 and CC-BY 3.0
