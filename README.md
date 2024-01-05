# Under Construction
<br>

## About
- these are the English language-files that can be used by community members as a template to translate Lailloken UI and/or adapt it to non-English game-clients

- these community translations / "language packs" will be treated as some form of extension to the main tool and will not be officially implemented

  - they will be separate projects, with their own repositories
 
  - it's a good idea to advertize/announce your plans of starting a project in a new thread in [this discussions section](https://github.com/Lailloken/Lailloken-UI/discussions/categories/translations-localization) in order to prevent multiple independent projects from emerging
<br>

## Publication
- simply create a new repository to host your project

  - you can name it whatever you want, but it's probably best to simply call it `Lailloken-UI-XYZ` (mirroring this repo's name)
 
- the tool searches the `data` folder for folders containing language-files, e.g. `data\english`, so (depending on your preferences) you can either:

  - use this repo's file/folder structure (users will have to manually create the `data\XYZ` folder and copy your files into it)
 
  - use a top-level `XYZ` folder and store the files in there (so users will only have to extract that folder from the downloaded ZIP into the `data` folder)
 
- to avoid confusion, please `DO NOT` create a fork of the main Lailloken-UI project

  - I don't want to miss core feedback/bug-reports just because users post them on the wrong repo
 
  - I don't mean to discredit the work that goes into translating, but re-working the tool to implement this translation "framework" was much more work than translating/adapting text-strings
<br>

## Getting Started
- [download](https://github.com/Lailloken/Lailloken-UI-English/archive/refs/heads/main.zip) the template files and put them into a `separate` folder for easy access

- open the `data` folder within your Lailloken UI installation and create a `new folder` with the name of your target language
- the chosen folder-name will be used/displayed in the settings menu:
  - in a dropdown-list used to switch between UI languages (if you choose to translate for that as well)
 
  - to show which client-language has been detected  
![image](https://github.com/Lailloken/Lailloken-UI-English/assets/61888437/6bc87e98-290e-427e-9eb7-1219013b5493)

- copy the template `client.txt` file into the folder you have created, then open it and read the instructions
  - you can start by adapting the keys tagged with `system_`, `contributor`, and `log_` to your target language first
 
  - once `log_enter` has been adapted, save the file and restart Lailloken UI
  - the `general` section of the settings menu should now show that the script has detected your client's language
 
- if the `client.txt` file has been fully adapted, the majority of item-related features will be usable in the target language

- anything beyond the `client.txt` is optional, and every file more or less corresponds with a specific area/feature within the tool
  - `important note:` don't dump every template-file into your project, only include those you actually translate/adapt (otherwise the tool will access outdated English template files)
 
- in order to translate the tool's own UI, the `UI.txt` file has to be translated
  - if this file is present in a secondary language folder, the settings menu will have a dropdown-list with languages to choose from
