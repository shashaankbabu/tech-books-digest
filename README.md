# Tech Books Digest

Tech Books Digest is an open, collaborative repository where developers read, summarise, and break down technical books. The goal is to create a long-term, community-driven knowledge base covering system design, distributed systems, cloud, architecture, and software engineering concepts.

This repository provides a consistent structure for adding new books, chapters, diagrams, and shared concepts — with templates to keep everything organized.

---

# Repository Structure (Detailed)

Below is the complete structure of this repository and the purpose of each directory.
```
tech-books-digest/
├── books/                      # One folder per book (chapters, summary, progress)
│   ├── README.md               # How to add a new book
│   ├── template-book/          # Example book folder to copy when adding a new book
│   │   ├── 01-chapter-01.md
│   │   ├── progress.md
│   │   └── summary.md
│   └── (actual books will live here)
│
├── shared/                     # Knowledge used across all books
│   ├── README.md               # How to contribute to shared knowledge
│   ├── glossary.md             # Technical definitions
│   ├── concepts.md             # Explanations of general concepts (CAP, ACID, etc.)
│   ├── interview-questions.md  # Questions derived from book learnings
│   └── diagrams/               # Architecture diagrams & visual explanations
│       └── README.md
│
├── templates/                  # Templates for consistency
│   ├── TEMPLATE_README.md
│   ├── chapter-template.md
│   ├── book-summary-template.md
│   └── progress-template.md
│
├── .github/                    # GitHub metadata (Issues, PRs, workflows)
│   ├── ISSUE_TEMPLATE/
│   │   ├── book_suggestion.yml
│   │   ├── improvement.yml
│   │   └── general_question.yml
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── workflows/              # Optional automation (markdown checks, link checks)
│
├── progress.md                 # Global reading progress (across all books)
├── CONTRIBUTING.md             # How contributors should collaborate
├── CODE_OF_CONDUCT.md          # Community standards
├── LICENSE                     # CC BY-NC-SA 4.0 License
└── README.md                   # This file

---
```

# What This Repository Contains

This repository is designed to document technical learning **book by book**, with a structure that ensures:

- Each book gets its own folder  
- Each chapter has structured notes  
- Each book has a summary  
- Progress can be tracked  
- Shared knowledge (concepts, diagrams, glossary) is reusable  
- Community contributions are simple and guided  

All notes follow templates to keep formatting consistent and easy to navigate.

---

# How to Add a New Book

Follow these steps when adding a new book:

1. Go to `books/`
2. Copy the folder `template-book/`
3. Rename it to the book’s name in lowercase with hyphens  
   Example: `designing-data-intensive-applications`
4. Inside the new folder:
   - Update `01-chapter-01.md` with the first chapter notes  
   - Update `progress.md` based on each completed chapter  
   - Use `summary.md` to document the final summary when done  
5. Add more chapter files as you read the book (copy from templates)

All templates are available inside `templates/`.

---

# How to Add Notes to a Chapter

1. Create a new file using the naming rule:

   `NN-chapter-title.md`

   Example:  
   `02-replication-and-consistency.md`

2. Copy the contents of `templates/chapter-template.md`

3. Fill sections:
   - Key ideas  
   - Summary  
   - Deep insights  
   - Real-world applications  
   - Questions  
   - Diagrams (optional)

4. Commit and open a PR.

---

# Shared Resources

The `shared/` folder is for general knowledge that spans across multiple books.

You can add:

- **glossary** terms  
- **concepts** such as CAP theorem, ACID, load balancing, consistency models  
- **interview questions**  
- **global diagrams** (placed in `shared/diagrams/`)

Anything not tied to a single book goes here.

---

# Contributing

We welcome contributions from:

- People reading and summarising books  
- Developers wanting to add explanations or diagrams  
- Anyone improving existing notes  
- Readers suggesting books  

Before contributing:

1. Read `CONTRIBUTING.md`  
2. Use the correct template  
3. Follow naming conventions  
4. Open a PR with clear details  

Issue templates exist for book suggestions, improvements, and questions.

---

# License

This repository uses:

**Creative Commons Attribution–NonCommercial–ShareAlike 4.0 (CC BY-NC-SA 4.0)**

You are free to share and adapt the content, as long as:

- You provide attribution  
- You do not use it commercially  
- You share adaptations under the same license  

See the full license text in `LICENSE`.

---

# Maintainers

- Shashaank Babu
- Aakash Panchal

For questions, suggestions, or collaboration, please open an Issue or Discussion.

---

# Current Status

The repository structure and templates are complete.  
We will begin adding books and chapter notes soon.  
Community contributions are welcome from day one.

