![subdora logo](assets/subdora.png "subdora logo")
[![PyPI](https://img.shields.io/badge/PyPI-Ready-blue.svg)](https://pypi.org/project/Subdora/) 

<h1>Subdora 0.0.2</h1>

<p>This is the second release of subdora. Subdora is an obfuscation tool which makes source code very hard to interprate</p>

<h2>Installation</h2>

```
pip install Subdora
```

<h2>Supported OS</h2>

| Version | Arm   | Linux(64) | Windows(64) |
|:-------:|:-----:|:---------:|:-----------:|
| 0.0.2   | ❌    | ✔️         | ✔️           |
| 0.0.1   | ❌    | ✔️         | ✔️           |


<h2>What's new in v0.0.2</h2>

* Add support to parse .myst files as modules
* Improve error handeling


<h2>How to use</h2>
<h3>Core functionality</h3>

<p>obfuscating main.py file </p>

```py
Subdora.subdora_encode_file("main.py")
```

<p>This will generate a main.myst file in order to execute myst file</p>

```py
Subdora.subdora_parse("main.myst")
```

<h3>Loading a .myst file as module</h3>

<p>.myst file can be loaded as module by setting load_as_module to true while parsing the myst file</p>

<h3>Additional features</h3>
<p>Subdora provide an iteration counter which ensures that .myst if parsing is done more than specified iterations Subdora automatically corrupt whole .myst file</p>

```py
Subdora.subdora_encode_file("main.py",no_of_iterations)
```


<h3>Features</h3>

* Obfuscation of python code
* Support iteration counter
* Supports loading obfuscated code as module in another python projects

  
