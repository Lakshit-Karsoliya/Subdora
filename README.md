![subdora logo](https://raw.githubusercontent.com/Lakshit-Karsoliya/Subdora/main/assets/subdora.png "subdora logo")
<div align="center"><i>Library for obfuscating python scripts</i></div>
<h1>Subdora 0.2.1</h1>

<p>This is the fifth release of subdora. Subdora is an obfuscation tool which makes source code very hard to interprate</p>
<hr>
<h2>What Subdora Does?</h2>
<p>Subdora Transforms python code into non-redable format to deter casual inspection and adds a layer of protection.</p>

<h2>What problem subdora solves?</h2>
<p>Python code is often easy to read and reverse-engineer, making it vulnerable to unauthorized copying, and sometimes, complex algorithms are tampered with during casual inspection</p>

<h2>Why I made this library?</h2>
<p>I created this library because existing obfuscation tools are limited in functionality and often come with high costs. I wanted to provide a comprehensive and affordable solution for protecting Python code.</p>

<hr>
<h2>Installation</h2>

```
pip install Subdora
```

<strong>Tested On</strong>
* Windows 10/11 
* Unbuntu >=22.04 
* Linux Mint 

<h2>What's new in v0.2.1</h2>

* bug fixes for linux systems (server)

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



