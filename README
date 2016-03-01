### Execution:
```
./a3 < board_file
```
Note: Execution of script runs subprocess ```rm board.*``` on current folder before generation of boards.

### Assumptions:
Working through the rules outlined in the pdf left the board generation process
with a few required assumptions. These assumptions may differ from the tested 
boards used on the online generator; however, he rules are taken straight from 
the pdf.

```1.``` Serpents are assumed to poison simultaneously. Therefore, a white and black 
serpent adjacent will remove each other from the board.

```2a.``` The after effects run in sequence. This means the poisoning from the 
serpents occurs before the golf carts, transporters, and joey exploding.

```2b.``` Serpents poison before transporting doing a "drive-by" poison. Therefore,
a transported serpent must wait a turn to poison on the other pad.

```3a.``` When a serpent poisons an enemy piece, and adjacent to that enemy piece is an enemy old woman, the serpent is removed, the enemy piece is removed, and the 
enemy old woman transforms into an empress.

```3b.``` When an empress poisons an enemy piece, and adjacent to that enemy piece is an enemy old woman, the empress is NOT removed, the enemy piece is removed, and 
the enemy old woman is NOT transformed. The rules claim the serpent transforms 
the old woman and not the poison itself.

```4.``` The transporter rules were changed from the pdf to:
```
  (3,1) - > (7,9)
  (3,9) - > (3,1)
  (7,1) - > (3,9)
  (7,9) - > (7,1)
```