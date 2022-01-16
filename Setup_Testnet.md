### Prerequisite ###
*  Open port 30311 (TCP) 

### To start a Toro Testnet node on Windows
*  Download "toro_testnet_windows.exe", "toro_test.json" into a folder
*  Init the blockchain node with
   ```
   > toro_testnet_windows.exe --datadir data init toro_test.json
   ```
*  Start the blockchain node with
   ```
   > toro_testnet_windows.exe --datadir data
   ```
*  Attach Javascript console with
   ```
   > toro_testnet_windows.exe attach ipc:\\.\pipe\geth.ipc
   ```

### To start a Toro Testnet node on MacOS
*  Download "toro_testnet_macos", "toro_test.json" into a folder
*  Make the binary executable
   ```
   > chmod +x toro_testnet_macos
   > chmod 755 toro_testnet_macos
   ```
*  Init the blockchain node with
   ```
   > ./toro_testnet_macos --datadir data init toro_test.json
   ```
*  Start the blockchain node with
   ```
   > ./toro_testnet_macos --datadir data
   ```
*  Attach Javascript console with
   ```
   > ./toro_testnet_macos attach ./data/geth.ipc
   ```

### To start a Toro Testnet node on Linux
*  Download "toro_testnet_linux", "toro_test.json" into a folder
*  Make the binary executable
   ```
   > chmod +x toro_testnet_linux
   > chmod 755 toro_testnet_linux
   ```
*  Init the blockchain node with
   ```
   > ./toro_testnet_linux --datadir data init toro_test.json
   ```
*  Start the blockchain node with
   ```
   > ./toro_testnet_linux --datadir data
   ```
*  Attach Javascript console with
   ```
   > ./toro_testnet_linux attach ./data/geth.ipc
   ```
*  If the dynamic binary (toro_testnet_linux) does not work, try the static version (toro_testnet_static_rhel or toro_testnet_static_ubuntu).
