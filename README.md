# tic_tac_toe_bot

Introducing the Tic Tac Toe Bot, a sophisticated script designed to anticipate and analyze multiple moves ahead. This intelligent algorithmic solution efficiently stores the computed moves in a dedicated file, ensuring time-saving benefits for subsequent computations. Originally developed for a traditional 3×3 tic tac toe game, the script has been further enhanced to accommodate a versatile NxN tic tac toe board.

One significant challenge encountered during the implementation process arose when the computing times for larger board sizes (N >= 4) exceeded 20 seconds per move. This delay posed an inconvenience for players engaged in matches against the computer. To address this issue, a creative workaround was devised, involving the conversion of each board position into a simplified numerical representation. Leveraging the inherent properties of prime numbers, each position was assigned a unique prime number corresponding to either "X" or "O." By transforming the entire game board into a single numerical value, the computational efficiency was dramatically improved compared to recalculating the board state.

Following an evaluation of the board at a predetermined depth, the script intelligently transformed the board into a numerical representation, which was then stored in a .pkl file for future utilization.
