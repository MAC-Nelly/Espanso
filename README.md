# Espanso Configuration

 
## Features

This configuration includes several categories of text expansions:

###  **Base Expansions** (`base.yml`)
- Common abbreviations and acronyms
- Technical terms and shortcuts
- Organizational terminology

###  **Date & Time** (`date_time.yml`)
- Dynamic date insertions
- Time stamps
- Meeting templates
- Formatted date strings

###  **Emojis** (`emojis.yml`)
- 100+ emoji shortcuts using `'` prefix
- Common expressions and reactions
- Professional and casual emojis
- Special sequences like table flip `'flip` → (╯°□°)╯︵ ┻━┻

###  **Foreign Etymology** (`foreign_etymology.yml`)
- Accented characters and foreign terms
- Proper spelling for non-English words
- Special character combinations

###  **Long Words & Terms** (`long_words_or_terms.yml`)
- Technical terminology expansions
- Industry-specific phrases
- Complex word shortcuts

###  **Miscellaneous** (`misc.yml`)
- Various utility expansions
- Special formatting
- Custom shortcuts

###  **Stylization Corrections** (`stylization_corrections.yml`)
- Common brand name corrections
- Proper capitalization fixes
- Trademark and copyright symbols

###  **Symbols** (`symbols.yml`)
- Mathematical symbols
- Currency symbols
- Arrow symbols
- Keyboard shortcuts representation
- Special characters

###  **Typos** (`typos.yml`)
- Common typo corrections
- Frequently misspelled words
- Auto-corrections for typing mistakes

## 🛠️ Installation

1. **Install espanso** if you haven't already:
   ```bash
   # Windows (via installer)
   # Download from https://espanso.org/install/
   ```

2. **Copy configuration files** to your espanso directory:
   ```
   Windows: %APPDATA%\espanso\
   ├── config\
   │   └── default.yml
   └── match\
       ├── base.yml
       ├── date_time.yml
       ├── emojis.yml
       ├── foreign_etymology.yml
       ├── long_words_or_terms.yml
       ├── misc.yml
       ├── stylization_corrections.yml
       ├── symbols.yml
       └── typos.yml
   ```

3. **Restart espanso**:
   ```bash
   espanso restart
   ```

## ⚙️ Configuration Details

### Custom Settings
- **Backend**: Clipboard injection for better compatibility
- **Word Separators**: Extended list including common punctuation
- **Toggle Key**: Disabled for seamless operation
- **Undo Backspace**: Disabled to prevent accidental undos

### Key Bindings
Most emoji expansions use the `'` prefix followed by a descriptive word:
- `'fish` → 🐟
- `'rage` → 😡
- `'heart` → ❤️
- `'check` → ✅

Symbols use various prefixes:
- `'r` → → (right arrow)
- `'deg` → ° (degree symbol)
- `'tm` → ™ (trademark)

## 📊 Usage Examples

### Quick Emojis
```
'smile → 😁
'fire → 🔥
'clap → 👏
'rocket → 🚀
```

### Date & Time
```
'date → 09/24/2025
'n → 4:57 PM -
'st → 09/24/2025 4:57 PM - meeting start
```

### Technical Terms
```
'js → JavaScript
'ts → TypeScript
'k8s → Kubernetes
'cicd → continuous integration/continuous deployment
```

### Symbols
```
'r → →
'deg → °
'tm → ™
'copyright → ©
```

##  Troubleshooting

### Expansions Not Working?
1. Check if espanso is running: `espanso status`
2. Restart espanso: `espanso restart`
3. Check logs: `espanso log`

### Inconsistent Triggering?
- Make sure to use word separators (space, punctuation, Enter)
- Try different applications - some may block text injection
- Consider switching injection backends in `config/default.yml`

### Common Issues
- **Word boundaries**: Expansions require word separators to trigger
- **Application compatibility**: Some secure applications may block text injection
- **Timing**: Try typing slower if expansions aren't triggering

## 🔗 Resources

- [Espanso Documentation](https://espanso.org/docs/)
- [Espanso GitHub Repository](https://github.com/federico-terzi/espanso)
- [Configuration Examples](https://espanso.org/docs/matches/basics/)

---

*Happy text expanding! 🚀*
