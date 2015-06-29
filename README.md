# Erlang-Calculator
An Erlang B and Erlang C calculator for queuing theory made with macros, VBA


Part 1:
It is desired to design an Erlang B calculator for the M/M/c/c "lost calls queuing model". The input parameters are the average arrival rate, packets/min, the average service rate packets/min and the probability of blocking, PB. The output parameter should be the number of servers required to satisfy the PB requirement. Remember that the number of servers has to be an integer. So if the answer from your “calculation is not an integer, you need to take the “next” higher integer.

Part 2:
It is desired to design an Erlang C calculator for the M/M/c "delayed calls queuing model". The input parameters are the average arrival rate, packets/min, the average service rate, packets/min. In addition, include input constraints on each of the following (separately and then collectively)
a) The probability that an arriving Packet will find all servers busy (i.e. P (W > 0)) should not exceed where is an input parameter
b) Given that an arriving packet must wait, the average waiting time should not exceed minutes where is an input parameter.
c) Less than % of all packets should have to wait more than minutes for a free server where and are input parameters
The output of your calculator should be the number of servers required to satisfy the above requirements/constraints. In addition, your calculator should enable me to find the following averages: The average number of busy servers and the average number of packets in the system (both waiting and being served).
