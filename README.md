![subdora logo](https://raw.githubusercontent.com/Lakshit-Karsoliya/Subdora/main/assets/subdora.png "subdora logo")

<h1>Subdora 0.2.0</h1>
<p style="color:red;font-size:12px;">***This version of subdora is not backward compatiable, it is recommended to use the latest verison of subdora </p>

<p>This is the fourth release of subdora. Subdora is an obfuscation tool which makes source code very hard to interprate</p>

<h2>Installation</h2>

```
pip install Subdora
```

<!-- <h2>Supported OS</h2> -->

<!-- | Version | Arm   | Linux(64) | Windows(64) |
|:-------:|:-----:|:---------:|:-----------:|
| 0.2.0   | ❌    | ✔️         | ✔️        |
| 0.1.0   | ❌    | ✔️         | ✔️        |
| 0.0.2   | ❌    | ✔️         | ✔️        |
| 0.0.1   | ❌    | ✔️         | ✔️        | -->




<h2>What's new in v0.2.0</h2>

* able to obfuscate python script into images while retaning ineration counter and expiry time 
* Add support for cli tool 
* Add expiry time feature

<h2>How to use</h2>
<h3>Core functionality</h3>

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

<code>C:> subdora --run main.img</code>

<h3>


<h3>Features</h3>

* Obfuscation of python code
* obfuscation of python code into image files
* Support Code expiry Feature
* Support iteration counter
* Support for cli tool
* Supports loading obfuscated code as module in another python projects

  
