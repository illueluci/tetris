# tetris

original from https://www.youtube.com/watch?v=zfvxp7PgQ6c and I want to transform this classic tetris game into modern tetris game.

change log in 2 Apr 2022:
-controls : rotate counterclockwise, hard drop, holding a piece
-add counter_before_locking (so pieces doesn't immediately lock upon landing)
-7-bag system
-hold system
-scoring update (single, double, triple, tetris). no t-spin yet

change log in 3 Apr 2022:
-T-spin system (3 corner method) + and some bug fix. (because it's just 3 corner method, the t-spin is so generous lol)
-hold system bug fix
-soft drop slight improvement

change log in 5 Apr 2022
-back to back
-combo
-display line clear indicator
-wall kicks


to be implemented:
-scoring according to speed
-soft drop & hard drop scoring
-ghost piece


bug found :
-if line clear skips a line, grid is floating
-sometimes wall kick fails?
-instant game over if piece hangs above y=0 (to the left or to the right)
