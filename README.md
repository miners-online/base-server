# Miners Online - Base Server

Base Server is the shared modpack for all servers in the Miners Online network.

## What's included

- LuckPerms configuration
- Velocity proxy support using Fabric Proxy Lite
- Configuration for Patbox's styling suite
- The ViaVersion suite for cross-version support
- Modernised CrossStich from [PR #23](https://github.com/PaperMC/CrossStitch/pull/23) for Velocity to support Fabric commands

## Configuration placeholders

All configuration files in this repository use placeholders. If you use [itzg's docker-minecraft-server](https://github.com/itzg/docker-minecraft-server), you can set these placeholders using environment variables-if not, you would have to manually replace them in the configuration files.

- *LuckPerms*:
  - `CFG_LUCKPERMS_SERVER` - The server name to use for LuckPerms context
  - `CFG_LUCKPERMS_STORAGE_METHOD` - The storage method to use for LuckPerms (e.g., `H2`, `MySQL`, `MariaDB`, `PostgreSQL`, `MongoDB`, etc.)
  - `CFG_LUCKPERMS_DB_ADDRESS` - The address of the database to use
  - `CFG_LUCKPERMS_DB_NAME` - The name of the database to use
  - `CFG_LUCKPERMS_DB_USERNAME` - The username for the database
  - `CFG_LUCKPERMS_DB_PASSWORD` - The password for the database
  - `CFG_LUCKPERMS_REDIS_ENABLED` - Whether to enable Redis for LuckPerms
  - `CFG_LUCKPERMS_REDIS_ADDRESS` - The address of the Redis server
  - `CFG_LUCKPERMS_REDIS_USERNAME` - The username for the Redis server
  - `CFG_LUCKPERMS_REDIS_PASSWORD` - The password for the Redis server
- *Fabric Proxy Lite*:
  - `CFG_FABRICPROXY_SECRET` - The secret key for Fabric Proxy Lite

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
