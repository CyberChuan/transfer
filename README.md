#### split file
```shell
split -b 99M [file-name] [prefix-name]
# split -b 99M WebStorm-2025.1.3.exe webstorm_installer_
```

#### cat files
```shell
cat [file-names] > [file-name]
# cat webstorm_installer_a* > webstorm_installer.exe
```

#### files sha256 code
```text
vscode:   a7e37b9cf6d47beb4c564d167022ca324bfeb971944f21a9ce87e953e154a52b
webstorm: 060e697d95a0898f714ac5cbf054fe770fa33a8c1152047aa1bc2ff30f3ab21d
```