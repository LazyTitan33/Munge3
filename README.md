![munge](munge.png)
# Munge

<i>Updated print statements to work with python3.</i>

A dirty little python script to munge dictionary words into possible passwords.

Example usage:

./munge.py -l 9 -i dictionary.txt -o munged.txt

# Policy

Password policy enforcer to optimise dictionaries for cracking.

Example usage:

./policy.py -luns -i munged.txt -o optimised.txt
