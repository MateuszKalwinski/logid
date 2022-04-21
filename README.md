# logid
Logitech mx master 2s configuration

## Instruction

Open terminal

For Debial and Ubuntu

```sh
sudo apt install cmake libevdev-dev libudev-dev libconfig++-dev git
```
Clone repository

```sh
git clone https://github.com/PixlOne/logiops.git
```
Copy and Paste the following commands in terminal

```sh
cd logiops
mkdir build
cd build
cmake ..
make
```
Install

```sh
sudo make install
```

Start using

```sh
sudo systemctl start logid
```

Do if you want autostart logid

```sh
sudo systemctl enable logid
```
