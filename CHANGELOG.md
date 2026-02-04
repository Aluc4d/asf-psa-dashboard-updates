# Changelog
All notable changes to ASF PSA Dashboard will be documented in this file.

## [1.0.0] - 2024-XX-XX (Update this date!)

### 🎉 Initial Release

#### ✨ Features
- Real-time ASF bot monitoring with modern UI
- Beautiful dark theme with color-coded status indicators
- Console window for debug information
- User settings system with persistent storage
- Auto-loot system with three modes:
  - Automatic loot when all bots finish
  - Emergency loot at scheduled time
  - Threshold-based loot after X cards
- Telegram notification system
- Auto-update system via GitHub
- Manual loot button
- Statistics dashboard
- About dialog with developer credits

#### 🎛️ Settings
- Telegram bot token and chat ID configuration
- Emergency loot time selection
- Cards threshold customization
- Toggle for each auto-loot feature
- ASF IPC URL configuration

#### 🔄 Auto-Update
- Automatic update checking on startup
- One-click update installation
- Support for forced updates
- GitHub-based distribution

#### 📱 Telegram
- Notifications for all loot actions
- Detailed loot results
- Enable/disable from settings

#### 💻 Technical
- Built with PyQt6
- Single EXE deployment
- No Python installation required for end users
- Settings stored in JSON file
- Automatic settings reload

---

## [Unreleased]

### Planned Features
- Multi-language support
- Discord integration
- Custom themes
- Advanced statistics
- Enhanced bot management
- Export/import settings

---

## Template for Future Releases

## [X.X.X] - YYYY-MM-DD

### ✨ Added
- New feature 1
- New feature 2

### 🔧 Changed
- Changed behavior 1
- Updated UI element

### 🐛 Fixed
- Bug fix 1
- Bug fix 2

### 🗑️ Removed
- Deprecated feature

### ⚡ Performance
- Performance improvement 1

### 🔒 Security
- Security fix 1

---

## Version Numbering

We use Semantic Versioning (SemVer):
- **MAJOR** version (X.0.0): Incompatible API changes
- **MINOR** version (0.X.0): New features, backward-compatible
- **PATCH** version (0.0.X): Bug fixes, backward-compatible

Examples:
- `1.0.0` → Initial release
- `1.1.0` → Added new feature
- `1.1.1` → Fixed bug
- `2.0.0` → Major redesign/breaking changes

---

## How to Use This Changelog

### When Releasing a New Version:

1. **Update version in code**:
   ```python
   APP_VERSION = "1.0.1"  # In ASF_PSA_Dashboard.py
   ```

2. **Add new section in this file**:
   ```markdown
   ## [1.0.1] - 2024-02-15
   
   ### 🐛 Fixed
   - Fixed Telegram notification bug
   - Corrected time display in dashboard
   
   ### ✨ Added
   - Added new color theme option
   ```

3. **Build and release**:
   - Build new EXE
   - Create GitHub release
   - Update version.json

4. **Commit changes**:
   ```bash
   git add CHANGELOG.md
   git commit -m "Release v1.0.1"
   git push
   ```

---

## Categories Explained

### ✨ Added
New features that have been added.

### 🔧 Changed
Changes in existing functionality.

### 🗑️ Deprecated
Features that will be removed in upcoming releases.

### 🗑️ Removed
Features that have been removed.

### 🐛 Fixed
Bug fixes.

### 🔒 Security
Security-related fixes and improvements.

### ⚡ Performance
Performance improvements.

### 📝 Documentation
Documentation changes.

---

**Developed by Aluc4d** ❤️
