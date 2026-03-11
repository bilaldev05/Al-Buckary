# Contributing to Al-Buckary 🤝

Thank you for your interest in contributing to Al-Buckary! We welcome contributions from developers of all skill levels. Many of our issues are labeled `good first issue` — perfect for beginners.

## Getting Started

### 1. Fork & Clone

```bash
# Fork this repository on GitHub, then:
git clone https://github.com/YOUR_USERNAME/Al-Buckary.git
cd Al-Buckary
flutter pub get
flutter run
```

### 2. Find an Issue

Browse [open issues](https://github.com/soghayarmahmoud/Al-Buckary/issues) and pick one that interests you.

| Label | Description |
|---|---|
| `good first issue` | Great for beginners |
| `help wanted` | We need help with this |
| `bug` | Something isn't working |
| `enhancement` | New feature request |

### 3. Create a Branch

```bash
git checkout -b feature/issue-number-short-description
# Example: git checkout -b feature/23-download-notification
```

### 4. Make Changes

- Follow existing code patterns in the project
- Use Arabic text direction (`TextDirection.rtl`) for all content
- Use `Provider` for state management
- Test on both dark and light themes

### 5. Commit & Push

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```bash
git commit -m "feat: add bookmark icon to hadith card"
git commit -m "fix: resolve text color in collection page"
git commit -m "docs: update README with new features"
```

| Prefix | Usage |
|---|---|
| `feat:` | New feature |
| `fix:` | Bug fix |
| `docs:` | Documentation |
| `style:` | Formatting only |
| `refactor:` | Code restructure |
| `test:` | Adding tests |
| `chore:` | Tooling, deps |

### 6. Open a Pull Request

- Reference the issue number: `Closes #23`
- Describe what you changed and why
- Include screenshots for UI changes

---

## Project Structure

```
lib/
├── main.dart              # App entry point
├── database_helper.dart   # SQLite database
├── models/                # Data models
├── pages/                 # Screens
├── components/            # Reusable widgets
├── providers/             # State (Provider)
├── services/              # Background services
└── themes/                # Theme management
```

## Need Help?

- Open an issue with the `question` label
- Email: [alsighiar@gmail.com](mailto:alsighiar@gmail.com)

---

بارك الله فيكم — May Allah bless your contribution! 🤲
