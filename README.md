# Trust Web3 Provider

```Status	Unconfirmed
Size in Bytes	378
Date/Time	20/02/2025 - 16:54:51 UTC
Included in block	884598
Confirmations	0
Total Input	1 BTC
Total Output	0.9998866 BTC
Fees	0.0001134 BTC
Fee per byte	3.0000000000000004e-7 BTC
Value when transacted	97,629.37 USD
 Inputs
Index	0
Address	0xdE8668bd378F05aA87C516289bcb04C299c5501A
Sigscript ASM	N/A
Sigscript HEX	N/A
 Outputs
Index	0
Address	bc1q0txcvmtd95g8fl9tr7x78khs8wd2ysaju33rcr
Sigscript ASM	0 7acd866d6d2d1074fcab1f8de3daf03b9aa243b2
Sigscript HEX	00147acd866d6d2d1074fcab1f8de3daf03b9aa243b2
 
Index	1
Address	0xdE8668bd378F05aA87C516289bcb04C299c5501A
Sigscript ASM	0 701a8d401c84fb13e6baf169d59684e17abd9fa216c8cc5b9fc63d622ff8c58d
Sigscript HEX	0020701a8d401c84fb13e6baf169d59684e17abd9fa216c8cc5b9fc63d622ff8c58d
                    ___           ___           ___
      ___          /  /\         /  /\         /  /\          ___
     /__/\        /  /::\       /  /:/        /  /::\        /__/\
     \  \:\      /  /:/\:\     /  /:/        /__/:/\:\       \  \:\
      \__\:\    /  /::\ \:\   /  /:/        _\_ \:\ \:\       \__\:\
      /  /::\  /__/:/\:\_\:\ /__/:/     /\ /__/\ \:\ \:\      /  /::\
     /  /:/\:\ \__\/~|::\/:/ \  \:\    /:/ \  \:\ \:\_\/     /  /:/\:\
    /  /:/__\/    |  |:|::/   \  \:\  /:/   \  \:\_\:\      /  /:/__\/
   /__/:/         |  |:|\/     \  \:\/:/     \  \:\/:/     /__/:/
   \__\/          |__|:|~       \  \::/       \  \::/      \__\/
                   \__\|         \__\/         \__\/

```

A modular TypeScript library designed to offer Web3 interfaces, enabling your
wallet to connect with decentralized applications.

```
 +----------------+            +------------------+           +---------------+
 |                |            |                  |           |               |
 |      dApps     |  <----->   |   web3 provider  |  <----->  |  your wallet  |
 |                |            |                  |           |               |
 +----------------+            +------------------+           +---------------+

```

## Supported chains

- Cosmos [Docs](/packages/cosmos/README.md)
- Solana - _Wallet Standard fully compatible_ [Docs](/packages/solana/README.md)
- Ethereum _EIP-1193_ [Docs](/packages/ethereum/README.md)

# Useful links

[Using the library](/docs/USAGE.md)

[Contributing](/docs/BUILD.md)

[Adding a new chain](/docs/NEW.md)
