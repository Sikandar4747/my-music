# Sikandar's Music

An unofficial cross platform desktop app for YouTube Music.

![Sikandar's Music](.github/images/readme_main_app.png)

Sikandar's Music is a personal fork of [YTMDesktop](https://github.com/ytmdesktop/ytmdesktop) by the YTMDesktop Team, licensed under [GPL-3.0](LICENSE). All credit for the original application goes to its authors and contributors.

# Developing

```bash
# Clone this repository
git clone https://github.com/Sikandar4747/my-music.git
# Go into the directory
cd my-music
# Install dependencies (this project uses pnpm)
pnpm install
# Run the app
pnpm start
```

# Building the Project
To build for your platform, run `pnpm make`. The tools you need for each platform are listed below.

## Windows
The recommended way to get the tools you need (Visual Studio, Python and others) is Electron's build tools:

`npm i -g @electron/build-tools`

## Linux
- For Debian based distros like Ubuntu, install `fakeroot` and `dpkg`
- For RedHat based distros like Fedora, install `rpm` or `rpm-build`

By default both packages are built on Linux.

# License
GPL-3.0-only. See [LICENSE](LICENSE).
