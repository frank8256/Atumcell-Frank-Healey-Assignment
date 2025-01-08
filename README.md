# Atumcell-Frank-Healey-Assignment

Each CVE has their own directory 

Each directory has a set of snort rules and a corresponding traffic pcapng for those rules to be ran on 

In each CVE# directory, the following command can be used to analyze the traffic with the cooresponding Snort3 rules:

snort -r traffic.pcapng -c snort/snort.lua -q -A full
