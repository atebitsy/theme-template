# How to create a Theme for atebitsy
> This supports Twitter **v8.49** and atebitsy **v8.49**

- - - -

## **Theme `Information` Block**
[Use this Template to create a Dark Theme](https://github.com/atebitsy/theme-template)

[Use this Template to create a Light Theme](https://github.com/atebitsy/theme-template)

#### Information about your Theme
| Property        | Description       |
|:--------------- | :---------------: |
| name            | Theme Name        |
| version         | Versioning        |
| author     | atebitsy |
| description     | Short Theme Description |
| GitHubRepoThemeURL     | GitHub Theme Repo URL |
| id              | Your unique Theme UUID  |

- - - -

The `name` and file name doesn't need to match.
  - `"name": "Theme Template",` === `example.json`

Important Strings inside the `json`:
* `name` --> The Theme name you want displayed in atebitsy's Theme Settings
* `author` --> The author you want displayed in atebitsy's Theme Settings
* `version` --> The version you want displayed in atebitsy's Theme Settings
* `id` --> Your **Unique** UUID. Google how to get it. [Use this website to generate a UUID](https://www.uuidgenerator.net) or 
[Use this VSCode Extension to generate a UUID](https://marketplace.visualstudio.com/items?itemName=netcorext.uuid-generator) 

Color codes inside the `json` can be the following:
* 6 character HEX --> `#RRGGBB`
  * atebitsy can take 8 character HEX --> `#RRGGBB`
* 8 character HEX --> `#RRGGBBAA`
  * atebitsy can also take 8 character HEX --> `#RRGGBBAA`

