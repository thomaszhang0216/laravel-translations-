# Changelog

All notable changes to `laravel-translations` will be documented in this file.

## v1.0.7 - 2024-02-19

### What's Changed

* Extend the ExceptionHandler set in the project by @ahtinurme in https://github.com/MohmmedAshraf/laravel-translations/pull/75

**Full Changelog**: https://github.com/MohmmedAshraf/laravel-translations/compare/v1.0.6...1.0.7

## v1.0.6 - 2024-02-13

### What's Changed

* Update Github Actions by @MohmmedAshraf in https://github.com/MohmmedAshraf/laravel-translations/pull/69
* Fixes for JSON export by @ahtinurme in https://github.com/MohmmedAshraf/laravel-translations/pull/66
* Fix translation key format by @MohmmedAshraf in https://github.com/MohmmedAshraf/laravel-translations/pull/73

### New Contributors

* @ahtinurme made their first contribution in https://github.com/MohmmedAshraf/laravel-translations/pull/66

**Full Changelog**: https://github.com/MohmmedAshraf/laravel-translations/compare/1.0.5...v1.0.6

## v1.0.5 - 2024-02-02

### What's Changed

* Fix: Dot Notation for Nested Key Not Working by @MohmmedAshraf in https://github.com/MohmmedAshraf/laravel-translations/pull/63
* Add download translations option for production by @MohmmedAshraf in https://github.com/MohmmedAshraf/laravel-translations/pull/64

**Full Changelog**: https://github.com/MohmmedAshraf/laravel-translations/compare/1.0.4...1.0.5

## v1.0.4 - 2024-01-24

### What's Changed

* Fix Export Issue for Keys with Dots by @MohmmedAshraf in #57 #58

**Full Changelog**: https://github.com/MohmmedAshraf/laravel-translations/compare/1.0.3...1.0.4

## v1.0.3 - 2024-01-22

### What's Changed

* Update create_phrases_table.php by @NoahNxT in https://github.com/MohmmedAshraf/laravel-translations/pull/55
* Fix installation bugs by @MohmmedAshraf in https://github.com/MohmmedAshraf/laravel-translations/pull/54

### New Contributors

* @NoahNxT made their first contribution in https://github.com/MohmmedAshraf/laravel-translations/pull/55

**Full Changelog**: https://github.com/MohmmedAshraf/laravel-translations/compare/1.0.2...1.0.3

## v1.0.2 - 2024-01-19

### What's Changed

* Add: Missing Source key modal by @MohmmedAshraf in https://github.com/MohmmedAshraf/laravel-translations/pull/51
* Translation Strings as Keys support and adding file name in key option by @benaja in https://github.com/MohmmedAshraf/laravel-translations/pull/49

### New Contributors

* @benaja made their first contribution in https://github.com/MohmmedAshraf/laravel-translations/pull/49

**Full Changelog**: https://github.com/MohmmedAshraf/laravel-translations/compare/1.0.1...1.0.2

## v1.0.1 - 2024-01-18

- Update the Readme
- Fix installation issue `brick/varexporter`

## v1.0.0 - 2024-01-18

🚀 **Exciting News: Version 1.0 Release!** 🚀

After months of thorough beta testing, presenting Version 1.0 of the package, loaded with game-changing features and improvements.

**Highlights:**

1. **Inertia Stack Transition:**
   
   - Reimagined the package using Inertia alongside Vue and Typescript, focusing on delivering a significantly improved user experience.
   
2. **Google Translation Integration:**
   
   - Seamless integration with `stichoza/google-translate-php` for Google Translate functionality, and it's completely free of charge!
   
3. **Collaborate with Contributors:**
   
   - Easily invite external contributors to assist with translations or manage them collaboratively.
   
4. **Enhanced UI and More:**
   
   - Refined user interface and various improvements promise an even smoother translation management experience.
   

**Additional Notes:**

- As part of ongoing improvements, delved into TypeScript. Some components are still a work in progress, committed to refining their structure and functionality.

**Action Required:**

1. **Uninstall Previous Version:**
   
   - A new command, has been added to help uninstall the package. It removes all assets, configuration files, and cleans up the database. Please ensure everything is removed before proceeding with the installation, as this command is still in beta, give it a shot by running the following command:
     
     ```bash
     php artisan translations:clean
     
     
     
     
     
     
     
     
     
     ```
   - Alternatively, manually uninstall using:
     
     ```bash
     composer remove outhebox/laravel-translations
     
     
     
     
     
     
     
     
     
     ```
   
2. **Install v1.0:**
   
     ```bash
     composer require outhebox/laravel-translations
   
   
   
   
   
   
   
   
   
     ```
3. **Configuration Update:**
   
   - Review and update configuration files, especially those related to Livewire.
   

Your feedback is highly valued as we continue to enhance the package.

Cheers to version 1.0! 🎉

## v0.1.2 - 2023-12-20

Fix Saving translations with parameters is not working, #46 #47

## 0.1.1 - 2023-11-11

Updated to support **Livewire v3**. Please note, we've discontinued support for older PHP versions. This package is now compatible exclusively with **PHP v8.1** or higher.

## 0.0.7 - 2023-06-28

Enhanced Installation Command. (Closes #36 & #37)
Enhanced Import Translation Command.
Enhanced UI/UX for improved user experience.
Introduced Filter Phrases feature, allowing users to easily switch between translated and untranslated phrases. (See #28)
Added Progress Bar indicator to track translation progress for each new language.
Included Empty states when no languages or phrases are found.
Various other improvements and bug fixes.

## v0.0.6 - 2023-02-19

Add Laravel 10 Support
RTL support for Pashto language by @shahghasiadil
Routes enhancement by @shahghasiadil
Translation List Query Logic Fix @shahghasiadil
Added the function to reverse the migration by @Goatform
Add the file name to phrase list by @kmaking

## v0.0.5 - 2023-01-20

Added language: Portuguese (Brazil) by @A2ronLil
Improve Livewire Components by @Ronildo-Sousa

## v0.0.4 - 2023-01-10

Add Laravel 8 Support, Thanks to @thinkverse
Fix Missing Parameters #10
Add tests for TranslationsManager by @elguitarraverde

## v0.0.3 - 2023-01-03

Optimized languages import #3 by @PovilasKorop

## v0.0.1 - 2022-11-14

initial release...

Enjoy 💖
