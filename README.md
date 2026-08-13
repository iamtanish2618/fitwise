# fitwise

A Flutter and Firebase mobile app for recipe discovery, ingredient pairing, and using leftovers.

## Source and history

This repository imports [EatWise](https://github.com/MonaTheDon/EatWise) at commit `197fb428a63725b89f8fd568fb880c367f244bc2`.
The original source files, commit history, and author attribution are retained. The original documentation is available in [docs/UPSTREAM_README.md](docs/UPSTREAM_README.md).

The import and repository rename were prepared on 15 October 2026. The rename commit uses a user-requested historical date of 2026-08-13; that timestamp does not represent when this repository was created or when the upstream code was originally written.

## Stack

- Flutter and Dart
- Firebase Authentication and Cloud Firestore
- Provider state management
- RecipeDB and FlavourDB APIs

## Run locally

1. Install Flutter and clone this repository.
2. Run `flutter pub get`.
3. Configure a Firebase project you control and update the platform Firebase configuration.
4. Confirm availability of the RecipeDB and FlavourDB API endpoints used by the application.
5. Connect an emulator or device and run `flutter run`.

The application retains its original EatWise package identifiers; fitwise is the repository name.
