<div align="center">
  <h1>MeshyDownloader</h1>
  <p><strong>Extracts and downloads decrypted <code>.glb</code> 3D models directly from public Meshy.ai share links.</strong></p>

  <p>
    <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.10+-blue.svg?style=flat-square&logo=python&logoColor=white" alt="Python" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-CC0%201.0-yellow.svg?style=flat-square" alt="License: CC0 1.0" /></a>
    <a href="https://pypi.org/project/websockets/"><img src="https://img.shields.io/badge/Dependency-websockets%2011.0+-green.svg?style=flat-square" alt="websockets" /></a>
  </p>
</div>

<p align="center">
  <img src="assets/demo.gif" alt="MeshyDownloader Live Demo" width="100%" />
</p>

> [!IMPORTANT]
> **Requirements**: Windows 10/11 and Google Chrome installed natively for headless debugging injection.

MeshyDownloader provides a desktop GUI that intercepts decrypted 3D model data directly inside the browser's web worker in real time, extracting clean `.glb` files from public Meshy.ai links without requiring browser DevTools inspection.

## Quickstart

```bash
git clone https://github.com/IamOumarIbrahim/meshydownloader-glb-extractor.git
cd meshydownloader-glb-extractor
pip install websockets
python meshy_downloader.py
```

1. Paste a public Meshy.ai share link (e.g. `https://www.meshy.ai/s/...`).
2. Select destination folder and click **Extract & Download Model**.

## Limitations

- **Platform**: Tested and optimized for Windows 10/11.
- **Browser**: Requires native Google Chrome for remote debugging injection.

## License

Dedicated to the public domain under [CC0 1.0 Universal](LICENSE).
