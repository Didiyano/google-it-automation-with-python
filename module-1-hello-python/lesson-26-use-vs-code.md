## 🐍 Module 1 – Lesson 26 Setting Up and Using VS Code

## 🌟 What This Lesson Covers

Now that you’ve explored different coding tools (Jupyter, Colab, etc.), it’s time to look more closely at VS Code — an open-source code editor filled with powerful developer features.

In this lesson, you’ll learn:

- What makes VS Code a great tool
- How to check if Python 3 is installed
- How to install VS Code
- How to install the Python extension
- How to create and run a Python file
- Why VS Code is so popular for Python development

---

## 💻 Why VS Code Is Useful

VS Code includes several built-in technologies that make coding easier:

- IntelliSense for smart code completion
- Interactive debugger
- Syntax highlighting
- Integrated terminal
- Extensions for extra features

It’s simple, intuitive, and works on Windows, macOS, and Linux.

---

✔️ **Step 1: Check if Python 3 Is Installed**

Open your terminal window and type:

python3 --version

If Python 3 is installed

You’ll see something like:

Python 3.10.12

**If Python is not installed**

You’ll see:

command not found


If so, you need to install Python 3.

✔️ **Step 2: Install Python 3 (Linux Example)**

In the terminal, type:

sudo apt install python3

Enter your password.

If prompted:

Do you want to continue?  [Y/n]

Choose yes.


Python 3 will now install and be ready to use.

✔️ **Step 3: Download & Install VS Code**

Go to the official VS Code download page:

👉 [code.visualstudio.com/download](https://code.visualstudio.com/download)

Choose the version for your operating system.
In the video example (Linux), they download the **.deb** package.

**Installing the .deb package (Linux example)**

1.  Go back to the terminal

2.  Navigate to your Downloads folder:

cd Downloads/


3.  List files:

ls


4.  Install VS Code using:

sudo dpkg -i <filename>.deb

VS Code is now installed.


✔️ **Step 4: Open VS Code**

In the terminal, type:

code

VS Code will launch.


✔️ **Step 5: Install the Python Extension**

Inside VS Code:

Press Ctrl + Shift + X to open the Extensions panel

Search for Python

Click Install

Once installed, VS Code will ask if you want to start Python development.


✔️ **Step 6: Create and Run Your First Python File**

Click Create Python File

A new Python workspace opens

Type:

print("Hello world")


Click the Run button

VS Code will prompt you to save your file

Name your file (example: helloworld.py) and click Save

Your output will appear in the integrated terminal:

Hello world


You’ve officially run your first script in VS Code!

---

## 🧠 Key Takeaways

- VS Code is a powerful and customizable editor
- IntelliSense helps with autocomplete and syntax highlighting
- You can debug directly inside VS Code
- There’s a huge library of extensions
- It supports full Python development with ease

---

## 🎉 You Did It!

That was a lot of setup, but you now know:

- How to install Python
- How to install VS Code
- How to create, run, and debug Python files