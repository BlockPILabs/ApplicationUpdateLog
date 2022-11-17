# MigrationLog

After clearly checking the code between our Testnet and Alphanet, we want to inform you that the code has been fully migrated.   
To avoid unnecessary misunderstanding and work, we list the different details below. And some related bugs are gone after the migration. 
 

1. The name of API key is limited to 20 bytes.
2. The notification of expiring packages will not include 0 RU packages now.
3. The content of the advanced feature of the API key is restricted to limited options.
4. The free package can not be subscribed to auto-scaling.
5. Auto-scaling status is limited to “active” or “stop” now.
6. The chain name is verified when creating a new api key.
7. Wallet address is added to the sign message when login with web3 wallet.
8. PAYG package can not be purchased on one's initiative now. It can only be subscribed to.
9. PAYG will give the exact number of RUs in the message.
10. The response is simplified when calling some registration APIs to avoid sensitive information leaks.
11. Rate limit on CF is set to a smaller number.

For those who already submitted reports before the pause, the assessment will be based on the **old** code.  
After the bug bounty goes online again, submissions will be reviewed and assessed based on the **new** code.  
So you might want to **doublecheck** if the new code still has the bugs from the old code. 
We value all the hard work from Immunefi Whitehat community.   
Thank you!
