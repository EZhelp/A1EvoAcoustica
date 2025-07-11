# A1 Evo Acoustica beta for adjustable EDC mod
Audyssey-based Sound Optimization Tool for Denon/Marantz AVRs.

Harnessing the power of [REW](https://www.roomeqwizard.com/) and proprietary algorithms, A1 Evo aims to produce world-class room correction for MultEQ, MultEQ XT, and XT32 AVRs. Improvements remain worthwhile for basic MultEQ, but improve further with more capable XT & XT32 hardware.

AVRs must be compatible with MultEQ Mobile app (~2016 onward), though the app itself is not required.

### Key Resources
* [YouTube Guide](https://www.youtube.com/watch?v=wQHF0-MOMMY)
* [Downloads](https://drive.google.com/drive/folders/1O-KcP9jfBYZePW9lGPE2sbqrx_x96Vrr)
* [Discussion thread](https://www.avsforum.com/threads/acoustica-latest-and-greatest-from-oca-for-denon-marantz-only.3324025/)
* [Quick Guide Windows](./docs/quick-guide-windows.md)
* [Quick Guide Mac](./docs/quick-guide-mac.md)

### Local Build & Development

#### Prerequisites

- [Git](https://git-scm.com/downloads) - Version control system
- [Node.js](https://nodejs.org/) - JavaScript runtime (v18 or later recommended)
- [npm](https://www.npmjs.com/) - Package manager (included with Node.js)

##### Linux Installation Example (Debian/Ubuntu)

```bash
# Update package lists
sudo apt update

# Install Git
sudo apt install git

# Install Node.js and npm using NodeSource repository
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
sudo apt install -y nodejs

# Verify installations
git --version
node --version
npm --version
```

#### Clone the Repository

```bash
git clone https://github.com/ObsessiveCompulsiveAudiophile/A1EvoAcoustica.git
cd A1EvoAcoustica
```

#### Install Dependencies

```bash
npm ci
```

#### Start the Program

```bash
npm start
```

This will launch the A1 Evo Acoustica tool.

#### Build Executables

```bash
npm run build
```

Or for a specific platform ([available options](./package.json))

```bash
npm run build-windows
```

[LICENSE](./LICENSE)
