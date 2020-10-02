Mai's economy system is still young and in need for more ideas for proper economy implementation. 
Mai's Economy System is Server-based and does not reflect your earnings in another server. Transferring coins from server to server is also not possible at this moment (though there are also no plans to implement this kind of feature soon).

## Mai Economy currently Features

- [Earning Currency Points](#Earning) (No Name as of Yet)
- [Transferring Currency Points](#Transferring)
- [Betting](#Betting) (Earning in a whole new Level!)
- [Spending](#Spending) (No ways as of yet)

## Important Terms

- [Banking](#Banking)
- [Currency Overflow](#Overflow)
- [Wallet](#Wallet)
<br><br>

### Earning
Earning Currency from this bot isn't that hard, but the way to earn it isn't a lot either. The bot only have 4 ways to earn currencies, which are `beg`, [`bet`](#Betting), `find`, and `daily` (see [Currency Commands](https://github.com/maisans-maid/Mai/wiki/Commands#Economy)). 

|  Source  |  Cooldown  |    Value    |
|----------|------------|-------------|
`beg` | 1 - 3 hrs (Random) | 100 - 300 coins (Random) | 
`bet` | see [Betting](#Betting) | see [Betting](#Betting) | 
`find`| 1 - 3 hrs (Random) | 100 - 300 coins (Random) | 
`daily` | 24 hours (streak is lost within 48 hours) | 550 coins (Base) <br> + 50 coins per streak |

Before you are able to use these commands properly, you will have to need a [wallet](#Wallet). You will also need to have a [bank](#Banking) to prevent currency [overflow](#Overflow)

[Back to top](#mai-economy-currently-features)

<br><br><br><br>
### Transferring
You can transfer your currency around, from your wallet to bank (depositing), bank to wallet (withdrawing), and even bank to another bank (transferring).
- When you transfer currency from your wallet to the bank, you will need to pay for an additional 5% of the amount to be deposited (e.g. depositing 100 requires you to have 105 on your wallet).
- When you attempt to deposit all of your current balance, some will balance will actually remain in your wallet, but the remaining will be less than the minimum required amount.
- The minimum required amount to transfer from and to bank is 100. This is also true when transferring amount from bank to bank.
- The taxation is different from deposit/withdraw to transfer (Deposit and Withdraw has 5% fee, Transfer has twice the amount at 10%)
- Transferring requires both of the parties involved to have a bank account (Mai's banking system, not real bank account)
- You cannot withdraw an amount greater than what your wallet can hold (20000 coins atm, subject to change). If you attempt to do so, you'll receive an error stating that it can cause a currency [overflow](#Overflow) together with the maximum amount you can withdraw at the moment.
<br><br>
[Back to top](#mai-economy-currently-features)
<br><br><br><br>
### Betting
A not-so-reliable way of earning coins in the Mai Economy. The Betting system has 33.33% win rate and rewards can be as twice up to 10x the amount of the bet amount (e.g. betting 500 will give you at least 1000 up to 5000 coin). The bet result will arrive a minute after you made the bet, but the bet amount will be instantly subtracted from your wallet. You will also need a bank to start betting (Won amounts are automatically transferred to your bank without taxes). The minimum bet amount is 500, while the maximum bet amount is 5000.
<br><br>
[Back to top](#mai-economy-currently-features)
<br><br><br><br>
### Spending
As of the moment, there has been no way to spend money yet (Except betting and paying for transaction charges/tax). This article will be updated soon as the commands for Economy spending system has ben put in place. There are also no works as of the moment for Mai's Economy's spending system.
<br><br>
[Back to top](#mai-economy-currently-features)
<br><br><br><br>
### Banking
Because of the limitation of the wallet, you will eventually need a bank. If you don't have a bank yet, you can get one by using the [`bank`](https://github.com/maisans-maid/Mai/wiki/Commands#Economy) command (which costs 2,500 of your current coins). You will also need a bank to start betting because won bets are automatically transferred here. You will also need to deposit and withdraw your current coins from time to time (to prevent [overflow](#Overflow)). Also, transferring credits from user to user requires you to have a bank.
<br><br>
[Back to top](#mai-economy-currently-features)
<br><br><br><br>
### Overflow
A special feature this Economy system has is the Overflow. This is put in place to limit the wallet to it's decided maximum capacity (@ 20,000). What happens in an overflow event is that:
- Earnings when the overflow happens will be forever lost, they are not transferred to your bank. (e.g., if you have 19,500 in your wallet and received a daily reward of 1000, you'll only receive 500 of it. The other 500 will not be retrievable)
- If you have full amount of what the wallet can hold (20,000), you lose the ability to receive daily rewards, find, and beg credits.
- You will not lose coins when withdrawing amount when in overflow. You will simply receive an error message.
- Overflow is not cooldown based, meaning unless you free up your wallet, you will not be able to receive wallet-reliant services.
<br>

To prevent Wallet Overflow, free up your wallet by transferring some of your wallet credits to your [bank](#Banking)
<br><br>
[Back to top](#mai-economy-currently-features)
<br><br><br><br>
### Wallet
Wallet is your primary coin storage in Mai's economy system. After registering to the economy system, you'll receive a random amount from Mai to fill up your newly acquired wallet. This wallet can only hold 20,000 coins though, so you will need to have a bank. In case you earn more than what your wallet can hold, it will cause your credits to [overflow](#Overflow).
<br><br>
[Back to top](#mai-economy-currently-features)
<br><br><br><br>
### 🔗 [Go back to Home](https://github.com/maisans-maid/Mai/wiki)