# vscode_setting

## 拡張機能

[extensions.txt](extensions.txt)はサーバー側に設定する。

### 保存

```bash
code --list-extensions | tail -n +2 > extensions.txt
```

### 反映

```bash
cat extensions.txt | xargs -L 1 code --install-extension
```

## 設定

[settings.json](settings.json)はサーバー側に設定する。

## キーバインド

[keybindings.json](keybindings.json)はクライアント側に設定する。
