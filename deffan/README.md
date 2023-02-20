_________________________
### Prerequisite

- [NodeJS](https://nodejs.org/en/)
```shell
curl -fsSL https://deb.nodesource.com/setup_19.x | sudo -E bash - &&\
sudo apt-get install -y nodejs
```
- NPM
```shell
sudo apt install npm
```
- Note :
If it already exists, you can ignore the installation.
_________________________

### How to run

Change directory to directory deffan

```shell
cd ~/inery-testnet-faucet-tasks/deffan
```

##### Install dependencies

```shell
npm install
```

##### Run the script

```
npm run deffan
```

_________________________
#### Command to run TOKEN

##### For Create token
```
npm run create-token
```
##### For Issue token
```
npm run issue
```
##### For Transfer token
```
npm run transfer
```
##### For Retire token
```
npm run retire
```
_________________________

#### Command to run CRUD

##### For Create data
```
npm run write-data
```
##### For delete data
```
npm run delete-data
```
##### For update data
```
npm run update-data
```
##### For read data
```
npm run read-data
```
_________________________