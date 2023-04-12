Solution no 1.

The event loop allows node to carry out non-blocking operations, despite the fact that javascript is single threaaded.It works as part of the node engine to handle the operations of call back functions. 

Solution no 2.

Timers phase: This phase executes callbacks that use timers.
pending: This phase executes i/o operation that were defferred to the next loop cycle.
prepare, idle: This phase runs internally.
Poll: This phase executes input/output callbacks.
Check or setImmediate phase: This phase executes any callbacks in set immediate timers from the poll.
Close or exit phase: This phase keeps running as far as there are timers or input/output callbacks. If there are none, the process ends.

Solution no 3

Some best practices in server side dev are;
Using Es6 async/await
Keep code small
Ensure code is readable
Practice modularisation of code.
Handle Errors

Solution no 4

The NPM is the node package manager and it's responsible for managing all the dependencies our program needs to run both production dependencies and development dependencies

You initialize a package by typing the command npm init or npm init -y in your command line interface.

Solution no 5

To run a script in the package.json file, you go to your package . json file and under the scripts object,
add the <key> and the terminal command you want to run as it's value.

In your terminal, type the command: npm run <key>


