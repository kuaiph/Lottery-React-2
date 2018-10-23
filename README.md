# Lottery-React

# Function :

Lottery app that registers a manager, players, and funds to be contributed and won.
Built with MetaMask, the Rinkeby test network, Remix and Infura.
The smart contact logic resides in Lottery.sol (https://github.com/prateeksawhney97/Lottery-Smart-Contract-Ethereum) and this repository contains the front-end page built with create-react-app.

# How it works :

To take part in the lottery every user needs to send some amount of money(which cannot be less than 0.01 ETH for each user). After some people have entered the contract a "third-party"(manager of the contract) will tell the contract to pick a winner, beware that he does not pick the winner itself, the contract does that. After it picks the winner, the contract sends him the full price and resets; to continue for other players that want to play.

# Screenshots :

![screenshot from 2018-10-23 12-17-30](https://user-images.githubusercontent.com/34116562/47343758-7e8e7700-d6c4-11e8-8c8f-9a6b8d0e3f27.png)
![screenshot from 2018-10-23 12-20-24](https://user-images.githubusercontent.com/34116562/47343771-851cee80-d6c4-11e8-8483-ea2a236f04cf.png)
![screenshot from 2018-10-23 12-49-28](https://user-images.githubusercontent.com/34116562/47343823-8d752980-d6c4-11e8-9fbc-fdeff4034504.png)
![screenshot from 2018-10-23 12-49-34](https://user-images.githubusercontent.com/34116562/47343825-8f3eed00-d6c4-11e8-9fc4-a33ef76965f4.png)
