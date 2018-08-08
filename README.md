This is the [Regovar](https://regovar.org) apt repository.

You can enable it on your Debian 9 (Stretch), your Ubuntu 16.04 LTS (Xenial) or your Ubuntu 18.04 (Bionic) as follow:

```sh
curl -s https://arkanosis.net/jroquet.pub.asc | sudo apt-key add -
curl -s https://dl.denomme.fr/asdeno.pub.asc | sudo apt-key add -
echo "deb https://apt.regovar.org/ stable software" | sudo tee /etc/apt/sources.list.d/regovar.list
sudo apt update
```
