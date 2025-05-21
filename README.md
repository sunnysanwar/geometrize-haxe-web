# 🎨 GeoMagic 🧠 Art Machine

🎯 **Live Demo:** [GeoMagic-Art-Machine](https://sunnysanwar.github.io/geometrize-haxe-web/)

> Transform your images into stunning abstract art by evolving colorful geometric shapes rendered dynamically on an HTML5 Canvas. Watch your images come alive with triangles, ellipses, curves, and more — all in real time with creative algorithms.

## ✨ Features

* Real-time image transformation on a responsive HTML5 Canvas.
* Customize shape types: rectangles, rotated rectangles, triangles, ellipses, rotated ellipses, circles, lines, and Bezier curves.
* Adjust shape opacity, background opacity, mutation rate, and randomness with intuitive sliders and checkboxes.
* Interactive controls with instant visual feedback.
* Export your artwork as PNG, SVG, or JSON.
* Open-source, inspired by Michael Fogleman’s [primitive](https://github.com/fogleman/primitive).

## 🛠️ Getting Started

1. Clone the Repository

```bash
git clone https://github.com/sunnysanwar/geometrize-haxe-web.git
cd docs
```

2. Run the App Locally

* Open `index.html` directly in your browser, **or**
* Serve files locally with Python HTTP server:

```bash
python -m http.server 8000
```

Then open your browser and go to `http://localhost:8000`

## 🎯 How It Works

GeoMagic uses an HTML5 canvas to dynamically render your uploaded image as a composition of evolving geometric shapes. Pick your shape types, adjust settings, and watch your photo turn into abstract art in real time!

## 🎛️ Interface Overview

* **Canvas Window**: Displays the evolving geometric art.
* **Shape Controls**: Enable/disable shape types (rectangles, triangles, ellipses, etc.).
* **Sliders**: Adjust opacity, mutation rate, randomness, and shape limits.
* **Buttons**: Run/Pause, Step, Open Image, Random Image, Reset.
* **Save Options**: Export as PNG, SVG, or JSON.

## 📷 Example Outputs

![Example Flower](https://github.com/sunnysanwar/geometrize-haxe-web/blob/main/screenshots/flower.png)
![Example Butterfly](https://github.com/sunnysanwar/geometrize-haxe-web/blob/main/screenshots/monarch_butterfly.png)

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙌 Acknowledgments

* Built using [Geometrize Haxe](https://github.com/Tw1ddle/geometrize-haxe).
* Inspired by the original [primitive](https://github.com/fogleman/primitive) concept by Michael Fogleman.