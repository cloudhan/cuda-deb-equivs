# Memorandum

```sh
sudo apt install equivs
```

```sh
for f in `ls *11-5`; do equivs-build $f > /dev/null ; done
sudo dpkg -i *.deb
rm *.deb
```

```sh
# Normal Ubuntu
sudo apt intall cuda-11-5
# WSL2 Ubuntu
sudo apt install cuda-toolkit-11-5
```
