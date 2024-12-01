# Repository: Erasmus-24

This repository contains introductory Python materials for Erasmus students from the IPEM class. The focus is on basic Python programming in conjunction with calculating Break-Even Points (BEP) and other indicators.

## How to Download and Set Up the Repository

### For macOS/Linux:
1. **Open a terminal** and navigate to the directory where you want to download the repository:
   ```bash
   cd /path/to/your/folder
   ```
2. **Clone the repository**:
   ```bash
   git clone https://github.com/andy111223/erasmus-24.git
   ```
3. **Enter the project directory**:
   ```bash
   cd erasmus-24
   ```

### For Windows:
1. **Open Command Prompt** (or PowerShell) and navigate to the directory where you want to download the repository:
   ```cmd
   cd C:\path\to\your\folder
   ```
2. **Clone the repository**:
   ```cmd
   git clone https://github.com/andy111223/erasmus-24.git
   ```
3. **Enter the project directory**:
   ```cmd
   cd erasmus-24
   ```

---

## Opening `.ipynb` Files in VS Code

### Set Up a Virtual Environment (if not set up yet):
1. **Ensure pip is upgraded**:
   ```bash
   python3 -m ensurepip --upgrade  # macOS/Linux
   python -m ensurepip --upgrade  # Windows
   ```
2. **Create a virtual environment**:
   ```bash
   python3 -m venv venv  # macOS/Linux
   python -m venv venv   # Windows
   ```
3. **Activate the virtual environment**:
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
   - On Windows:
     ```cmd
     .\venv\Scripts\activate
     ```
4. **Upgrade pip**:
   ```bash
   pip install --upgrade pip
   ```
5. **Install necessary packages**:
   ```bash
   pip install notebook ipykernel numpy plotly
   ```
6. **Register the kernel for Jupyter notebooks**:
   ```bash
   python -m ipykernel install --user --name=venv --display-name "Python (env)"
   ```

### Open the Notebook in VS Code:
1. Launch **Visual Studio Code** and open the `erasmus-24` folder.
2. Select the `.ipynb` file (e.g., `python-basics.ipynb`).
3. Make sure to select the kernel associated with the virtual environment:
   - Go to the **Kernel selector** in the top-right corner of the notebook interface.
   - Select "Python (env)."

---

## Importing `.ipynb` Files into Google Colab

### Steps:
1. Open [Google Colab](https://colab.research.google.com/).
2. In the Colab interface, go to **File > Open Notebook**.
3. Switch to the **GitHub** tab and paste the repository URL:  
   `https://github.com/andy111223/erasmus-24.git`
4. Select the desired `.ipynb` file and click **Open**.

### Editing in Google Colab:
- You can modify code cells by clicking on them.
- Run cells using:
  - `Shift + Enter` to run the cell and move to the next.
  - `Ctrl + Enter` to run the cell and stay in the same cell.

### Adding Dependencies in Google Colab:
To install dependencies (e.g., `numpy`, `plotly`), use the following command in a Colab code cell:
```python
!pip install numpy plotly
```

---

## What Are Git and GitHub?

Imagine you're writing a book with your friends, and you want to track all the changes anyone makes so that no one accidentally overwrites anyone else's work. **Git** is like a magical diary that remembers every single change you or your friends make. It keeps a history of everything, so if you make a mistake, you can undo it easily!

**GitHub** is a website where you can store this magical diary (your project's files and their history) online. This way, your friends (or even strangers!) can look at your work, suggest changes, or even contribute to your project.

### How to Install Git (Step by Step)

#### For macOS/Linux:
1. **Open Terminal** (this is a program that lets you type commands directly to your computer).
2. **Install Git**:
   - On macOS, type:
     ```bash
     brew install git
     ```
     (If `brew` isn’t installed, you can first install it by following the instructions at [brew.sh](https://brew.sh/).)
   - On Linux (Ubuntu), type:
     ```bash
     sudo apt update
     sudo apt install git
     ```
     You’ll be asked for your password—type it in and press Enter.
3. **Verify Installation**:
   Type the following to check if Git is installed:
   ```bash
   git --version
   ```
   You should see something like `git version 2.x.x`.

#### For Windows:
1. **Download Git**:
   Go to [git-scm.com](https://git-scm.com/) and click **Download for Windows**.
2. **Install Git**:
   - Double-click the downloaded file to start the installer.
   - Keep clicking "Next" and leave the options as default.
   - At the end, click "Finish."
3. **Verify Installation**:
   - Open **Command Prompt** (search for "cmd" in the Start Menu).
   - Type:
     ```cmd
     git --version
     ```
     You should see something like `git version 2.x.x`.

---

## What Is Google Colab?

Think of Google Colab as a magical notebook in the cloud. It's like an `.ipynb` file, but it lives on the internet and runs on Google's supercomputers instead of your own laptop. This means:

1. **No installation is needed**: You don’t need to set up Python, VS Code, or anything else—just open a browser and start coding!
2. **Runs on Google’s hardware**: If your laptop is slow, Colab can use Google's computers (with options like GPUs for faster calculations).
3. **Always available**: You can access it from any device with an internet connection.

### How Is Google Colab Different From `.ipynb` in VS Code?

| Feature                | `.ipynb` in VS Code                          | Google Colab                                |
|------------------------|----------------------------------------------|--------------------------------------------|
| **Where it runs**      | On your own computer (uses its resources).  | On Google’s servers (your computer just needs a browser). |
| **Setup required**     | You need to install Python, VS Code, and libraries. | No setup—just open it in your browser.     |
| **File location**      | Stored on your computer.                    | Stored in Google Drive or temporarily in the browser. |
| **Speed**              | Depends on your computer’s power.           | Uses Google’s powerful servers, faster for complex tasks. |
| **Offline use**        | Yes, works without internet.                | No, needs an internet connection.          |

In simple words, **VS Code is like cooking in your own kitchen** (you need to buy and set up everything yourself), and **Google Colab is like going to a restaurant** (everything is ready—you just need to start eating).

---

### Final Note
Remember: If you're using Google Colab, you can edit your notebook directly online, but if you’re working in VS Code, you have to set up Python and libraries yourself. Choose the one that suits your situation!