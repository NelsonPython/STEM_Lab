<h1>Configuring your Public Radio</h1>

Public radio runs on an Oracle VirtualBox loaded with the Ubuntu 18.04 operating system and the Python 3.x programming language with Pandas, Numpy, Matplotlib, Folium, and Google text-to-speech modules installed.

<h3>Installing Oracle VirtualBox</h3>

<a href="https://www.virtualbox.org/">Download and install Oracle VirtualBox</a>.  

<a href="https://www.virtualbox.org/manual/ch04.html#guestadd-intro">Download and install VirtualBox Guest Additions</a>

<h3>Installing Ubuntu 18.04</h3>

<a href="http://releases.ubuntu.com/18.04.4/?_ga=2.216561171.445070319.1590454515-1663201285.1590454515">Download the ISO</a>

Use this ISO to configure your VirtualBox

<h3>Verifying Python and PIP</h3>

Verify that Python3 has been pre-installed:

```
python3 --version
$ Python 3.7.3
```

Verify the pip points to python3
```
pip --version
$  pip 18.1 from /usr/lib/python3/dist-packages/pip (python 3.7)
```


<h3>Installing Pandas</h3>

<a href="https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html">use the pip install</a>

```
pip3 install pandas
```

<h3>Installing Matplotlib</h3>

<a href="https://matplotlib.org/3.1.1/users/installing.html">use the pip install</a>

``` 
python -m pip install -U matplotlib  
```

<h3>Installing Folium</h3>

<a href="https://pypi.org/project/folium/">use the pip install</a>

```
 pip install folium
```

<h3>Installing Google TTS</h3>

<a href="https://pypi.org/project/gTTS/">use the pip install</a>

```
 pip install gTTS
 ```
 
 
