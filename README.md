# Metacrafters_3
Eth proof-intermediate (Writing a smart contract to implement the require(), assert() and revert() statements)


# Description
In this project, we will be creating a smart contract that implements error-handling techniques in a solidity programming language. We have three techniques, namely require, assert and revert statements, to handle the errors. 

require()- used to validate certain conditions before the execution of a function and takes two parameters as input. The first parameter is the condition we want to validate, and the second parameter is the message to be displayed on the console if the condition goes wrong or doesn't satisfy it. The second parameter is optional, it works if we pass only one parameter.

assert()- it is also similar to require() function, but it takes only one parameter. If the condition fails, then the function execution is terminated with an error message. If the condition that is passed through the assert() function is true, the execution jumps to the next statement in the function.

revert()- it is used to point to an error and revert the current call. It causes the EVM(Ethereum virtual machine) to revert all the changes made to the state, and things return to the initial state or state before the function call was made. Another use of the revert() statement is that gas is conserved; once the revert() is committed, the leftover gas is returned to the user. If this statement is not present, the whole gas is wasted and cannot be saved. In this way, we will be using all three statements in the Error handling.

# Getting started

Installing

Copy the code and paste it into Remix- Ethereum IDE

Executing program

After completing the code, we will compile it by clicking on the myToken.sol icon in the Solidity compiler. After clicking on the icon, go to Deploy and run transactions. Under the deployed contracts, we can see the variables and the functions declared. After that, we can use the default address provided. Paste the address in the mint, add the value, and check the balance. Also, we can burn the token via the burn function. Add the address, and burn the token. Check the balance  We can work with the functions by applying different values. In this way, we can create a new token.

# Authors
BYLAPUDI DEEPAK VENKATA SWAMY NAIDU
@bdvsnaidu(https://github.com/bdvsnaidu)
