# Project Sirius

<p align="center">
  <strong>Porting Discovery Freelancer 4.86 to the Open-Source LibreLancer Engine</strong>
</p>

<p align="center">
  <em>A community-driven effort to bring the Discovery Freelancer experience to a modern, cross-platform game engine</em>
</p>

---

## 📖 What is Project Sirius?

**Project Sirius** is an ambitious community project that aims to port **Discovery Freelancer 4.86 (Episode 14 - Exiles)** — one of the most comprehensive and beloved Freelancer mods ever created — to the open-source **LibreLancer** engine.

### The Vision

Freelancer, released by Digital Anvil and Microsoft in 2003, remains a cult classic space trading and combat game. The Discovery mod transformed it into an expansive multiplayer universe with hundreds of ships, dozens of new systems, deep faction politics, and a vibrant roleplaying community that has thrived for nearly two decades.

However, the original Freelancer engine is over 20 years old, limited to Windows, and increasingly difficult to run on modern systems. **Project Sirius** seeks to preserve and modernize this experience by:

- **Porting Discovery 4.86 content** to LibreLancer's modern rendering pipeline
- **Enabling cross-platform play** on Windows, Linux, and macOS
- **Improving graphics and performance** with modern OpenGL/Vulkan rendering
- **Preserving the Discovery experience** while enabling future enhancements

---

## 🎮 About Discovery Freelancer 4.86

Discovery Freelancer 4.86 "Episode 14 - Exiles" is the culmination of over a decade of community development. Set in the year 818 A.S., it expands the Freelancer universe with:

### Content Scale

| Feature | Total | Added by Discovery |
|---------|-------|-------------------|
| **Player Ships** | 290 | 255 |
| **Star Systems** | 152 | 97 |
| **Bases & Stations** | 617 | 444 |
| **Factions** | 139 | 92 |
| **Weapons** | 250+ | 250+ |
| **Commodities** | 275 | 200+ |
| **Infocard Texts** | 15,000+ | 15,000+ |

### The Storyline

> *The year is 818 A.S. and war is everywhere.*

Seventeen years after Trent saved humanity, Sirius-wide conflict engulfs the sector:

- **Liberty** has dealt a devastating blow to Rheinland, seizing invaluable research
- **Gallia** has been unleashed upon Sirius, their Grand Armée storming through the Taus
- **Bretonia** faces extinction as Gallic forces prepare to strike Leeds
- **Kusari** has undergone a governmental overthrow, with Emperor Kogen now an exile
- **The Ronin**, displaced Kusarian forces, forge an unlikely alliance with their former enemies

War rages throughout Sirius. Armadas larger than ever before face off. It is a time of uncertainty and danger.

---

## 🔧 About LibreLancer

