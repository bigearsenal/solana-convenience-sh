# Convenience bash files for solana cli
## Set permission
```sh
chmod -R u+x .
```

## Install solana-cli and spl-token cli
- https://docs.solana.com/cli/install-solana-cli-tools
- https://spl.solana.com/token

## Set account
```sh
solana config get
```

```sh
vi /PATH/TO/PRIVATE/KEY.json
```

```sh
// Send all non-zero token to recipient, close zero-balance token, send all SOL to recipient
./send-all-and-close <RECIPIENT>
```

or
```sh
./send-all <RECIPIENT>
./close-all
./send-all-sol <RECIPIENT>
