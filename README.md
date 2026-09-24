# Which Female Athlete Are You Most Like?

## Overview
This program is a personality quiz about female athletes. The user will answer five questions about their personality and sports preferences. Based on their answers, the program will determine which female athlete they are most like. Possible results include A'ja Wilson, Simone Biles, Coco Gauff, Sha'Carri Richardson, and Serena Williams.l.


## Sample Questions and Responses
> Do you prefer working with a team or alone?
> 1. Team
> 2. Alone
>
> What describes you better?
> 1. Fast
> 2. Strong
>
> When facing a challenge, how are you?
> 1. Calm
> 2. Competitive 
>
> Where would you rather compete?
> 1. Indoors
> 2. Outdoors
>    
> What is important to you?
> 1. Winning
> 2. Having fun
> 
## Variables
> work_style (str): stores whether the user chooses team or alone. This is used later to help determine the athlete result.
> ability (str): stores whether the user chooses fast or strong.
> challenge (str): stores whether the user chooses calm or competitive.
> location (str): stores whether the user chooses indoors or outdoors.
> goal (str): stores whether the user chooses winning or having fun.
> athlete (str): stores the final female athlete result.

# One variable works because the program gives the user one final athlete.

## Conditional Logic Outline
> Example:
> - **Conditional statement 1** : Working Style
>   - `if` response is team: display congratulatory message, the program displays a message saying they enjoy working with others.
>   - `elif` If the user chooses alone, the program displays a message saying they enjoy working independently.
>   - `else`: If another answer is entered, the program tells the user the answer was not recognized.

>
> - **Conditional statement 2** : Abiltiy
>   - `if` If the user chooses fast, the program displays a message saying speed matches their personality.
>   - `elif` If the user chooses strong, the program displays a message saying strength matches their personality.
>   - `else`:  If another answer is entered, the program tells the user the answer was not recognized.
>  
> - **Conditional statement 3** : Facing Challenges
>   - `if`: If the user chooses calm, the program displays a message saying they stay calm when facing challenges.
>   - `elif`: If the user chooses calm, the program displays a message saying they stay calm when facing challenges.
>   - `else`:If another answer is entered, the program tells the user the answer was not recognized.
>     
> - **Conditional statement 4**: Location 
>   -  `if`:  If the user chooses indoors, the program displays a message saying they prefer indoor competition.
>   -  `elif`: If the user chooses outdoors, the program displays a message saying they prefer outdoor competition.
>   - `else`: If another answer is entered, the program tells the user the answer was not recognized.
>  
>   - **Conditional statement 5** : Overall Goal
>  - `if`: If the user chooses winning, the program displays a message saying they are focused on winning.
>  - `elif`: If the user chooses having fun, the program displays a message saying they enjoy having fun while competing.
>  - `else`: If another answer is entered, the program tells the user the answer was not recognized.
>
>  # Final Athlete Result
>  - `if`: If the user chooses team and strong, the result is A'ja Wilson.
>  - `elif`: If the user chooses alone, calm, and indoors, the result is Simone Biles.
> - `elif`: If the user chooses alone, fast, and outdoors, the result is Sha'Carri Richardson.
>  - `elif`: If the user chooses alone, competitive, and winning, the result is Serena Williams.
>  - `else`: If the answers do not match the choices above, the result is Coco Gauff.

 # There are no nested conditional statements because the program can check the answers using separate conditional statements and logical operators such as and.


## How to Run
1. Clone this repo
2. Run `python3 main.py` or `python main.py`

## Demo Video
[DELETE AND REPLACE ME: link to your 5-minute explanation video]