[LibreLancer](https://github.com/Lazrius/Librelancer) is an open-source reimplementation of the Freelancer game engine, created by Callum McGing. It provides:

- **Modern Rendering**: OpenGL 3.1+ with support for advanced shaders and post-processing
- **Cross-Platform**: Native support for Windows, Linux, and macOS
- **Improved Tools**: Built-in editors for systems, ships, and game content
- **Active Development**: Ongoing improvements and bug fixes
- **Mod Support**: Designed to work with Freelancer mods and total conversions

---

## 🚀 Project Status

Project Sirius is currently in **active development**. We are working on:

### Completed
- [x] Initial LibreLancer engine integration
- [x] Discovery 4.86 data file parsing
- [x] Basic system loading and rendering
- [x] Ship model loading and display
- [x] Equipment and weapon systems
- [x] UI framework integration

### In Progress
- [ ] Post-processing effects (Vignette, Film Grain, SSAO)
- [ ] Deferred rendering pipeline optimization
- [ ] Advanced lighting and shadows
- [ ] Full multiplayer server compatibility
- [ ] Sound system integration

### Planned
- [ ] Complete Discovery content verification
- [ ] Performance optimization passes
- [ ] Cross-platform testing
- [ ] Community server infrastructure
- [ ] Documentation and modding guides

---

## 📦 Installation

### Prerequisites

- **.NET 10.0 SDK** or later
- **Visual Studio 2022** or compatible IDE (for development)
- **Original Freelancer installation** (required for base game assets)
- **Discovery Freelancer 4.86** (required for mod content)

### Building from Source

```bash
# Clone the repository
git clone https://github.com/your-repo/project-sirius.git
cd project-sirius

# Navigate to the LibreLancer source
cd Librelancer/Source\ Code

# Build the solution
dotnet build LibreLancer.sln --configuration Release

# Run the game
dotnet run --project src/Launcher/Launcher.csproj
```

### Configuration

1. Launch the game and navigate to **Settings**
2. Set the **Game Data Path** to your Discovery 4.86 installation directory
3. The game will automatically detect and load Discovery content

---

## 🎨 Features

### Modern Graphics

Project Sirius leverages LibreLancer's modern rendering capabilities:

- **Dynamic Lighting**: Real-time point lights, directional lights, and shadows
- **Post-Processing**: Vignette, film grain, heat haze, and SSAO effects
- **High-Resolution Support**: Native 4K and ultrawide monitor support
- **Improved Particle Effects**: Enhanced explosion, thruster, and weapon effects

### Gameplay Enhancements

- **Improved Physics**: Better collision detection and ship handling
- **Enhanced UI**: Modernized interface with better scaling and readability
- **Quality of Life**: Various improvements based on community feedback

### Preservation

- **Content Fidelity**: Faithful recreation of the Discovery 4.86 experience
- **Compatibility**: Designed to work with existing Discovery save files (where possible)
- **Community Focus**: Built by the community, for the community

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### Code Contributions

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Other Ways to Help

- **Testing**: Play the game and report bugs
- **Documentation**: Improve guides and documentation
- **Content Verification**: Help verify Discovery content renders correctly
- **Community Support**: Help other users on forums and Discord

---

## 📚 Documentation

- [Project Wiki](./Documentation/) - Detailed technical documentation
- [LibreLancer Docs](https://github.com/Lazrius/Librelancer/wiki) - LibreLancer engine documentation
- [Discovery Wiki](https://discoverygc.com/wiki) - Discovery Freelancer lore and content

---

## 🙏 Credits

### Project Sirius Team
- Community contributors and developers

### LibreLancer Engine
- **Callum McGing** - Original author and primary developer
- LibreLancer contributors

### Discovery Freelancer 4.86
- **Discovery Development Team**: Alexander "Igiss" Zalessky, Aeternus Doleo, Blodo, Evan "Dab" Sondgerath, Friday, Jinx, Linkus, Lohingren, Martin "Mjolnir" Rytir, Matt "Cannon" Dean, Silent Assassin, Shemkel, Treewyrm, Xoria, and many others
- **Discovery Gaming Community** - For nearly two decades of passion and creativity

### Original Freelancer
- **Digital Anvil** - Original game development
- **Microsoft Game Studios** - Publishing

---

## ⚖️ Legal

Project Sirius is a non-commercial, community-driven project created for educational and preservation purposes. It is not affiliated with, endorsed by, or connected to Microsoft Corporation, Digital Anvil, or the Discovery Development Team.

- LibreLancer engine code is licensed under the **MIT License**
- Project Sirius modifications are licensed under the **MIT License**
- Discovery Freelancer content remains property of the Discovery Development Team
- Original Freelancer assets remain property of Microsoft/Digital Anvil

See [LICENSE](./LICENSE) for full details.

---

## 🔗 Links

- **Discovery Gaming Community**: [https://discoverygc.com](https://discoverygc.com)
- **Discovery Wiki**: [https://discoverygc.com/wiki](https://discoverygc.com/wiki)
- **LibreLancer**: [https://github.com/Lazrius/Librelancer](https://github.com/Lazrius/Librelancer)

---

<p align="center">
  <em>"War rages throughout Sirius. It is a time of uncertainty and danger, as both known and unknown foes threaten the balance in Sirius."</em>
</p>

<p align="center">
  Made with ❤️ by the Freelancer community
</p>
