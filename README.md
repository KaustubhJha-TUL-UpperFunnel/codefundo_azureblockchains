# codefundo_azureblockchains
codefundo.io 2019 azure blockchains project

My idea is to create a unified secure and fast voting system using azure block chains. Every node(voter) has an Aadhar card number , which will be used To access the ledger(that keeps the track of votes)
After gaining access to the ledger you can cast your vote,this process involves States that goes into azure block chains.
Taking a successful casting or transaction your details are locked into the ledger.
The rules of the following voting for high security can be defined in the json file later on during development.
If at some point you commit some error the status can be updated in as  INCORRECT/FLASE/REJECTED.
For a fair system to ensure proper exectution and security he/she is alloted a time limit of max 5 minutes.Any error during that period will allow you to start the process again.This ensures credibiltiy and flexibility.
Whatever the results of your casted votes(success,failed or timeout) will be stored onto the ledger and will lock you out of the system such that you can't enter your vote again.
STAGES OF THE VOTING , 1.)Person verfication 2.)Biometric scan , 3.) aadhar scan ,  4.)Vote Casting , 5.)TIMEOUT
To make sure that voting is fast we can make divide the ledger into parts alloted to each district , that can be updated in real time.
