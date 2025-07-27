# Chess Engines

## Intro: Why You Should Care About Chess Engines
### I love chess
### Marked a tipping point considering mechanical intelligence
### Potential analogy for how we should approach the flood of generative AI

As soon as he was convinced I understood the rules of chess, my dad had me play against the computer. It was incredibly frustrating. When playing against my dad, at least my inevitable loss was preceded with him pointing out bad moves and explaining what I had missed. A good move brought praise, but a great move brought a brief bit of silence, which somehow felt even more rewarding. Playing a game against the computer, on the other hand, was a frustrating experience of helplessly watching each move get punished with frigid precision: no emotion, no explanation. It felt like an absolute that the computer would win: it had memorized openings, endgames, and had the ability to accurately calculate multiple moves ahead. Which is why after months of losing, when I finally beat the machine I didn't celebrate my victory. I thought something was wrong with the program. How could it lose?

But the certainty of mechanical victory has not always been as guaranteed as it seemed to me as a child. Only a few decades prior, only in science fiction would a chess player lose to an artificial intelligence. But the infamous game between Deep Blue vs. Gary Kasparov sent shockwaves through the whole world at large. Chess has often served as a heuristic for intelligence, and now we had a computer who was evenly matched with the best player alive. Had we finally created a machine that was smarter than us? Was the game of chess, thousands of years old, ultimately solved? Would we as a culture even play chess anymore?

As with most accomplishments in artificial intelligence, these fears were unfounded and ultimately hollow. Even though chess engine capabilities have exponentially improved over the past few years, the game of chess has not dipped in popularity nor relevance. We have incorporated chess into how we study and analyze the game. We continue to play chess because, ultimately, playing chess is fun. And I think the perseverance of chess is important to remember as we watch a monsoon of AI-generated art pollute the internet. So in this article, I seek to break down the evolution of the chess engine and how some of the greatest minds in computer science approached capturing the soul of chess in paper and metal.

Sources:
  * https://www.scientificamerican.com/article/20-years-after-deep-blue-how-ai-has-advanced-since-conquering-chess/
  * https://www.ibm.com/history/deep-blue

## Pre-computer: Hiding the Man in the Machine
### The Mechanical Turk, Ajeeb, and Mephisto
### El Ajedrecista: the first true computer game

The first chess playing automatons appeared pulled from the pages of science fiction: including the turban-wearing, pipe-smoking upper half of a Turkish man, and a life-sized, velvet-clad devil with cloven hooves. Up until the 20th century, automatons like The Mechanical Turk, Ajeeb, and Mephisto toured western nations and boasted victory over multiple historical opponents, including Benjamin Franklin, Napoleon Bonaparte, and Theodore Roosevelt. However, each automaton was less "auto" than it let on. Those who sought to create chess playing automatons took an approach popular with both modern AI companies and chess players alike: they cheated. Devices like the Mechanical Turk and Ajeeb concealed operator compartments where a player could pilot the machine, and Mephisto used electric relays to enable remote control.

The first true chess playing machine was invented in Spain by Leonardo Torres Quevedo. Named "El Ajedrecista", or "The Chess Player", the automaton was only capable of playing a specific scenario in chess: the King-Rook-King checkmate. The machine consisted of a chessboard ontop of an electric circuit, where the human player moved the black King and El Ajedrecista moved the white King and Rook. It could not play a whole game like its "automaton" predecessors, but it could play completely on its own by following the algorithm devised by Torres:
***
If the black King
    is in the same zone as the rook
        then the rook moves away from the zone to either the a- or the h-file.
    is not in the same zone as the rook and the vertical distance between the black king and the rook is
        more than a square
            then the rook moves one square vertically towards the black king.
        one square, with the vertical distance between the two kings being
            more than two squares
                then the king moves one square vertically towards the black king.
            two squares, with the number of squares representing their horizontal distance apart being
                odd
                    then if the rook is on the a- or h-file, it moves to the b- or g-file respectively, and vice versa.
                even
                    then the white king moves one square horizontally towards the black king.
                zero
                    then the rook moves one square vertically towards the black king.
***
This progress was crucial, as it was the first time an inventor had accurately captured a piece of chess in the machine. By devising a clear set of instructions which a computer could follow, Torres made the first step towards writing the fundamental building blocks that would comprise the first chess engine.

Source: https://web.archive.org/web/20051125113328/http://www.chessgraphics.net/ac.htm
Source: https://www.chessprogramming.org/El_Ajedrecista#cite_note-15

## Playing the game on paper: Shannon, Turing, and Von Neumann
### Turochamp
### Von Neumann's Min-Max theorem
### Shannon's Alpha Beta Pruning

## Playing the game on metal: Bernstein, Thompson, and Deep Blue
### Alex Bernstein & the 2 Move Checkmate
### Ken Thompson & Belle
### Shannon's Alpha Beta Pruning


## Post-computer: Taking the Man out of the Machine
### Stockfish NNUE
### Leela Zero
### Alpha Zero

## Outro: Where does that leave us?
