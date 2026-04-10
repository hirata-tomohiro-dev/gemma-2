# Gemma 3 Linux Offline Bundle Part 2

このリポジトリは、`gemma` repo を補完するための model split file 置き場です。

この repo 単体では起動できません。`gemma` repo と同じ親ディレクトリに配置してください。

GitHub ZIP の場合:

```text
/opt/offline/
  gemma-main/
  gemma-2-main/
```

clone の場合:

```text
/opt/offline/
  gemma/
  gemma-2/
```

含まれるもの:

- `bundle/linux/vendor/models/gemma3-1b-it-qat.gguf.part-05`
- `bundle/linux/vendor/models/gemma3-1b-it-qat.gguf.part-06`
- `bundle/linux/vendor/models/gemma3-1b-it-qat.gguf.part-07`
- `bundle/linux/vendor/models/gemma3-1b-it-qat.gguf.part-08`
- `bundle/linux/vendor/models/gemma3-1b-it-qat.gguf.part-09`
- `bundle/linux/vendor/models/gemma3-1b-it-qat.gguf.part-10`

実行は `gemma` repo 側の `bundle/linux/install-gemma3-openai-offline.sh` と `bundle/linux/start-gemma3-openai-server.sh` を使ってください。
