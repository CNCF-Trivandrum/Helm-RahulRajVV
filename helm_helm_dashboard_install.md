# Helm & Helm Dashboard installation commands

[RAHUL RAJ V V]

## Installing Helm in Windows

- Download the latest version of helm for windowsamd64
- Unzip the downloaded file and navigate to the extracted folder
- Copy helm.exe from the extracted folder
- Create a new folder in C drive: c:\helm
- Paste the copied helm.exe to c:\helm directory
- Go to System properties--> Environment properties --> Edit "path" variable in system variable list. Add "c:\helm" path.
- try entering helm command from command prompt 

## Installing Helm in Linux

```sh
$ curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3
$ chmod 700 get_helm.sh
$ ./get_helm.sh
```

## Helm dashboard Installation

- Download the package from below URL
```sh
https://github.com/komodorio/helm-dashboard/releases
```
- Run the below command to install the helm dashboard plugin

```sh
helm plugin install https://github.com/komodorio/helm-dashboard.git
```

- After installing start helm dashboard by below command

```sh
helm dashboard
```
** STAY TUNED FOR MORE UPDATES **

