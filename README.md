Voting : The contract to be able to vote.
For this contract can have three types of users - Owner : can add votes and change the contract status - Voter : can add proposals and vote for a proposal - Public :can only see the winner


Functions

addProposal
voter register a proposal

Name	Type	Description
_desc	string	description of the proposal
Returns:

No parameters

addVoter
owner register a voter

Name	Type	Description
_addr	address	address of the voter
Returns:

No parameters

endProposalsRegistering
owner change status from ProposalsRegistrationStarted to ProposalsRegistrationEnded

No parameters

Returns:

No parameters

endVotingSession
owner change status from VotingSessionStarted to VotingSessionEnded

No parameters

Returns:

No parameters

getOneProposal
returns the proposal struct of this id

Name	Type	Description
_id	uint256	id of proposal
Returns:

Name	Type	Description
tuple	
getVoter
returns the voter struct of this address

Name	Type	Description
_addr	address	address of voter
Returns:

Name	Type	Description
tuple	
getWinner
returns the proposal struct who won

No parameters

Returns:

Name	Type	Description
tuple	
getWinners
returns the list of proposals struct who won

No parameters

Returns:

Name	Type	Description
tuple[]	
owner
Returns the address of the current owner.

No parameters

Returns:

Name	Type	Description
address	
proposalsArray
**Add Documentation for the method here**

Name	Type	Description
uint256	
Returns:

Name	Type	Description
description	string	
voteCount	uint256	
renounceOwnership
Leaves the contract without owner. It will not be possible to call `onlyOwner` functions anymore. Can only be called by the current owner. NOTE: Renouncing ownership will leave the contract without an owner, thereby removing any functionality that is only available to the owner.

No parameters

Returns:

No parameters

setVote
voter vote for a proposal

Name	Type	Description
_id	uint256	id of the proposal
Returns:

No parameters

startProposalsRegistering
owner change status from RegisteringVoters to ProposalsRegistrationStarted

No parameters

Returns:

No parameters

startVotingSession
owner change status from ProposalsRegistrationEnded to VotingSessionStarted

No parameters

Returns:

No parameters

tallyVotes
the owner tailly the votes

No parameters

Returns:

No parameters

tallyVotesDraw
the owner tailly the votes

No parameters

Returns:

No parameters

transferOwnership
Transfers ownership of the contract to a new account (`newOwner`). Can only be called by the current owner.

Name	Type	Description
newOwner	address	
Returns:

No parameters

workflowStatus
**Add Documentation for the method here**

No parameters

Returns:

Name	Type	Description
uint8	
