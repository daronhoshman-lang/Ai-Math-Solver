# Ai-Math-Solver
# 🧠 Math AI Assistant

An AI-powered desktop math solver built with Python, Tkinter, and Ollama.

This application can solve:
- Algebra
- Calculus
- Geometry
- Basic arithmetic
- Multi-step equations
- Word problems
- Optimization problems
- And more

The app uses local AI models through Ollama, so everything runs directly on your computer.

---

# 📸 Features

- Modern desktop GUI
- AI-powered math solving
- Step-by-step explanations
- Handles complex word problems
- Runs locally with Ollama
- Dark mode interface
- Lightweight and fast
- Buildable into a standalone EXE

---

# 🛠️ Technologies Used

- Python
- Tkinter
- Ollama
- PyInstaller

---

# 📦 Installation

## 1. Install Python

Download Python:

https://www.python.org/downloads/

Make sure to enable:

```text
Add Python to PATH
```

during installation.

---

## 2. Install Ollama

Download Ollama:

https://ollama.com

---

## 3. Download an AI Model

Open CMD or PowerShell:

```bash
ollama pull llama3
```

Recommended math models:

```bash
ollama pull deepseek-r1:8b
```

or

```bash
ollama pull qwen2.5:7b
```

---

## 4. Install Python Dependencies

```bash
pip install ollama
```

---

# 🚀 Running the App

Start Ollama first.

Then run:

```bash
python math_ai_gui.py
```

or

```bash
py math_ai_gui.py
```

---

# 🖥️ Building the EXE

Install PyInstaller:

```bash
py -m pip install pyinstaller
```

Build the application:

```bash
py -m PyInstaller --onefile --windowed math_ai_gui.py
```

Your executable will appear in:

```text
dist/
```

---

# 🎨 Adding an App Icon

Place an `.ico` file in the project folder:

```bash
py -m PyInstaller --onefile --windowed --icon=icon.ico math_ai_gui.py
```

---

# ⚙️ Recommended Model

Inside the Python script:

```python
MODEL_NAME = "llama3"
```

For stronger math reasoning:

```python
MODEL_NAME = "deepseek-r1:8b"
```

---

# 🧪 Example Questions

```text
Solve x^2 + 5x + 6 = 0
```

```text
What is the derivative of x^3 + 2x?
```

```text
A train travels 60 mph for 3 hours...
```

```text
Find the area of a triangle with base 10 and height 5
```

---

# 📂 Project Structure

```text
Math-AI-Assistant/
│
├── math_ai_gui.py
├── README.md
├── requirements.txt
├── icon.ico
└── dist/
```

---

# ❗ Troubleshooting

## Ollama Not Found

Make sure Ollama is:
- Installed
- Running
- Added to PATH

Test with:

```bash
ollama list
```

---

## Model Missing

Pull the model again:

```bash
ollama pull llama3
```

---

## EXE Closes Immediately

Run the Python version first:

```bash
python math_ai_gui.py
```

to view any errors.

---

# 📈 Future Improvements

Planned features:
- Chat history
- Voice input
- OCR math solving from images
- LaTeX rendering
- Better UI themes
- Multi-model support
- GPU acceleration

---

# 🤝 Contributing

Pull requests are welcome.

Feel free to fork the project and improve it.

---

# 📜 License

This project is free to use and modify.

---

# ⭐ Support

If you like this project, consider giving it a star on GitHub.
