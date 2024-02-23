# Explorer Registry

Data registry for https://zenode.app/explorer.

This has been written by ZENODE and is licensed under the APACHE 2.0-license (see [LICENSE](./LICENSE)).

> [!NOTE]
> The explorer on [https://zenode.app/explorer](https://zenode.app/explorer) lists the endpoints provided in this repository.

## PR Requests

If you wish to be included on the explorer, make a PR, editing the files:
- [/endpoints/namada-se/rpcs.json](/endpoints/namada-se/rpcs.json)
- [/endpoints/namada-se/apis.json](/endpoints/namada-se/apis.json) _(indexer)_
- [/profiles.json](/profiles.json) _(optional; for an avatar)_

> Currently, it's preferred to give an avatar coming from Keybase (images originating from the domain amazonaws.com), but might change this in the future to be less limited/restrictive.

## Supports

- Namada/Shielded Expedition
  - RPC (~currently only supports **http://** or **tcp://**~ v0.31.6 introduced support for **https://**!)
  - API/Indexer (**https://** supported)

## Credits

- Creating the endpoint registry was inspired by Gavin Birch (@gavinly from Knowable.vc). He pointed towards this being useful to have! A big shout out to him ❤️.

</br>

<p align="right">— ZEN</p>
<p align="right">Copyright (c) 2024 ZENODE</p>
