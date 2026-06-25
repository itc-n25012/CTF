# Webサーバ構築マニュアル（Apache + Basic認証）

## 1. Apacheインストール

```bash
sudo apt update
sudo apt install apache2 apache2-utils -y
```

## 2. Apache起動

```bash
sudo systemctl start apache2
sudo systemctl enable apache2
```

確認
```bash
sudo systemctl status apache2
```
~                                                                                        
~                               
