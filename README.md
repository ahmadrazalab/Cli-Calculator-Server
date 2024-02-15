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
