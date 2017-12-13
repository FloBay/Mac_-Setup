# Mac_-Setup
How to setup an Mac for programming

This includes the following steps:

## 1. Install Xcode:

### 1.1 Check whether Xcode is installed:

```bash
$ xcode-select -p

/Applications/Xcode.app/Contents/Developer
```

If xcode command is not kown, download and install Xcode.

### 1.2 Install Xcode Command Line Tools:

```bash
$ xcode-select --install
```

This opens and starts an automatic installment procedure. Wait until installation has been completed.

### 1.3 Agree to the licence (Xcode and Apple SDKs Agreement):

```bash
$ sudo xcodebuild -license

You have not agreed to the Xcode license agreements. You must agree to both license agreements below in order to use Xcode.
...
```

### 1.4 Verify that you’ve successfully installed Xcode Command Line Tools:

```bash
$ gcc --version

Apple LLVM version 9.0.0 (clang-900.0.39.2)
```

## 2. Install Anaconda:

### 2.1 Download and install Anaconda (64-bit version)

Link: https://www.anaconda.com/download

### 2.2 Verify that youe've successfully installed Anaconda 

```bash
$ conda --version

conda 4.3.30
```

### 2.3 Test that jupyter is running :

```bash
$ jupyter notebook
```

If it is nor running install jupyter with the following command:
```bash
$ conda install -c anaconda jupyter
```

### 2.4 Install R and R-packages

```bash
$ conda install -c r r-essentials
```

## 3. Download important Python libraries:

...
