# sukidesu

*「好きです。」*

想いを伝えるための CLI ツールです。

## 必要なもの

- curl
- Bash などの一般的なシェル環境

## インストール

ユーザー単位でインストールする場合:

```bash
mkdir -p ~/.local/bin
curl -L https://raw.githubusercontent.com/shizu-na/sukidesu/main/sukidesu -o ~/.local/bin/sukidesu
chmod +x ~/.local/bin/sukidesu
```

`~/.local/bin` が `PATH` に含まれていない場合は、`~/.bashrc` などのシェル設定ファイルに次を追加します。

```bash
export PATH="$HOME/.local/bin:$PATH"
```

設定を反映します。

```bash
source ~/.bashrc
```

システム全体で利用できるようにする場合:

```bash
sudo curl -L https://raw.githubusercontent.com/shizu-na/sukidesu/main/sukidesu -o /usr/local/bin/sukidesu
sudo chmod +x /usr/local/bin/sukidesu
```

## 使い方

```bash
sukidesu
```

## オプション

- `-f`: 答えを急かします。

## アンインストール

`~/.local/bin` に配置した場合:

```bash
rm ~/.local/bin/sukidesu
```

`/usr/local/bin` に配置した場合:

```bash
sudo rm /usr/local/bin/sukidesu
```
