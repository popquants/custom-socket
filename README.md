# custom-socket
Python custom socket with MT5

1st, setup your MetaTrader5 Terminal:
go to 

'Tools' > 

'Options' > 

'Expert Advisor' tab

Tick 'Allow WebRequest for listed URL:'

add your Localhost
    
![mt5_setting](https://github.com/popquants/custom-socket/assets/25944798/09df8df6-ec0f-4e29-9e91-d8ecbcc3b9c9)

2nd, Deploy 'socket_client.mq5' on Meta Editor

3rd, Run 'socket_server.py'

4th, Drag 'socket_client' EA to the chart you need to get the prices.

5th, The result will appear in Python terminal.

![socket_example](https://github.com/popquants/custom-socket/assets/25944798/a6243956-6834-4c2a-a1c7-30fa87783726)

Thank you.
