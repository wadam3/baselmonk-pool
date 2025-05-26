# baselmonk-pool

solo mining pool using Datum

## Usage

1. Copy the example configuration file and update it with your credentials:

   ```bash
   cp datum.config.json.example datum.config.json
   # edit datum.config.json and set your username, password and address
   ```

2. Run the setup script:

   ```bash
   ./setup_datum.sh
   ```

The script uses `datum.config.json` for configuration and performs the setup steps required to run the pool.
