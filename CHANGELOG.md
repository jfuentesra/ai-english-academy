# Changelog

All notable changes to the AI English Academy project will be documented in this file.

## [v1.1.0] - 2026-03-03

### ✨ Added
- **Enhanced PWA Manifest** with shortcuts, screenshots, and share target capabilities
  - Added app shortcuts for quick access to Chat and Lessons
  - Added multiple resolution app icons (192x192, 512x512)
  - Implemented share target for text and audio files
  - Improved app categories and metadata

- **Improved Service Worker**
  - Implemented network-first caching strategy
  - Added better error handling and fallback mechanisms
  - Background sync ready for future progress syncing
  - Smart cache cleanup on activation
  - Comprehensive logging for debugging

- **Complete README Overhaul**
  - Professional English content with proper formatting
  - Detailed feature comparison table vs competitors
  - Cost savings calculation ($360/year vs Duolingo Max)
  - Step-by-step installation guides for all platforms
  - Learning levels structure (A1-C2)
  - Sample idioms organized by level
  - Contribution guidelines
  - Roadmap for future versions
  - Spanish language bonus section

### 🔧 Improved
- **Manifest.json**
  - More descriptive application name and short_name
  - Better description for app stores
  - Proper theme and background colors
  - Categories for app discovery
  - Screenshot configurations for install prompts

- **Service Worker (sw.js)**
  - Network-first strategy for better offline support
  - Proper handling of external APIs (Anthropic Claude)
  - Better cache version management
  - Improved error logging and debugging
  - Background sync event listener ready

### 📚 Documentation
- Complete project documentation in English
- Clear installation instructions for mobile and desktop
- Deployment guide for GitHub Pages
- Contributing guidelines with issue templates
- License information clearly stated

### 🚀 Performance
- Optimized Service Worker caching
- Better handling of network failures
- Improved offline functionality
- Faster app startup time

---

## [v1.0.0] - 2026-03-03

### ✨ Initial Features
- 60+ curated English lessons (A1-B1 levels)
- Unlimited AI conversations with Claude AI
- Voice recognition and text-to-speech
- 20+ American idioms with explanations
- Gamification system (points, XP, streaks, badges)
- Progressive Web App (PWA) support
- Works offline with Service Worker
- Automatic progress saving with LocalStorage
- Modern UI with Tailwind CSS and gradients
- React 18 single-file application
- MIT Open Source License

### 🛠️ Technology Stack
- React 18 for UI
- Tailwind CSS for styling
- Claude AI API for conversations
- Web Speech API for voice features
- Service Workers for offline support
- LocalStorage for data persistence
- Lucide Icons for UI elements

---

## Roadmap

### 🚧 v2.0 (Q2 2026)
- [ ] 200+ lessons covering B2-C2 levels
- [ ] Downloadable certificates
- [ ] Dark mode support
- [ ] Multiple interface languages
- [ ] User community features
- [ ] Competitive challenges
- [ ] Anki integration for spaced repetition
- [ ] Native mobile apps (iOS/Android)

### 🔮 v3.0 (Q3-Q4 2026)
- [ ] Human volunteer tutors
- [ ] Video call practice sessions
- [ ] Specialized courses (Business, Medical, etc.)
- [ ] Handwriting recognition
- [ ] Augmented reality features

---

## How to Contribute

We welcome all contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

### Quick Contribution Ideas
1. **Add more lessons** - Especially B2, C1, C2 levels
2. **Improve translations** - Help expand language support
3. **Fix bugs** - Report or fix issues
4. **UI/UX improvements** - Design enhancements
5. **Documentation** - Improve guides and tutorials
6. **Content creation** - Add idioms, exercises, or dialogues
7. **Testing** - Test on different devices and browsers
8. **Performance** - Optimize app speed and size

---

## Support

If you encounter any issues:

1. **Check existing issues** - Your problem might already be reported
2. **Search documentation** - Most questions are answered in README
3. **Open a new issue** - Include detailed description and screenshots
4. **Start a discussion** - Share ideas and suggestions

---

## License

MIT License - See [LICENSE](LICENSE) for details

---

**Made with ❤️ for English learners worldwide**
