# Books Directory

This folder contains notes for each book.  
Every book gets its own subfolder with a consistent structure.

## Folder Structure for a New Book

Each book folder should follow this structure:

books/<book-name>/
    01-chapter-01.md
    02-chapter-02.md
    progress.md
    summary.md

## Naming Conventions

- Book folder name: lowercase, hyphen-separated  
  Example: `designing-data-intensive-applications`

- Chapter files: `NN-chapter-title.md`  
  Use a two-digit number prefix to maintain ordering.  
  Example: `01-introduction.md`, `02-transactions.md`

- Summary file: `summary.md`  
  Contains the complete overview of the book.

- Progress file: `progress.md`  
  Tracks chapter-wise completion.

## How to Add a New Book

1. Create a new folder under `books/` using the naming rules above.
2. Copy templates from `/templates/`:
   - Use `chapter-template.md` to create the first chapter file.
   - Use `progress-template.md` to create a progress file.
   - Use `book-summary-template.md` to create the summary file.
3. Add content to the chapter files as you read.
4. Open a Pull Request with your changes.

## How to Add Chapters

1. Copy `chapter-template.md` from `/templates/`.
2. Rename it to the next chapter number:
   - Example: `03-storage-engines.md`
3. Fill in the template with your notes.
4. Add diagrams if needed (use `shared/diagrams` for general diagrams).

Consistency across book folders helps keep this repository organized and easy to navigate.
