# 学子论坛0529

@ShanghaiTech University  
Speaker: Siyun Liu

## PDF to Markdown

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

## RSS Subscription

Chrome Extension: [RSSHub Radar](https://chromewebstore.google.com/detail/rsshub-radar/kefjpfngnndepjbopdmoebkipbgkggaa?hl=en-US&utm_source=ext_sidebar)

RSS Reader: [Folo](https://github.com/RSSNext/Folo)]

- Try on the Browser: [Web App](https://app.follow.is/)
- Install `Folo` on MacOS:
  ```shell
  brew install --cask folo
  ```
- Install `Folo` on Windows with scoop
  ```shell
  scoop install folo
  ```

