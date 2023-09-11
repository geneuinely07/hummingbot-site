This is **part 2** of the Hummingbot Liquidity Mining Quickstart Guide:

1. [Create API Keys]
2. **Configure Hummingbot Miner**
3. [Install Hummingbot]
4. [Create Bot]
5. [Earn Rewards]

## Create a Hummingbot Miner account

Hummingbot Miner is a liquidity mining platform where you can run market making bots to earn liquidity rewards on various exchanges. In this step, you will add your read-only API key to Miner so that you can earn and monitor rewards for the orders placed by your bots.

> Users are free to download and run Hummingbot without signing up on the mining platform. The liquidity mining strategy in particular, however, is optimized for participating in Hummingbot Miner campaigns.

1. Navigate to [Hummingbot Miner](https://miners.hummingbot.io), and click on `Log in`
![](./2-a-log-in.png)

2. Select `Sign up`

3. Enter your email address, read and agree to the [Terms of Service](https://hummingbot.io/terms/), then click on `Create account`
![](./2-b-sign-up.png)

4. Check your email to confirm your account and you will need to enter the displayed security code 
![](<2-c-security code.png>)

5. On the Hummingbot Miner email, click on `Log in to Hummingbot Miner`

> After clicking on the link sent by email, a new tab will open for you to enter the security code
![](<2-d-enter code.png>)

6. You should now be logged into Hummingbot Miner with your new account.

![](2-e-logged-in.png)

7. Go to the Settings page, and add the read-only API to your account.

![](<2-f-connect api.png>)

Add the read-only API key, Secret key, and Passphrase generated in [step one][Create API Keys]

![](2-g-api.png)

> Please do not attempt to use the same API key on more than one Hummingbot miner account. Doing so will be seen as an attempt to cheat the system, since this could potentially cause users to be rewarded multiple times for the same orders, and will result in blacklisting.

Next, you'll need to [install hummingbot][Install Hummingbot]

[Create API Keys]: ../1-create-keys
[Configure Hummingbot Miner]: ../2-configure-miner
[Install Hummingbot]: ../3-install-hummingbot
[Create Bot]: ../4-create-bot
[Earn Rewards]: ../5-earn-rewards