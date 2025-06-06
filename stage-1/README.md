# Function Scripts for DNA Translation, Logistic Growth and Hamming Distance Determination

## 📌 Task Overview
Here are four Python functions for various biological computations:

dna_to_protein: to translate DNA sequence into protein sequence.
generate_logistic_growth_curves: for generating multiple logistic growth curves with variations in lag and exponential phases.
time_to_80_percent_growth: to determines the time needed to reach 80% of the carrying capacity.
hamming_distance: for calculating the Hamming distance between pairs of usernames.

## Requirements
 - Python 3.x
## Function Descriptions
### 1. DNA to Protein Translation (dna_to_protein)
Purpose: Converts a DNA sequence into its corresponding protein sequence by first transcribing it into mRNA and then translating it using the standard genetic code.

Parameters:
dna_sequence (str): A string representing the DNA sequence.
Returns:
A string representing the translated protein sequence.
Key Features:
Replaces thymine (T) with uracil (U) to generate the mRNA sequence.
Reads the mRNA sequence in codon triplets.
Stops translation when encountering a stop codon.
Example Usage:
protein_sequence = dna_to_protein("ATGGCCATTGTAATGGGCCGCTGAAAGGGTGCCCGATAG")
print(protein_sequence)  # Returns translated protein sequence
### 2. Generating Logistic Growth Curves (generate_logistic_growth_curves)
Purpose: Simulates logistic population growth for multiple curves with varying lag phases and growth rates.

Parameters:
num_curves (int): Number of growth curves to generate (default: 100).
K (int): Carrying capacity (default: 1000).
P0 (int): Initial population size (default: 10).
E (float): Base of the natural logarithm (default: 2.71828).
max_time (int): Maximum time steps for simulation (default: 100).
Returns:
A list of dictionaries, each containing time points, population sizes, and the curve index.
Key Features:
Models population growth using the logistic growth equation.
Includes variations in lag phase and growth rate.
Useful for ecological and biological modeling.

Example Usage:
growth_curves = generate_logistic_growth_curves()
print(growth_curves[0])  # Displays first growth curve data

### 3. Time to 80% of Carrying Capacity (time_to_80_percent_growth)
Purpose: Computes the time required for a population to reach 80% of its carrying capacity based on logistic growth.

Parameters:
K (int): Carrying capacity.
P (int): Initial population size.
r (float): Growth rate.
dt (float): Time step increment (default: 0.01).
Returns:
A float representing the time required to reach 80% of carrying capacity.
Key Features:
Implements a numerical approach using small time steps.
Models logistic growth over time.  


Example Usage:
time_taken = time_to_80_percent_growth(K=1000, P=10, r=0.12)
print(time_taken)  # Returns time required to reach 80% of K

### 4. Hamming Distance Calculation (hamming_distance)
Purpose: Computes the number of differing characters between two strings of equal length.

Parameters:
username1 (str): First username.
username2 (str): Second username.
Returns:
An integer representing the Hamming distance (number of differing characters).
Raises:
InvalidValueError if the two strings are not of equal length.
Key Features:
Useful for comparing similarity between usernames or genetic sequences.  

Example Usage:
distance = hamming_distance("abcdef", "abcxef")
print(distance)  # Output: 1  

## 📌 Team Members
👤 Saurabh1234556
👤 @SamuelEA25
👤 @Ace-all
👤 @mirra-09
👤 Drihotu
👤 @PliciousG
