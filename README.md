# 学子论坛0529

@ShanghaiTech University  
Speaker: Siyun Liu

## Markdown Convertor

### PDF to markdown

[Marker from VikParuchuri](https://github.com/VikParuchuri/marker)

For conda user to try marker, install it with

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
> Choose the Chinese server instead of the international one, much better for localized content.

## Obsidian

### Basic

[Official Website](https://obsidian.md/)

[Obsidian Help](https://help.obsidian.md/)

- Install `Obsidian` on MacOS
  ```shell
  brew install --cask obsidian
  ```
- Install `Obsidian` on Windows
  ```shell
  winget install Obsidian.Obsidian
  ```

### Plugins

- Remotely Save
- Zotero Integration
- Dataview
- Mermaid Tools
- Math Indicator Changer

### Copilot

Silicon Flow: [Website](https://cloud.siliconflow.cn/models)

## More Tools

- Homebrew & winget
- 1Password
- Koodo Reader
- Bionic Reading

