Blockhain Metacoin

Basic Installation:
1. Truffle
2. Ganache

How to open:
1. Make sure you open your ganache
2. Cd to your project
   ->Truffle migrate
3.Cd to your project
   ->Truffle console
   ->Check Balance:
         ->MetaCoin.deployed().then(function(instance){return instance.getBalance(accounts[0]);}).then(function(value){return value.toNumber()});   


https://docs.google.com/document/d/1HAvsP3ug-cyoeGz7nIuJjsZ8LJoLlDAucghGoCCwCFA/edit