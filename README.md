# JSON Crack (jsoncrack.com)

感谢jsoncrack.com做出的开源贡献，本项目在此基础上没有做任何的创新，只是将json的展示层级做了三级的处理。

> <b><a href="https://jsoncrack.com">JSON Crack - Crack your data into pieces</a></b>

## ⚡️ Features

- Search Nodes
- Share links & Create Embed Widgets
- Download/Clipboard as image
- Upload JSON locally or fetch from URL
- Great UI/UX
- Light/Dark Mode
- Advanced Error Messages

## 🛠 Development Setup

```console
  npm install
  npm run dev
```

## 🐳 Docker

A [`Dockerfile`](Dockerfile) is provided in the root of the repository.
If you want to run JSON Crack locally:

* Build a Docker image with `docker build -t jsoncrack .`
* Run locally with `docker run -p 8888:8080 jsoncrack`
* Go to http://localhost:8888

## License

This project is open source and available under the [GNU General Public License v3.0](LICENSE).
