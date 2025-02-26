+++
disableToc = false
title = "Easy Setup Demo"
weight = 2
+++

This is for `Linux`, `Mac OS`, or `Windows` Hosts. - [Docker Desktop](https://docs.docker.com/engine/install/), [Python 3.11](https://www.python.org/downloads/release/python-3110/), [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

Linux Hosts:

There is a Full_Auto installer for some types of Linuxs, feel free to use them but please note, they may not fully work so please use the links at the top if you need to install something.

```bash
git clone https://github.com/lunamidori5/localai-lunademo.git

cd localai-lunademo

#Pick your type of linux for the Full Autos, if you already have python, docker, and docker-compose installed skip this chmod. But make sure you chmod the setup_linux file.

chmod 777 Full_Auto_setup_Debian.sh or chmod 777 Full_Auto_setup_Ubutnu.sh

chmod 777 Setup_Linux.sh

./(the setupfile you wish to run)
```

Windows Hosts:

```batch
REM Make sure you have git, docker-desktop, and python 3.11 installed

git clone https://github.com/lunamidori5/localai-lunademo.git

cd localai-lunademo

call Setup.bat
```

MacOS Hosts: 

{{% notice Note %}}
- I need some help working on a MacOS Setup file, if you are willing to help out, please contact Luna Midori on [discord](https://discord.com/channels/1096914990004457512/1099364883755171890/1147591145057157200) or put in a PR on [Luna Midori's github](https://github.com/lunamidori5/localai-lunademo).
{{% /notice %}}

Video How Tos 

- Ubuntu - ``COMING SOON``
- Debian - ``COMING SOON``
- Windows - ``COMING SOON``
- MacOS - ``PLANED - NEED HELP``

Enjoy localai! (If you need help contact Luna Midori on [Discord](https://discord.com/channels/1096914990004457512/1099364883755171890/1147591145057157200))

{{% notice Issues %}}
- `Git Bash` on Windows is not working.
- Running over `SSH` or other remote cmd may bug out, load slowly, or crash.
- There seems to be a bug with docker-compose not running. (Main.py workaround added)
{{% /notice %}}
