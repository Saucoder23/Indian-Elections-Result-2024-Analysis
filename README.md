# Indian-Elections-Result-2024-Analysis

### "Database Tables Used" ###
constituencywise_results: Stores constituency-wise winning candidate, total votes, and margin information.

partywise_results: Stores party-wise results, number of seats won, and alliance classification.

statewise_results: Maps constituencies to states.

states: List of states with their respective IDs.

constituencywise_details: Candidate-wise detailed voting (EVM and postal votes)

 ### "Key Analyses Performed" ###
Total Seats:
Calculates the total number of parliamentary seats across the country.

State-wise Seat Distribution:
Displays the number of seats available for elections in each state.

Alliance Performance:

Total seats won by NDA alliance.

Total seats won by I.N.D.I.A. alliance.

Seats won by each party within the alliances.

Alliance Classification:
Updated the partywise_results table to add a party_alliance field identifying whether a party belongs to NDA, I.N.D.I.A, or OTHER.

Most Successful Alliance:
Identified which alliance won the most seats nationwide.

Candidate-Level Insights:

Winning candidate's name, party, total votes, and margin for specific constituencies.

EVM vs Postal vote distribution for candidates in a constituency.

Candidates with the highest number of EVM votes.

State-wise Party Success:

Number of seats won by each party in a given state.

Seats won by each alliance (NDA, I.N.D.I.A., OTHER) in each state.

Top Performers and Runner-ups:

Identified the winner and runner-up candidates for each constituency within a state.

State-Level Election Summary: For Maharashtra, calculated:

Total seats

Total candidates

Total parties

Total votes (EVM + Postal)

Breakdown of EVM and postal votes.

#### Technologies Used ####
SQL (Structured Query Language)

Microsoft SQL Server
