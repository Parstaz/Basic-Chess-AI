# Basic-Chess-AI
The A.I uses Nega-Max Algorithm to search for the best moves, it also tracks the game progress and the difficulty of the A.I. can be changed by the user for a higher difficulty setting.

#Min Max Algorithm
An algorithm used to determine the score in a zero-sum game after a certain number of moves, with best play according to an evaluation function. The algorithm can be explained like this: In a one-ply search, where only move sequences with length one are examined, the side to move (max player) can simply look at the evaluation after playing all possible moves. The move with the best evaluation is chosen. But for a two-ply search, when the opponent also moves, things become more complicated. The opponent (min player) also chooses the move that gets the best score. Therefore, the score of each move is now the score of the worst that the opponent can do.

#Alpha Beta Algorithm(Alpha Beta Pruning)
The Alpha-Beta algorithm (Alpha-Beta Pruning, Alpha-Beta Heuristic [2] ) is a significant enhancement to the minimax search algorithm that eliminates the need to search large portions of the game tree applying a branch-and-bound technique. Remarkably, it does this without any potential of overlooking a better move. If one already has found a quite good move and search for alternatives, one refutation is enough to avoid it. No need to look for even stronger refutations. The algorithm maintains two values, alpha and beta. They represent the minimum score that the maximizing player is assured of and the maximum score that the minimizing player is assured of respectively.

