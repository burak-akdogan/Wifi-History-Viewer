# WiFi History Viewer

A Windows app that shows your WiFi connection history from the Windows Event Log.


---

## Requirements

- Windows 10 / 11
- Python 3.9+

```bash
pip install -r requirements.txt
```

---

## Run

```bash
python wifi_history_viewer.py
```

Or just double-click **`WifiHistoryViewer.exe`** — no Python needed.

> For full history, run as Administrator via **Options → Run As Administrator**.

---

## Build EXE

```bash
pyinstaller --onefile --windowed --icon="wifi_icon.ico" --name="WifiHistoryViewer" wifi_history_viewer.py
```

---

## License

MIT © 2026 Burak Akdogan
