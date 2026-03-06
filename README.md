# TerminalAI

Terminal için CLI AI asistanı: chat, özetleme, kod üretme, arama ve komutları otomatikleştirme.

## Kurulum

Gerekli paketleri yüklemek için:
```bash
python3 -m pip install -r requirements.txt
```

## Konfigürasyon

1. Örnek config dosyasını kopyalayın:
```bash
cp config.yaml.example config.yaml
```
2. `config.yaml` dosyasını açın ve kendi **OpenAI API key’inizi** `openai_api_key` alanına yazın.
3. Opsiyonel ayarlar:
   - `theme`: "dark" veya "light"
   - `show_ascii_art`: true / false
   - `enable_fun_commands`: true / false

## Kullanım

Demo scripti çalıştırın:
```bash
python3 terminalai.py
```

Ekranda şunu görmelisiniz:
```
Welcome to TerminalAI demo!
This is a placeholder for your AI assistant.
```

İleri seviye seçenekler için:
```bash
python3 terminalai.py --help
```
- Bu komut tüm terminal AI komutlarını gösterir.
