# Aliyun FC Not Found

This repository implements a simple HTTP server that can be deployed on Aliyun FC platform. The server will always returns a `404 Not Found` response for any request, which can be used to deprecate some interfaces of some deployed functions (e.g., disabling the websocket interface to reduce cost).

## Quick Start

If you want to use this repository, you should first fork the repository and set the access key of Aliyun in the environment variable settings of github action.

The following is an explanation of the environment variables in github action.

| Environment Variable Name |              Description              |
| :-----------------------: | :-----------------------------------: |
|   ALIYUN_ACCESS_KEY_ID    | The access key of your Aliyun account |
| ALIYUN_ACCESS_KEY_SECRET  | The secret key of your Aliyun account |
