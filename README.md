### Workshop
Transaction ID: at1krz99kfqajewflr6k2s997mf4qe93a0qjhk06w3sfpzpa4lq4uqs7wyag3
Transaction ID: at1hjfdsgr4l4m2evg6232640rp4xt26l77hc89y3qwz53a43tplsrsexl8kj
Transaction ID: at14jaxmc3l8znmcrfsyefp9tcyq7jrf36wv79d6vkwrfvagfzc8vgs698pcu

## Preview
![Screenshot_20240823-064854](https://github.com/user-attachments/assets/f5cf084a-ad25-4006-93d0-d43e9f490590)

## Description
# First Workshop
Command: leo run main 3u32 2u32 --network testnet
Where main = transition function name, `3u32 2u32` is the inputs and network is specified `testnet`
I deploy using demo.leo.app
`generated private key in my.env needs to be change to that of your Leo wallet private key` for it to be deployed without error

# Second Workshop
For the second workshop

1st Command : `leo run mint <type_aleo_address> <type_amount>u64`
Record were generated from simple token (build and src files) were copied to my token file in order for the deployment to be successful.
 `generated private key in my.env needs to be change to that of your Leo wallet private key` for it to be deployed without errors.
 
2nd command: `leo run transfer "<Token_Record>" <to_address> <amount>u64`
The generated record from the 1st command were input into the second command's first input and then address and amount.
`generated private key in my.env needs to be change to that of your Leo wallet private key` for it to be deployed without errors.

# Third Workshop
Command: `leo run combine_hash_owner_receiver <type_your_address> <type_friend_address>`
This has only 2 inputs where first input is owner address (self.caller) and second input is the  receiver address.
`generated private key in my.env needs to be change to that of your Leo wallet private key` for it to be deployed without errors.
