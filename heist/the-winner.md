# 💰 The Winner

### Verifying The Winner

To circumvent any malicious attacks on the Polygon Network, once the countdown reaches zero, the winner is not paid out immediately. This is to allow us to verify that the winner has won legitimately and not used any methods to be the last deposit. Such as clogging up the network to stop other users making a deposit before the time has run out. Note that the winner’s wallet will not be subject to the criteria outlined in the [random drops](random-drops.md). Therefore, we will **NOT** be inspecting the winning wallet for any kind of suspicious activity such as a burner wallet. We will only be looking for any malpractice that has affected other users from winning. In the event that the winner has used some kind of attack to win, the contract will be called to reset the timer and the game will continue as normal.

### Manual Claim

In the unlikely event there are no devs around \(dead 💀\) to make a decision, a manual claim can be called from the winner which will start a timer of one week. If after the week has passed and there has still not been a decision made, the winner can manually claim their winnings without the need of a verification. This functionality was added as a last resort to ensure the winner will be paid out in adverse circumstances. Note that in this case the winner will only receive 50% of the pot and the other half will be burned. This is due to the fact that if this were to ever happen, then the final drop could not take place as no devs would be able to initiate the final drop. Therefore, you could say this is a way to say hey don't kill all the admins please 🤨.

### Pot Distribution

The winners pot will be allocated as follows:

| To | Allocation \[%\] |
| :--- | :--- |
| Winner | 70 |
| Final Drop | 20 |
| Dev | 10 |

Note these allocations are immutable on the blockchain and therefore cannot be changed or manipulated in any way \(excluding the manual claim function mentioned above\).

