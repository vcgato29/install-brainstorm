# Install Brainstorm

## Install

Simply clone the repo and run the install.sh script.

```bash
git clone https://github.com/penguinmenac3/install-brainstorm.git
cd install-brainstorm
./install.sh
```

## Install all Manual

Install the dependencies python-dev libhdf5-dev and libopenblas-dev.

```bash
sudo apt-get install python-dev libhdf5-dev libopenblas-dev
```

Install numpy brainstorm and pillow. Numpy and pillow are required to use images for an image recognition network.

```bash
sudo pip install numpy brainstorm pillow
```

## Testen mit MNIST

To test the installation a MNIST-project can be used.
The project can be installed automatically or manually.

Automatic:
```bash
./test.sh
```

Manual:
```bash
git clone https://github.com/pinae/MNIST-Brainstorm.git
cd MNIST-Brainstorm
python load_dataset.py
```
