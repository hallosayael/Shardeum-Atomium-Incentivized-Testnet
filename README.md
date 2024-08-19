# Shardeum-Atomium-Incentivized-Testnet

![image](https://shardeum.nyc3.cdn.digitaloceanspaces.com/shardeum/2024/06/ShArcade-Launch-4.png)

## System requirements:
VALIDATOR TIPE | CPU     | RAM      | SSD     |
| ------------- | ------------- | ------------- | -------- |
| Testnet | 2-4          | 4-16         | 250  |

  

## Important links for Shardeum:
- <a href="https://shardeum.org" target="_blank">Website</a>
- <a href="https://explorer-atomium.shardeum.org/" target="_blank">Explorer</a>
- <a href="https://twitter.com/shardeum" target="_blank">Twitter</a>
- <a href="https://discord.gg/shardeum" target="_blank">Discord</a>



# Install package managers

```
sudo apt update && sudo apt upgrade -y
```

```
sudo apt-get install curl
```

# Update package managers

```
sudo apt update
```

# Install docker and docker.io

```
sudo apt install docker-ce docker-ce-cli containerd.io docker-compose-plugin -y
```

```
sudo systemctl status docker
```

# Check that docker is working with (should return version 20.10.12 or higher):

```
docker --version
```

# Install docker-compose

```
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
```

### Setup permissions for docker-compose:
```
sudo chmod +x /usr/local/bin/docker-compose
```

### Check that docker-compose is working with (should return version 1.29.2 or higher):
```
docker-compose --version
```


## In order, say `y`, set a password, enter `8080` when it asks for port, press Enter directly when it asks for base directory so that it saves to `.shardeum`.

<img width="1440" alt="Ekran Resmi 2023-02-02 19 12 16" src="https://user-images.githubusercontent.com/101462877/216379061-943482d3-1f8e-4d11-9241-8a39be09065b.png">
  
<img width="1440" alt="Ekran Resmi 2023-02-02 19 13 12" src="https://user-images.githubusercontent.com/101462877/216379370-a8568c65-85ca-477a-a8e1-2a4e3f2c424f.png">

![image](https://user-images.githubusercontent.com/101462877/216380082-8c616ccd-8f60-4ec4-9324-ff1097c20eba.png)

# After seeing an output like the image below, continue...

![image](https://user-images.githubusercontent.com/101462877/216381866-e840b39c-1e87-4403-a0d2-32289e206ad4.png)

```bash
$HOME/.shardeum/shell.sh
```

```bash
operator-cli gui start
```


# Open any browser on your computer.

## In the search bar, type https://YOUR_IP:8080. IF NOT SECURE, WE SAY ADVANCED, PROCEED TO THE SITE.

<img width="578" alt="Ekran Resmi 2023-02-02 19 27 01" src="https://user-images.githubusercontent.com/101462877/216383216-0c28fabd-ba14-41a5-b886-dd87f775911e.png">

  
 
## Enter the password we set above.

<img width="1440" alt="Ekran Resmi 2023-02-02 19 28 13" src="https://user-images.githubusercontent.com/101462877/216383365-30973dbc-43a5-48cb-a916-6c1a013d4aec.png">
  
 
## Go to `Maintenance` and click `start node`.
  
<img width="1440" alt="Ekran Resmi 2023-02-02 22 36 51" src="https://user-images.githubusercontent.com/101462877/216432476-13ee3ec7-9381-4bf2-acb1-09baa8d75ad6.png">

  
## Refresh and wait a while
  

<img width="1440" alt="Ekran Resmi 2023-02-02 22 36 51" src="https://user-images.githubusercontent.com/101462877/216432965-714c474d-a742-4032-b6ca-bea7972962e1.png">
  
  
## Get Faucet Here: <a href="https://chaindrop.org/?chainid=8082&token=0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee" target="_blank">Faucet</a> 
  
  ![image](https://user-images.githubusercontent.com/101462877/216433395-0940fe21-6806-4a62-8d71-8b42330341ff.png)


## Stake.
  
  <img width="1440" alt="Ekran Resmi 2023-02-02 22 43 18" src="https://user-images.githubusercontent.com/101462877/216433614-73f58204-608f-419e-9901-7eb80590a577.png">


 ## Go back to the terminal and enter the following command.

```bash
operator-cli start
```
  

# You can view the status with the following command.
  

```bash
pm2 list
```
  
  ![image](https://user-images.githubusercontent.com/101462877/216434539-6bcf7343-fcb3-423a-a7ee-d1cb8f1dde68.png)

# Thanks to: agus1224 !!!
