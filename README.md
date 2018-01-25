# QIWIWallet.py
# pyQiwi Python QIWI API Wrapper

## Install pip install -U qiwipy

## Using `python import qiwi`

## Quick Tutorial

#### Get the current balance `python wallet = qiwi.Wallet (token = '', number = '79001234567') balance = wallet.balance ()`

#### Sending payment `python wallet = qiwi.Wallet (token = '', number = '79120004567') payment = wallet.send (id = 99, recipient = '79001234567', amount = 1.11, comment = 'Hello! ') `

#### Receive a commission for the payment of `python wallet = qiwi.Wallet (token = '', number = '79120004567') comission = wallet.commission (pid = 99, recipient = '79001234567', amount = 1.11)`

