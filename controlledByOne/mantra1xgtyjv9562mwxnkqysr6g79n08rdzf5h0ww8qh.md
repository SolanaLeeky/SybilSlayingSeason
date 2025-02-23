Between 12/4/2024, 1:32:15 PM and 12/4/2024, 1:48:51 PM, 
the wallet `mantra1xgtyjv9562mwxnkqysr6g79n08rdzf5h0ww8qh` received the token `ibc/6749D16BC09F419C090C330FC751FFF1C96143DB7A4D2FCAEC2F348A3E17618A` from 110 different addresses. 
All transactions were completed within 16 minutes, each using a uniform gas fee of 200,000 and occurring with an average delay of just 8.7 seconds per transaction. 
Please refer to the attached screenshots for further details.

![image](https://github.com/user-attachments/assets/58125a16-c6e6-4ac2-a273-f6f0310120c3)
![image](https://github.com/user-attachments/assets/50160060-4016-47fd-92e1-608c7f0703d8)

During this transaction process, the wallet `mantra1xgtyjv9562mwxnkqysr6g79n08rdzf5h0ww8qh` sent the IBC token to itself. This indicates that the controller likely loaded all wallet private keys into a bot. Subsequently, the same wallet sent the IBC token again with a consistent gas fee of 200,000, ensuring that each transaction was successfully confirmed on the blockchain.
![image](https://github.com/user-attachments/assets/3950119c-1629-4770-a82a-4a2492bbe26d)


Then he executed the same sequence of transactions across all 110 wallets.

First, each wallet received funds from Osmo. 
Next, they performed an ExecuteContract transaction with a gas fee of 456,381. 
Third, they sent an IBC token to `mantra1xgtyjv9562mwxnkqysr6g79n08rdzf5h0ww8qh` using a gas fee of 200,000. 
Fourth, an additional ExecuteContract transaction was executed with a gas fee of 422,826. 
Then, each wallet sent funds to new wallets with a gas fee of 200,000. This repeated process confirms a highly automated operation.

![image](https://github.com/user-attachments/assets/297d870e-65cc-4de5-b28e-c1cf628782a9)
![image](https://github.com/user-attachments/assets/c4e7397a-f8b2-428e-af9e-98ae469a6709)
![image](https://github.com/user-attachments/assets/7b619fdf-c582-4113-b072-53e542a3cb4c)
![image](https://github.com/user-attachments/assets/c4dd08c3-0883-41f7-ba05-783f7bfccc33)

Please review the file [mantra1xgtyjv9562mwxnkqysr6g79n08rdzf5h0ww8qh.json](./mantra1xgtyjv9562mwxnkqysr6g79n08rdzf5h0ww8qh.json) , which details the transaction routes for that wallet, and also check the accompanying [mantra1xgtyjv9562mwxnkqysr6g79n08rdzf5h0ww8qh.txt](./mantra1xgtyjv9562mwxnkqysr6g79n08rdzf5h0ww8qh.txt) file. The data should confirm that this wallet is part of a highly automated operation, consistently consolidating and routing funds with uniform gas fees.


