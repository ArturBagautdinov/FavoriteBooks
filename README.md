# FavoriteBooks 📚

A lightweight iOS app for keeping a personal list of favorite books.  
Add a book with title/author, optionally attach a cover image and a short description, then sort and filter your collection.

## Features

- ✅ Add / edit / delete favorite books
- 🖼️ Optional cover image (PhotosPicker)
- 📝 Description field for notes
- 🔎 Filter by first letter of the book title
- ↕️ Sorting:
  - Newest / Oldest
  - Title (A–Z / Z–A)
  - Author (A–Z / Z–A)
- 💾 Local persistence (JSON file in the app’s Documents directory)
- 🎨 Simple SwiftUI UI with a gradient background

## Tech Stack

- **SwiftUI** — UI
- **Observation** (`@Observable`, `@Bindable`) — state management
- **MVVM-style** separation (View ↔ ViewModel ↔ Store/Storage)
- **PhotosUI** — selecting cover images
- **Codable + FileManager** — JSON persistence

## Requirements

- Xcode (SwiftUI project)
- iOS version supporting **Observation** (iOS 17+)

## How to Run

1. Open `FavoritesManager.xcodeproj` in Xcode
2. Select an iPhone Simulator (or a real device)
3. Build & Run (`⌘R`)
