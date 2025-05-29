# 学子论坛 0529

@ShanghaiTech University  
Speaker: Siyun Liu

## Markdown Convertor

### PDF to markdown

[Marker from VikParuchuri](https://github.com/VikParuchuri/marker)

For conda user to try `marker`, install it with the following commands.

```shell
conda create --name marker
conda activate marker
conda install pip
pip install marker-pdf
```

Simplest command for converting a `PDF` file to `markdown` format

```shell
marker_single /path/to/file.pdf --output_dir /path/to/file
```

If you would like to apply LLM (Gemini is the default option)

```shell
marker_single /path/to/file.pdf --output_dir /path/to/file --use_llm --gemini_api_key your_api
```

[Markitdown from Microsoft](https://github.com/microsoft/markitdown)

### Website to markdown

Extension: [Simp Read](https://simpread.pro/)

## RSS Subscription

Chrome Extension: [RSSHub Radar](https://chromewebstore.google.com/detail/rsshub-radar/kefjpfngnndepjbopdmoebkipbgkggaa?hl=en-US&utm_source=ext_sidebar)

RSS Reader: [Folo](https://github.com/RSSNext/Folo)

Installation:

- Try on the Browser: [Web App](https://app.follow.is/)
- Install `Folo` on MacOS
  ```shell
  brew install --cask folo
  ```
- Install `Folo` on Windows with scoop
  ```shell
  scoop install folo
  ```

## Fragments

Cubox: [Web App](https://cubox.pro/)

> [!CAUTION]
> Choose the Chinese server instead of the international one, which is much better for localized content.

## Obsidian

### Basic

[Official Website](https://obsidian.md/)

[Obsidian Help](https://help.obsidian.md/)

Installation:

- Install `Obsidian` on MacOS
  ```shell
  brew install --cask obsidian
  ```
- Install `Obsidian` on Windows
  ```shell
  winget install Obsidian.Obsidian
  ```

### Useful Plugins

- Remotely Save
  - Recommend WebdAV synchronization
- Zotero Integration
- Dataview
  - [Example Vault](https://github.com/s-blu/obsidian_dataview_example_vault)
- Mermaid Tools
  - [Official documentation](https://mermaid.js.org/intro/)
- [Math Indicator Changer](https://github.com/Ori-Replication/obsidian-math-indicator-changer)

### Copilot

API Call:

- DeepSeek and Qwen, check [siliconflow](https://cloud.siliconflow.cn/models)

- Cost-effective choice: [Gemini](https://ai.google.dev/gemini-api/docs)

## Alternative for academic research - AnythingLLM

Installation:

- Install `AnythingLLM` on MacOS
  ```shell
  brew install --cask anythingllm
  ```
- Install `AnythingLLM` on Windows with scoop
  ```shell
  scoop install anythingllm
  ```

## Local LLM Deployment

- Ollama
- LM Studio

## More Tools

1. Package Manager

- [Homebrew](https://brew.sh/)
- [winget](https://learn.microsoft.com/en-us/windows/package-manager/winget/)

2. Password Manager

- [1Password](https://1password.com/) (requiring VISA card)
- [Password Generator](https://1password.com/zh-cn/password-generator) from 1Password

3. Reading

- [Koodo Reader](https://github.com/koodo-reader/koodo-reader): recommend the PRO version for seamless experience
- Bionic reading method
  - Edge/Chrome extension: [Bionic Reading](https://chromewebstore.google.com/detail/bionic-reading-aaread/glncdcmjopmgniilckffbhcpkgambpko)
  - Firefox extension: [Bionic Reader](https://addons.mozilla.org/en-GB/firefox/addon/bionic-reader/?utm_content=addons-manager-reviews-link&utm_medium=firefox-browser&utm_source=firefox-browser)
  - Application: [Bionic Reading](https://bionic-reading.com/)
