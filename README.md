![subdora logo](https://raw.githubusercontent.com/Lakshit-Karsoliya/Subdora/main/assets/subdora.png "subdora logo")

[![PyPI - Downloads](https://img.shields.io/pypi/dm/subdora)](https://pypi.org/project/subdora/)

<div align="center">
  <em>A Powerful Library for Obfuscating Python Scripts</em>
</div>

# Subdora 0.2.2

**Subdora** is a Python obfuscation tool designed to transform your code into a highly secure, non-readable format. Built to protect source code from unauthorized inspection and tampering, it’s backward-compatible with version 0.2.1, making it a flexible solution for securing complex Python algorithms.

---

## 🌟 What Subdora Does

Subdora takes your readable Python code and obfuscates it, converting it into a format that’s extremely challenging to interpret or reverse-engineer. This added layer of protection deters casual and unauthorized access, keeping your intellectual property safe.

---

## 🚀 The Problem Subdora Solves

Python code, by nature, is easy to read and vulnerable to reverse-engineering, posing a risk for unauthorized usage. This library is designed to:
- Protect complex algorithms and proprietary code from casual inspection.
- Prevent unauthorized copying and tampering, securing the functionality and integrity of your codebase.

---

## 💡 Why Subdora Was Created

Existing obfuscation tools often fall short—many lack essential features, while others come at a high price. Subdora was created to provide a **comprehensive** and **affordable solution** for developers and businesses looking to protect their Python code with ease.


<hr>
<h2>Installation</h2>

```
pip install Subdora
```

<strong>Tested On</strong>
* Windows 10/11 
* Unbuntu >=22.04 
* Linux Mint 

<h2>What's new in v0.2.2</h2>

* Minor bug fixes and improve error handeling

<h2>Features</h2>

* obfuscate python scripts
* able to obfuscate python script into images while retaning ineration counter and expiry time 
* Add support for cli tool 
* Add expiry time feature

<h2>How to use</h2>

<p><b>obfuscating main.py file</b> </p>

<p>From command line</p>

<code>C:\>subdora --obfuscate main.py --itr 10 --time 10m</code>

<p>From python file </p>

```py
Subdora.subdora_encode_file("main.py",no_of_iterations,expiry_time)#'4m 4h etc'
```

<p><b>This will generate a main.myst file in order to execute myst file</b></p>

<p>From command line</p>

<code>C:\>subdora --run main.myst</code>

<p>From python file</p>

```py
Subdora.subdora_parse("main.myst")
```

<p><b>Encoding python script to image</b></p>
<p>*only supports png and jpg files</p>
<code>C:>subdora --obfuscate main.py --img img.jpg --itr 5 --time 5m</code>

<br><p>This will generate main.png file to run the image file use</p>

<code>C:> subdora --run main.png</code>

<h3>


<h3>Features</h3>

* Obfuscation of python code
* obfuscation of python code into image files
* Support Code expiry Feature
* Support iteration counter
* Support for cli tool
* Supports loading obfuscated code as module in another python projects

<hr>

<i>
<p>Despite various obfuscation techniques, they can ultimately be reversed because all code eventually compiles down to assembly language. As a result, someone with intermediate cybersecurity skills can analyze and understand the code's execution process. This library primarily makes the code harder to comprehend for typical users. I always prefer security over obfuscation. I created this library because someone wheo needed to hide the logic for advanced technologies like traveling faster than light using Alcuberic drive , Quantum Entanglement Communicator (QEC), Hyperdimensional Stabilizer, Singularity Engine, Antimatter Fusion Reactor, Temporal Displacement Field (TDF), Dimensional Rift Generator, Graviton Manipulator. Existing libraries obfuscate scripts but come with many limitations, we can overcome those limitations with some financial investment. So I decided to develop this library. I don’t know how many people are using it or if it’s having any impact, but regardless, best of luck from my side.</p>
</i><br>
  <p>Made with <span style="color: red;">&#10084;</span> by Lakshit</p>



