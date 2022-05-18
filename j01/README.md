# The Beautiful Simplicity of Wordle
## Jonathan Phan, 2/25/22
Wordle is a popular word guessing game/app that was recently acquired by the *New York Times*, and demonstrates a beautifully clean and simple page, the usability of which helped propel it to its fame. Below is a screenshot of its initial look on desktop. Note that the mobile version looks almost completely identical. 
![Wordle home page](https://user-images.githubusercontent.com/72906410/155825635-87f0817d-f43f-4332-8fb2-6120b6c17a06.png)
> *Figure 1: Wordle Home Page*

As Wordle is a game, usability aspects such as **effectiveness** and **efficiency** are not very important, as long as the product works at all. Furthermore, things like **usefulness** is extremely subjective, as its main use is entertainment. What is much more important is that the game is extremely **learnable** and **memorable**, referring to how easy a product is to use when first starting and how easy it is to come back to after periods of inactivity, respectively. 
![wordle partially correct](https://user-images.githubusercontent.com/72906410/155827085-373a5552-54d3-4ad3-ab5f-dfc4958018df.png)
> *Figure 2: A partially correct guess*

![wordle correct](https://user-images.githubusercontent.com/72906410/155827091-6fdb077e-a522-44d7-a164-a868049354f8.png)
> *Figure 3: A correct guess*

Through these images, it is clear how Wordle accomplishes a very learnable system through its use of color. The incorrect guesses are greyed out, both in the display *and* keypad to make clear to the player that it is an incorrect guess. The orange yellow color appears on a guess that is partically correct, that is a guess where the letter appears in the word but not in the position guessed, while a green color is used for a completely correct guess. These are examples of **weak affordances**, or things that can suggest a certain meaning but are not explicit, where typically the color green is associated with being correct and orange is an error.

For those unaware, Wordle is a game that limits its playing time to 6 guesses per word, one word per day. Because of this, it is important that either someone can easily understand how to play without much instruction or easily remember it after playing it once. Wordle accomplishes this through the use of **strong affordances**. A strong affordance is some aspect of a product that clearly indicates its intended means of use. Looking back to Figure 1, notice that without doing anything, a keyboard appears, and without numbers. It is a crystal clear indication that the player is meant to type in letters. Furthermore, 5 discrete boxes per row suggest that there should be 5 letters, and the inability to move the cursor downwards indicates that 5 is the limit - that is, one should guess a five letter word. From here, we should explore how Wordle handles **error tolerance**. Error tolerance refers to a user's ability to identify and recover from mistakes. To be clear, error tolerance in Wordle is not guessing the wrong word, as that is an intended step of the game. Error tolerance in this case handles what should happen if the user enters an invalid word. In this case, the boxes which hold the letters shake and a message appears which states: "Not in word list". 

Through all of these seeming simple things in a simple game, Wordle is able to reach a wide audience and see a massive spike of success. And its simplistic design keeps those elements out of the way of the players and lead to a smooth and satisfying experience.
