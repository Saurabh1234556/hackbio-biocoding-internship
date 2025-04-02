# hackbio-biocoding-internship
# stage-o
Hey! I am saurabh mazumdar , I have completed the task for this stage.
- The codon assigned to me was UCU (Serine)
- This is my Stage-0 Task
- TASK INSTRUCTION
 Use any data structure of your choice to organize the following information
 Your names, Your slack username, Your email, Your hobby ,Your countries ,Your discipline, Your preferred programming language
 * NO functions, loops, conditionals or any complex concepts
 * code should include a final print statement that prints the organized output in a logical and understandable way
- TASK COVERS FOLLOWING BASICS OF PYTHON
 * Python Syntax
 * Python Data Types
 * Data Structures
- TASK IMPLEMENTATION
  I have used nested dictionaries as a data structure to solve this task.
- Link of our script 
  https://github.com/Saurabh1234556/hackbio-biocoding-internship/blob/main/stage-0/stage_0.py
#stage-1
Function Scripts for DNA Translation, Logistic Growth and Hamming Distance Determination
📌 Task Overview
Here are four Python functions for various biological computations:

dna_to_protein: to translate DNA sequence into protein sequence.
generate_logistic_growth_curves: for generating multiple logistic growth curves with variations in lag and exponential phases.
time_to_80_percent_growth: to determines the time needed to reach 80% of the carrying capacity.
hamming_distance: for calculating the Hamming distance between pairs of usernames.
🛠 Requirements
Python 3.x
📥 Installation
Clone this repository to your local machine:

git clone https://github.com/SamuelEA25/HackBio-Coding-Internship.git
🚀 Testing the Function Script
Open your command line interface and locate the file directory for script1:

cd path/to/script1
Enter the interactive mode for Python by entering this command:

python
Import the script (script1) and manually call each functions to test them

1️⃣ Translate DNA to Protein:

from script1 import dna_to_protein
dna = "TCCAGATCCACAAGCCCAACTTTCAACAAA"
print("Protein sequence:", dna_to_protein(dna))
2️⃣ Generate Logistic Growth Curves:

from script1 import generate_logistic_growth_curves
growth_curves = generate_logistic_growth_curves(num_curves=10, max_time=20)
print("Generated logistic growth curves:", growth_curves[:2])
3️⃣ Calculate Time to 80% of Carrying Capacity:

from script1 import time_to_80_percent_growth
K, P, r = 1000, 10, 0.1
time_to_80 = time_to_80_percent_growth(K, P, r)
print("Time to reach 80% of carrying capacity:", time_to_80)
4️⃣ Compute Hamming Distance:

from script1 import hamming_distance
distance1 = hamming_distance("AmakaMadubuike", "AmakaMadubuike")
distance2 = hamming_distance("Mirra", "mirr9")
distance3 = hamming_distance("PreciousGift", "PreciousGift")
distance4 = hamming_distance("SamuelEA", "Samuel18")
distance5 = hamming_distance("DrIhotu89", "Cyndy8436")
distance6 = hamming_distance("Saurabh", "Saurabh")
print("Hamming Distance Results:")
print(f"AmakaMadubuike vs AmakaMadubuike: {distance1}")
print(f"Mirra vs mirr9: {distance2}")
print(f"PreciousGift vs PreciousGift: {distance3}")
print(f"SamuelEA vs Samuel18: {distance4}")
print(f"DrIhotu89 vs Cyndy8436: {distance5}")
print(f"Saurabh vs Saurabh: {distance6}")
📌 Team Members
👤 SamuelEA25

👤 @Ace-all

👤 @mirra-09

👤 @PliciousG

👤 Drihotu

👤 Saurabh1234556
