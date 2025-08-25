# Personal Notes - Flutter Frontend

A minimal, modern notes app with local data persistence.

## Features
- Add, edit, delete, and view notes
- Instant search (title and content)
- Local persistence with SQLite (sqflite)
- Responsive layout for phones (list) and tablets (grid)
- Light theme with primary #1976D2, secondary #424242, accent #FFC107

## Run
- flutter pub get
- flutter run

## Structure
- lib/
  - main.dart: App entry, providers, routes, theme
  - src/models/note.dart: Note entity
  - src/data/notes_db.dart: SQLite helper
  - src/data/notes_repository.dart: ChangeNotifier state + CRUD
  - src/screens/notes_list_screen.dart: List/search/add screen with drawer
  - src/screens/note_edit_screen.dart: Add/edit screen
  - src/widgets/note_card.dart: Note tile/card UI
