title: Install Python38 on Ubuntu

## [What is Python](/what-is/python/)

---

[Python](https://www.python.org/) is a general-purpose coding language—which means that, unlike HTML, CSS, and JavaScript, it can be used for other types of programming and software development besides web development.

<br />

> Can be used for things like

- Back end (or server-side) web and mobile app development
- Desktop apps and software development
- Processing big data and performing mathematical computations
- Writing system scripts (creating instructions that tell a computer system to “do” something)

<br />

## [What is Ubuntu](/what-is/ubuntu/)

---

Ubuntu is a free and open-source Linux distribution based on Debian. Ubuntu is officially released in three editions: Desktop, Server, and Core for the internet of things devices and robots. All the editions can run on the computer alone, or in a virtual machine.

Ubuntu is a complete Linux operating system, freely available with both community and professional support - read more on [this link](/what-is/ubuntu/).

<br />

## Install Python3.8 on Ubuntu

---

```bash
$ sudo add-apt-repository ppa:deadsnakes/ppa
$ sudo apt-get update
$ sudo apt-get install python3.8
$ sudo apt-get install python3.8-venv
```

> Optionally, we can add the `disutils`

```bash
$ sudo apt install python3.8-distutils
```

> Test the creation of a Virtual Environment

```bash
$ python3.8 -m venv env
$
$ # Activate the VENV (Unix based systems)
$ source env/bin/activate
$
$ # Activate the VENV (Windows systems)
$ .\env\Scripts\activate
```

<br />

> In case of any issues, access the [support](https://appseed.us/support) page or talk with us on [Discord](https://discord.gg/fZC6hup).

<br />

## Links

- [Python 3 Installation & Setup Guide](https://realpython.com/installing-python/) - article published on RealPython
- [How to install Python](https://realpython.com/installing-python/) - a complete guide for many OS: Fedora, MacOS, Ubuntu
