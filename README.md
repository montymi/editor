<div id="readme-top"></div>

<!-- PROJECT SHIELDS -->
[![Creator][creatorLogo]][creatorProfile]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![GPL License][license-shield]][license-url]

<!-- PROJECT HEADER -->
# 📜 EDITOR

Custom Neovim configuration, initially forked from [LazyVim](https://github.com/montymi/LazyVim/starter), tailored for enhanced efficiency and personalized workflow. 

<!-- CALL TO ACTIONS -->
[![🚀 Explore Demo][demoLogo]][demoLogo-url]
[![🐛 Report Bug][bugLogo]][bugLogo-url]
[![✨ Request Feature][featureLogo]][featureLogo-url]

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#installation">Installation</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#setup">Setup</a></li>
      </ul></li>
    <li><a href="#usage">Usage</a>
      <ul>
        <li><a href="#getting-started">Getting Started</a></li>
        <li><a href="#advanced">Advanced</a></li>
      </ul></li>
    </li>
    <li><a href="#structure">Structure</a></li>
    <li><a href="#tasks">Tasks</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<br />

<!-- ABOUT THE PROJECT -->
## About The Project

This project is a Neovim configuration initiated from LazyVim/starter. It offers a comprehensive and modular setup aimed at enhancing the Neovim experience. The configuration is written entirely in Lua, ensuring efficient and flexible customization options.

### Key features include:

- Modular Configuration: Easily enable or disable plugins and settings.
- Performance Optimizations: Leverages LazyVim's optimizations for a faster editing experience.
- Extensibility: Seamlessly integrates with additional plugins and configurations.

### Built With

[![neovim][neovimLogo]][neovimLogo-url]
[![Lua][luaLogo]][luaLogo-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Installation

Script soon to be made, which will handle install of requirements and many near must-haves.

### Prerequisites
Ensure you have [git](https://git-scm.com/). Best bet, download the official release for your platform (Operating System) from the provided homepages and their download section. On Windows, your best bet is to use the resulting Git Bash application that will become available after installing git.

### Requirements

- Neovim >= 0.9.0 (built with LuaJIT)
- Git >= 2.19.0 (for partial clones support)
- A Nerd Font (optional)
- A C compiler for nvim-treesitter

Comfirm prerequisites by running the following command:
```bash
git --version && nvim --version
```

Download the repo locally before moving to correct folder:
```bash
git clone https://github.com/montymi/editor/
```

### Setup

For Unix, run:
```bash
sudo mv ./editor ~/.config/nvim
```
For Windows, run as Administartor:
```bash
mv ./editor ~/AppData/Local/nvim
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

### Getting Started

Start neovim and you should see automatic installations and, eventually, the custom starter screen, run:
```bash
nvim
```

Next, while still in neovim, perform a system diagnostics on the editor by typing:
```
:checkhealth
```
The result of your typing should appear in the middle center of the screen (with the : omitted)

### Advanced

#### Customizing Plugins
To customize plugins, modify the configuration in the `lua/plugins` directory. Refer to the [LazyVim documentation](https://github.com/LazyVim/LazyVim) for detailed instructions on customizing each plugin.

#### Advanced Configuration
For advanced configuration, such as setting up key bindings or autocommands, you can edit the `init.lua` file in the root directory. This file allows you to configure various Neovim settings and behaviors.

#### Performance Tuning
If you experience performance issues, consider profiling your Neovim startup time using tools like `nvim --startuptime`. You can also disable unnecessary plugins or features that you do not use frequently.

#### Troubleshooting
If you encounter issues, check the Neovim logs located at `~/.local/share/nvim/log`. Additionally, you can seek help from the [Neovim community](https://neovim.io/community) or the [LazyVim discussion forums](https://github.com/LazyVim/LazyVim/discussions).

For more detailed usage and advanced configurations, refer to the [LazyVim documentation](https://github.com/LazyVim/LazyVim).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- STRUCTURE -->
## Structure

```
editor
├── README.md
├── .gitignore
├── .neoconf.json
├── LICENSE
├── lazyvim.json
├── stylua.toml
├── init.lua
└── lua
    ├── config
    │   ├── autocmds.lua
    │   ├── keymaps.lua
    │   ├── lazy.lua
    │   └── options.lua
    └── plugins
        ├── example.lua # MORE THAN AN EXAMPLE
        └── mini-starter.lua # Custom welcome/start page
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- TASKS -->
## Tasks

- [ ] Create script to automate initial requirement collection
- [ ] Create script to automate neovim setup
- [ ] Add locally hosted AI copilot with `llm.nvim` and [ollama][ollamaLogo-url]

See the [open issues](https://github.com/montymi/ClearDocs/issues) for a full list of issues and proposed features.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

1. [Fork the Project](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. [Open a Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the Apache License. See `LICENSE.txt` for more information.

<br />

<!-- CONTACT -->
## Contact

Michael Montanaro

[linkedin-shield]: https://cdn-icons-png.flaticon.com/512/174/174857.png
[github-shield]: https://cdn-icons-png.flaticon.com/512/733/733553.png
[linkedin-url]: https://linkedin.com/in/michael-montanaro
[github-url]: https://github.com/montymi

<a href="https://linkedin.com/in/michael-montanaro/" target="_blank">
  <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="20" height="20" />
</a>
<a href="https://github.com/montymi/" target="_blank">
  <img src="https://cdn-icons-png.flaticon.com/512/733/733553.png" width="20" height="20" />
</a>

<br />

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [LazyVim](https://github.com/LazyVim)
* [Neovim][neovimLogo-url]
* [ClearDocs](https://github.com/montymi/ClearDocs)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[ollamaLogo]: https://img.shields.io/badge/Ollama-black?style=for-the-badge&logo=ollama&logoColor=natural
[ollamaLogo-url]: https://ollama.com
[neovimLogo]: https://img.shields.io/badge/Neovim-black?style=for-the-badge&logo=neovim&logoColor=natural
[neovimLogo-url]: https://neovim.io
[luaLogo]: https://img.shields.io/badge/Lua-black?style=for-the-badge&logo=lua&logoColor=natural
[luaLogo-url]: https://lua.org
[demoLogo]: https://img.shields.io/badge/🚀%20Explore%20Demo-grey?style=for-the-badge
[demoLogo-url]: https://github.com/montymi/ClearDocs
[bugLogo]: https://img.shields.io/badge/🐛%20Report%20Bug-grey?style=for-the-badge
[bugLogo-url]: https://github.com/montymi/ClearDocs/issues
[featureLogo]: https://img.shields.io/badge/✨%20Request%20Feature-grey?style=for-the-badge
[featureLogo-url]: https://github.com/montymi/ClearDocs/issues
[pythonLogo]: https://img.shields.io/badge/Python-black?style=for-the-badge&logo=python&logoColor=natural
[pythonLogo-url]: https://python.org/
[markdownLogo]: https://img.shields.io/badge/Markdown-black?style=for-the-badge&logo=markdown&logoColor=natural
[markdownLogo-url]: https://daringfireball.net/projects/markdown/
[htmlLogo]: https://img.shields.io/badge/HTML5-black?style=for-the-badge&logo=html5&logoColor=natural
[htmlLogo-url]: https://html.spec.whatwg.org/
[creatorLogo]: https://img.shields.io/badge/-Created%20by%20montymi-maroon.svg?style=for-the-badge
[creatorProfile]: https://montymi.com/
[contributors-shield]: https://img.shields.io/github/contributors/montymi/ClearDocs.svg?style=for-the-badge
[contributors-url]: https://github.com/montymi/ClearDocs/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/montymi/ClearDocs.svg?style=for-the-badge
[forks-url]: https://github.com/montymi/ClearDocs/network/members
[stars-shield]: https://img.shields.io/github/stars/montymi/ClearDocs.svg?style=for-the-badge
[stars-url]: https://github.com/montymi/ClearDocs/stargazers
[issues-shield]: https://img.shields.io/github/issues/montymi/ClearDocs.svg?style=for-the-badge
[issues-url]: https://github.com/montymi/ClearDocs/issues
[license-shield]: https://img.shields.io/github/license/montymi/ClearDocs.svg?style=for-the-badge
[license-url]: https://github.com/montymi/ClearDocs/blob/master/LICENSE.txt
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
