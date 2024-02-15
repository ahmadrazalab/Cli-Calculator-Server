# What is this and How to use ! 
This is just a simple calculator for server which is build in python language
To use it you need to install as per the below command
CMD :

```
calc 2+5
calc 2+6-8
```

## How to install 
```
wget https://github.com/ahmadrazalab/calc-server/releases/download/<version-no>/calc-arm.deb
sudo apt install calc-arm.deb or sudo dpkg -i calc-arm.deb)
```


## How to build 

>> Architectue 
```
calc-arm/
├── DEBIAN/
│   └── control
└── usr/
    └── bin/
        └── calculator.py
```

>> Build deb file

```
dpkg-deb --build calc-arm
```
