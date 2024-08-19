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

# Download and Install Validator
### Run the following command:
```
curl -O https://raw.githubusercontent.com/shardeum/validator-dashboard/main/installer.sh && chmod +x installer.sh && ./installer.sh
```
### The terminal will ask questions about your setup settings.
### Enter y to setup the web based dashboard
### Set a password for dashboard access
### Imput your IP address (vps)
### Make sure your vps port 8080, 9001, 10001 is available
# Wait for the installation process to complete

# Open validator GUI
### Go to your web browser and go to:
```
https://YourIP:8080/
```

### Enter the password you set during the installation process.
<img width="1440" alt="Ekran Resmi 2023-02-02 19 12 16" src="https://docs.shardeum.org/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FloginPage.9d8b33aa.jpg&w=828&q=75">

### You should now see the “Overview” page for the Shardeum Validator Dashboard in your web browser:
<img width="1440" alt="Ekran Resmi 2023-02-02 19 13 12" src="https://docs.shardeum.org/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FoverviewBetanet.1ca6b780.jpg&w=828&q=75">

# Start validator
### Go to the “Maintenance” page, then click the “Start Node” button in the top left white box:
<img width="1440" alt="Ekran Resmi 2023-02-02 19 13 12" src="https://docs.shardeum.org/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FstartBetanet.27c91085.jpg&w=828&q=75">

### if that does not work, you can also try running the following command on cli:
```
$HOME/.shardeum/shell.sh
```

```
operator-cli start
```

# Monitor validator
### Go to “Performance” to see your node’s hardware performance here:
<img width="1440" alt="Ekran Resmi 2023-02-02 19 13 12" src="https://docs.shardeum.org/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FperformanceBetanet.2cfbaad5.jpg&w=828&q=75">

### For more details about your node status run the following inside the CLI:
```
operator-cli status
```

# Connect Wallet to Shardeum Testnet
### Connect to Shardeum Validator with your wallet by configuring the network Shardeum Atomium

# Get SHM from ITN Faucet
### Claim testnet tokens from Shardeum Discord SHM Faucet.
  
# Stake SHM to validator
## GUI
### After you start the validator, go to the “Settings” page. You will be asked to connect your wallet:
<img width="1440" alt="Ekran Resmi 2023-02-02 22 36 51" src="https://docs.shardeum.org/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FconnectWalletBetanet.91738aaf.jpg&w=828&q=75">
  
### After you connect your wallet, you should see the following:
<img width="1440" alt="Ekran Resmi 2023-02-02 22 36 51" src="https://docs.shardeum.org/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FconnectedWalletOptions.3344a2b6.jpg&w=828&q=75">
   
### When you click "Add Stake", you will see the following:
<img width="1440" alt="Ekran Resmi 2023-02-02 22 36 51" src="https://docs.shardeum.org/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FconnectedWalletAddStake.f4614c14.jpg&w=828&q=75">

# DONE

# Uninstall Validator
```
rm -rf .shardeum
```
