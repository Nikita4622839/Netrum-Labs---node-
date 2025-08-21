⚡ Netrum Lite Node CLI
📌 What is Netrum Lite Node CLI?

Netrum Lite Node CLI is a lightweight command-line utility that allows anyone to join the Netrum decentralized compute network.

It lets you securely:

Create and manage wallets

Connect to the Netrum server

Register your node on-chain

Sync uptime data

Mine NPT tokens

Claim daily rewards

All actions are done directly from your terminal 🚀

Perfect for VPS and low-resource devices, this node offers fast setup, transparency, and passive token earnings.

## ⚙️ Hardware & Network Requirements

### Hardware
| Component   | Minimum  | Recommended |
|-------------|----------|-------------|
| **CPU**     | 2 Cores  | 2+ Cores    |
| **RAM**     | 4 GB     | 6 GB+       |
| **Disk**    | 50 GB SSD| 100 GB SSD  |

> 💡 SSD storage is **highly recommended** for stability and faster sync.

### Network
| Type        | Minimum Speed |
|-------------|---------------|
| **Download**| 10 Mbps       |
| **Upload**  | 10 Mbps       |

Stable internet is required for **uptime sync, mining, and claiming rewards**.









# 1. Clone the repository
 ```
git clone https://github.com/Nikita4622839/Netrum-Labs---node-.git
 ```

# 2. Enter the project directory
 ```
cd Netrum-Labs---node-
 ```

# 3. Install required packages
 ```
sudo apt update && sudo apt install -y curl bc jq speedtest-cli nodejs npm
 ```

# 4. (Optional) Install Node.js v20
 ```
node -v   # check current version
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install -y nodejs
 ```

# 5. Install project dependencies
 ```
npm install
 ```

# 6. Link the CLI globally
 ```
npm link
 ```

# 7. Test your installation
 ```
netrum
 ```
| Command                 | Description                  |
| ----------------------- | ---------------------------- |
| `netrum-update`         | Update CLI                   |
| `netrum-system`         | System status & logs         |
| `netrum-new-wallet`     | Create a new wallet          |
| `netrum-import-wallet`  | Import existing wallet       |
| `netrum-wallet`         | Inspect wallet & balance     |
| `netrum-wallet-key`     | Export private key           |
| `netrum-wallet-remove`  | Delete wallet files          |
| `netrum-check-basename` | Check Base domain conflicts  |
| `netrum-node-id`        | Show current Node ID         |
| `netrum-node-id-remove` | Clear Node ID                |
| `netrum-node-sign`      | Sign a message with node key |
| `netrum-node-register`  | Register node on-chain       |
| `netrum-sync`           | Start node sync              |
| `netrum-sync-log`       | View sync logs               |
| `netrum-mining`         | Start mining                 |
| `netrum-mining-log`     | View mining logs             |
| `netrum-claim`          | Claim rewards                |

✅ Conclusion / Quick Troubleshooting Guide

Update code: git pull → npm install → restart node.

Sync: wait for successful netrum-sync-log.

Wallet: register wallet before mining.

Gas/ETH: have ETH in reserve for fee (~5–10$).

Mining: start only after successful sync and registration.

Timers: keep intervals between attempts (netrum-claim every 24 hours).

API errors: sometimes server is unavailable, need to wait and try later.

