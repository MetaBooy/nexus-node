## nexus node guide


# 📦 Step 1: System Update & Install curl
```
sudo apt update && sudo apt upgrade -y
sudo apt install curl -y
```
# step 2 : install screen 
```
sudo apt update
sudo apt install screen -y
```
# step 3 : create screen 
```
screen -S nexus-node
```


# ⚙️ Step 2: Install Nexus CLI
```
curl https://cli.nexus.xyz/ | sh
```

# 📂 Step 3: Add Nexus to Your PATH
```
source ~/.bashrc
```
# 🚀 Step 4: Start Your Node
First, get your Node ID:

Go to (https://nexus.xyz)

Connect your wallet

Visit your Nodes page: https://nexus.xyz/nodes

# step 5 Then run:
```
nexus-network start --node-id <your-node-id>
```


