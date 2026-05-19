# ImageCompressor

Website: [woaimaihao.com](https://woaimaihao.com)

ImageCompressor is a local Windows desktop tool for compressing images and converting them to WebP. It supports drag-and-drop input and uses Sharp for image processing.

## Download

Download one of the packaged builds from the `dist` folder:

- `dist/ImageCompressor-1.0.0-installer.zip` - Windows installer package
- `dist/ImageCompressor-1.0.0-portable.zip` - portable Windows executable

After downloading, unzip the package and run the `.exe` file inside.

## Features

- Drag and drop local images
- Compress images to smaller WebP files
- Batch processing workflow
- Local processing, no online upload required

## Development

Install dependencies:

```bash
npm install
```

Run the app locally:

```bash
npm start
```

Build Windows packages:

```bash
npm run build
```

Run the smoke test:

```bash
node test/smoke.js
```

## 仓库网站外链

如果想把你的网站作为外链显示在 GitHub 仓库页面：

1. 打开 GitHub 上的仓库页面。
2. 点击右侧 About 区域旁边的齿轮图标。
3. 在 Website 字段里填入你的网站地址。
4. 点击 Save changes 保存。

也可以像当前 README 顶部这样，把网站链接直接放在文档最上方，方便访问者第一眼看到。
