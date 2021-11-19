# How to use dxFeed on Web3

> [Airnode](https://api3.org/airnode) API Documentation

{{ Give an overview of the API. Describe what it does. }}

**Home Page:** {{ URL to API home page }}  
**Web2 Docs:** {{ URL to API documentation }}

## Call this Airnode API

Read the [Airnode developer documentation](https://docs.api3.org/d/call-an-airnode) to learn how to call Airnode APIs. You'll need the **Provider ID** to call any endpoint in this API.

**Provider ID:** 0x155b746ad948bdbbaa6ae4279ae4c024403984ddf364499409697b66c42b826c

**Provider XPub:** xpub661MyMwAqRbcGzrtNwcaVrnV7zq4hspzs4mfTFRX5Cs8EVQE3ZWRviW3eCttSDArVoVRswVAThxWr2ycKPbRf1S8TfthfrtDTFf4geCseAf

[Reserved Parameters](https://docs.api3.org/r/reserved-parameters) are used to control Airnode behavior and are available for all endpoints.

## Available on Networks:

> Find more information on each chain [Here](https://ethereum.org/en/developers/docs/networks/).

| Chain   | Airnode RRP Contract                       |
| ------- | ------------------------------------------ |
| Rinkeby | 0xF9C39ec11055508BddA0Bc2a0234aBbbC09a3DeC |
| RSK     | 0x1190a5e1f2afe4c8128fd820a7ac85a95a9e6e3e |

# Endpoints

1. [GET /events.json](#0x4903a994f440e0bf4c4389832e18f7cff6ead57195b5f50a4cab92369b4621f4)

---

## GET /events.json <a name="0x4903a994f440e0bf4c4389832e18f7cff6ead57195b5f50a4cab92369b4621f4"></a>

{{ Describe the endpoint. Explain what it does and, if possible, deep link to the Web2 documentation. }}

**Web2 Docs:** {{ URL to endpoint documentation }}

You'll need the **Endpoint ID** to call this endpoint.

**Endpoint ID:** 0x4903a994f440e0bf4c4389832e18f7cff6ead57195b5f50a4cab92369b4621f4

[Request Parameters](https://docs.api3.org/pre-alpha/protocols/request-response/request.html#request-parameters)

````solidity
event		// Parameter Description...
fromTime		// Parameter Description...
indent		// Parameter Description...
source		// Parameter Description...
symbol		// Parameter Description...
timeout		// Parameter Description...
toTime		// Parameter Description...
```[Fixed Parameters](https://docs.api3.org/pre-alpha/airnode/specifications/ois.html#_5-3-fixedoperationparameters)

```solidity
format = 'json';		// The format parameter is fixed to json
````

[Response](https://docs.api3.org/pre-alpha/airnode/specifications/reserved-parameters.html#path)

```json
{ Add example response json here }
```

---
