# ApplicationUpdateLog

Keep tracking the updates-v1.01

The official site and dashboard have been updated. 
We made some improvements and restrictions to achieve better user experience:

1. The name of API key is limited to 20 bytes.
2. The notification of expiring packages will not include 0 RU packages now.
3. The content of the advanced feature of the API key is restricted to limited options.
4. The free package can not be subscribed to auto-scaling.
5. Auto-scaling status is limited to “active” or “stop” now.
6. The chain name is verified when creating a new api key.
7. Wallet address is added to the sign message when login with web3 wallet.
8. PAYG package can not be puechased on one's own initiative now, can only be subscribed.
9. PAYG will give the exact number of RUs in the message.
10. The responding is simplified when calling some registration APIs to avoid sensitive information leak.
11. Rate limit on CF is set to a smaller number.
