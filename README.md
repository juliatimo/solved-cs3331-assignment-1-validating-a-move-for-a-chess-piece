Download Link: https://assignmentchef.com/product/solved-cs3331-assignment-1-validating-a-move-for-a-chess-piece
<br>
Main task: given a chess piece and its initial position (x, y), verify that you can move it to the new position. The program should write “Piece_Name at X, Y can move to X+1, Y” or “Piece_Name at X, Y can NOT move to X+1, Y”. For example, “Queen at D, 1 can move to E, 1”. When verifying the move, check that initial and final positions are inside the chess board, new position is possible based on the rules for that piece and consider that the chess board only has that piece.

You are given a text file with several chess pieces. Number of pieces, types of pieces, and the order of the pieces may change every time you read a file. Each row in the file includes piece_name, color, pos_X, and pos_Y.

You must write a program to verify the movement of each chess piece in the given file. You must read values from the file, create an object/structure for each piece, allocate all the pieces in an array, prompt the user for the new position, and transverse the array verifying a move for each piece with the new position. You should print the verification result for each piece.

Chess additional information. A chess board contains 8 by 8 boxes which are potential places for the chess pieces. There are six different pieces: Pawn, Rook, Knight, Bishop, Queen, and King. Each piece has its own movement rules. Your task is to read some movements from a file and validate those ones.

The ChessU website has the following guidance<sup>1</sup>: In the initial position setup, the light queen is positioned on a light square and the dark queen is situated on a dark square. The diagram below shows how the pieces should be initially situated.




The movement rules for each chess piece follows:

<ul>

 <li>King can move exactly one square horizontally, vertically, or diagonally.</li>

 <li>Queen can move any number of vacant squares diagonally, horizontally, or vertically.</li>

 <li>Tower can move any number of vacant squares vertically or horizontally.</li>

 <li>Bishop can move any number of vacant squares in any diagonal direction.</li>

 <li>Knight can move one square along any rank or file and then at an angle. The knight´s movement can also be viewed as an “L” or “7″ laid out at any horizontal or vertical angle.</li>

 <li>Pawns can move forward one square, if that square is unoccupied. If it has not yet moved, the pawn has the option of moving two squares forward provided both squares in front of the pawn are unoccupied. A pawn cannot move backward.</li>

</ul>

1.<a href="http://www.chesscoachonline.com/chess-articles/chess-rules">http://www.chesscoachonline.com/chess</a><a href="http://www.chesscoachonline.com/chess-articles/chess-rules">–</a><a href="http://www.chesscoachonline.com/chess-articles/chess-rules">articles/chess</a><a href="http://www.chesscoachonline.com/chess-articles/chess-rules">–</a><a href="http://www.chesscoachonline.com/chess-articles/chess-rules">rules</a>