# 🧹 visyo

> **⚠️ Notice: Work in Progress**

> This project is not yet complete and is still being developed.

```text
       _
__   _(_)___ _   _  ___
\ \ / / / __| | | |/ _ \
 \ V /| \__ \ |_| | (_) |
  \_/ |_|___/\__, |\___/
             |___/
```

**Visyo** — ✨ A fast, minimal, and themeable CLI tool that displays **visual system output** across platforms.

## ✨ Features

-   **Cross-Platform Support**: Works seamlessly on Linux, macOS, Windows, and more.
-   **Fast and Lightweight**: Optimized for speed and minimal resource usage.
-   **Customizable Themes**: Personalize the visual output with a flexible theming system.
-   **Detailed System Information**: Displays kernel version, uptime, memory usage, processor load, and more.
-   **Error Diagnosis**: Use the `--doctor` flag to troubleshoot fetching issues.
-   **Modular Design**: Separate configuration and themes for better portability and modularity.
-   **Prebuilt Binaries**: Easily install with prebuilt binaries for quick setup.
-   **Open Source**: Actively maintained and open to contributions from the community.
-   **Extensive Documentation**: Comprehensive guides for installation, configuration, and customization.
-   **Community-Driven**: Built with feedback and contributions from a vibrant community.

## 🚀 Installation

To install **visyo**, simply clone the repository and follow the instructions below:

```bash
git clone git@github.com:trinhminhtriet/visyo.git
cd visyo

cargo build --release
ln -sf ${PWD}/target/release/visyo /usr/local/bin/visyo
```

Running the below command will globally install the `visyo` binary.

```bash
cargo install visyo
```

Optionally, you can add `~/.cargo/bin` to your PATH if it's not already there

```bash
echo 'export PATH="$HOME/.cargo/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

## 💡 Usage

Run **visyo** with the following command to start cleaning your filesystem:

```sh
./visyo [options] [path]

```

## 🤝 How to contribute

We welcome contributions!

-   Fork this repository;
-   Create a branch with your feature: `git checkout -b my-feature`;
-   Commit your changes: `git commit -m "feat: my new feature"`;
-   Push to your branch: `git push origin my-feature`.

Once your pull request has been merged, you can delete your branch.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
