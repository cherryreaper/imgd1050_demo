# Subtxt
Subtxt is a speculative 4-bit programming language used to denote the difference between what someone says and what they feel.
## Utilization
Users write out words using three 4-bit numbers to denote:
- A word o a scale from yes to no. These words should sxpress what you say.
- A color on a scale of red to green. This word should express how much you mean the word you are saying.
- The placement of their word on a singular linear line (this only goes up to 8)
  
Input will be will be read as follows:
[word] [color] [placement]

Words can be strung together to form possible reponses to questions.

## The System
Choose a response and a color.

![image](https://github.com/user-attachments/assets/f92685f2-afd5-4267-9ad7-9604fa2302fa)

Place the word.

![image](https://github.com/user-attachments/assets/f8834969-cf56-4468-ac16-8cfac199b077)

### Example
This code:

1011 1000 0011

1110 0011 0001

0101 1110 0010

1101 0101 0000

Will generate  the following image:

![image](https://github.com/user-attachments/assets/f2f580f8-4b28-4493-acbe-4e70b91a6add)


This image depicts someone who has agreed to do something despite not really wanting to do it.

## Challange
Answer the following question using the code. Try to use 3 or word segments:
⋅⋅⋅Could you drive me to the airport at 5 am this saturday?
