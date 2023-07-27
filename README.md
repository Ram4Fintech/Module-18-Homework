# Module-18-Homework

I initiated the following steps as required in this assignments

# Imports
All necessary libraries were imported

## Step 1:
I created the new dataclass Record and added the attributes 'sender', 'receiver' and 'amount' with their respective data types

## Step 2:
I renamed the 'data' attribute to 'record' and set it to use the instance of 'Record'
I defined the hash block (self) and after encoding it for record, creater id and timestamp, ran the sha update on each of these respectively. Similar actions were done on previous hash and nonce.
Then I created the class pychain with difficulty = 4. I defined proof of work and arroived at the calculated hash as the 'Winninh Hash'. Thereafter I defined the adding blaock function follopwed by validation of the block hashes to establish the validity of the Blockchain

## Step 3:
I added the user inputs to the streanlit interface for the input atreas of 'sender', 'receiver' and 'amount' and also added the 'Add Block' button functionality
Undder the PyChain Ledger heading, I specified the Block Difficulkty levels at 1,5 and 2. Coding were done to view the required blaock and also validate the pychain with streamlit button

## Step 4:
I tested the Pychain ledger by running the streamlit application and storing some mined blocks in the Pychain ledger
I confirmed in the Terminal that the Blockchain was initiated and is valid and the winning has indicated
Please refer to this screenshot:
![Step 4 - Testing pychain ledger testing confirmation](https://github.com/Ram4Fintech/Module-18-Homework/assets/121836558/5a1ef260-39fe-4f29-9de6-c008f1315fb6)
![Step 4 - Testing pychain ledger testing confirmation part 2](https://github.com/Ram4Fintech/Module-18-Homework/assets/121836558/4aadb12e-9dc7-443e-a040-1f17e7cc2013)



I then created three different blocks with different difficulty levelsand  these were successful as per the images here:
![First successful attempt at creating block](https://github.com/Ram4Fintech/Module-18-Homework/assets/121836558/5090746a-1f2a-419c-895c-696cfb861bf4)
![Second successful attempt at creating block with difficulty 5](https://github.com/Ram4Fintech/Module-18-Homework/assets/121836558/41001091-ff63-43c8-844c-5c8ee924c85f)
![Third successful attempt at creating block with difficulty 1](https://github.com/Ram4Fintech/Module-18-Homework/assets/121836558/87b6085a-e70b-4704-898d-a8317616483a)

Finally, I tried different blocks with sender, receiver and amount different from the above and tested them on different levels of difficulties - 1, 2 and 5, validated all the results as True and the results are here, with 2 pages of screen shots for each difficulty:
![Final pychain block with difficulty 1 part 1](https://github.com/Ram4Fintech/Module-18-Homework/assets/121836558/7e716113-3e5f-4deb-8a62-4369b897c4b6)
![Final pychain block with difficulty 1 part 2](https://github.com/Ram4Fintech/Module-18-Homework/assets/121836558/54c466f4-939b-47cd-adf1-f82d1a634fa8)
![Final pychain block with difficulty 2 part 1](https://github.com/Ram4Fintech/Module-18-Homework/assets/121836558/65c5acd3-4fc5-459c-83ac-7751b8d22d91)
![Final pychain block with difficulty 2 part 2](https://github.com/Ram4Fintech/Module-18-Homework/assets/121836558/7369b805-b4d2-4eac-81cc-58df099899e2)
![Final pychain block with difficulty 5 part 1](https://github.com/Ram4Fintech/Module-18-Homework/assets/121836558/fe7bc200-2cd7-42b7-9406-ac826c47fb36)
![Final pychain block with difficulty 5 part 2](https://github.com/Ram4Fintech/Module-18-Homework/assets/121836558/4fdf9bc5-3661-4b7f-b041-75101a5c83fc)








