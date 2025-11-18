# Video_Splitter
簡単な操作で、動画を一定の間隔に分割できます。
このアプリはWindows10または11上での動作を前提としています。

環境構築に必要なツール:
- ffmpeg (下記詳細)
- python 3.12 or higher.
- Pythonパッケージに関してはコードを直接ご覧ください。

PythonがインストールされていないPCで利用したい場合は、予めPythonがインストールされているPCで次のコマンドを実行し、exeファイルを生成してください。
ただし、動作が遅くなることがあります。
```
pip install pyinstaller
pyinstaller <<file path>> --onefile --noconsole
```

ffmpegは様々なインストール方法がありますが、Windowsの場合は、次のコマンドをコマンドプロンプトやPowerShell上で実行するのが最も簡単だと思います。
```
winget install --id=Gyan.FFmpeg -e
```

このアプリケーションはご自由にダウンロード・改変して頂いて構いませんが、自分向けに開発したものですので動作保証は致しかねます。
