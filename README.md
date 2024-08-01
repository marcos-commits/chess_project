# Basic Two Player Chess Game(일반 두 명 체스 게임)
___
**Rule 1(1번 규칙)**
White piece Goes first(항상 흰색 돌이 먼저 시작한다.) 

**Rule 2(2번 규칙)**
Whoever catches the King wins the game(왕을 먼저 잡는 사람이 승자이다.)

**Rule 3(3번 규칙)**
Each takes turn((흰색돌이 움직였으면 다음 차례는 검정색 돌 차례이다.)

___

**How to Start a Game(게임 하는 방법)**

 * Git clone to your local computer(개인 컴퓨터에 깃 클론으로 저장한다.)
   
 * Copy path your whole index.html, and open your browser and copy and paste it(개인 컴퓨터에 저장 되었으면 index.html가 있는 전체 경로를 복사 해서 브라우져 창에 입력한다.)

 * **Start playing Chess!! (체스 게임 시작!!)**

___
**Piece Movements(각각 돌들의 특징)**

<*Pawn(폰)*>

<img src="https://github.com/marcos-commits/chess_project/blob/main/img/blackPawn.png" width="50px" height="50px" title="blackPawn" /> 
  
 * First movement can go forward one or two times(첫 번째 움직일때 앞으로 1번 아니면 2번 전진 할 수 있다.)
   
 * After first movement Pawn can only move one forward at a time (첫 번째 움직임 이후 부터는 무조건 앞으로 1번 전진 할 수 있다.)
   
 * Pawn can capture an enemy piece by moving one diagonally forward left or one forward right (적의 돌들을 잡으려면 한쪽 왼쪽 대각선이나 한쪽 오른쪽 대각선으로 전진 상태로 잡을 수 있다.)
   
 * When the enemy's pawn moves two times forward for the first move, and when you are at the same row, you can capture the enemy. It's called `en Passant`. (적의 폰이 첫 번째 움직일때 두번 움직이고 아군의 폰이 같은 행에 나란히 있는 경우 `엉 파쌍`이란 움직임으로 통해서 적을 잡을 수 있다.)

 * When reaching to the end, pawn will be promoted either Knight, or Bishop, or Rook, or Queen. (폰이 남의 직영까지 끝까지 가면 기사 아니면 비숍 아니 룩 여왕 으로 승진이 가능다) 


<*Rook(룩)*>

<img src="https://github.com/marcos-commits/chess_project/blob/main/img/blackRook.png" width="50px" height="50px" title="blackRook" />

 * Can move forward, backward, left, and right (전진, 후진, 왼쪽, 오른쪽으로 자유 자재로 움직일 수 있다.)
   
 * Can't move diagonally (대각선으로는 못 움직인다.)
   
 * Can capture the enemy pieces with the same movements (적을 잡는 것은 위에 명시되어 있는 움직임으로 통해서 잡는 것이 가능하다.)
   
 * When the King and Rook didn't move once and no pieces are at the sideways without being checked. Rook can move next to the King. King moves leftwards two times and Rook moves rightward to the King. It's called `castling`. (아군의 왕과 룩이 한번도 움직이지 않는 상태이고 왕과 룩 사이에 돌들이 비어 있고, 체크가 되어 있지 않는 상태여야 하고, 룩과 왕 사이에 적이 공격하지 않는 상태이면, 왕은 오른쪽이나 왼쪽으로 두 칸 움직이는 것이 가능하다. 왕이 두 칸 움직이면 룩은 왕 바로 옆에 보호한다.)


<*Knight(기사)*>

<img src="https://github.com/marcos-commits/chess_project/blob/main/img/blackKnight.png" width="50px" height="50px" title="blackKnight" />

 * Can move 1 forward or downward and 2 sideways (left or right); Can move 2 forward or downward and 1 sideways (left or right) [앞으로나 뒤로 한 칸 그리고 왼쪽이나 오른쪽으로 두 칸 이동이 가능하고 아니면 앞으로나 뒤로 두 칸 그리고 왼쪽이나 오른쪽으로 한 칸 이동이 가능하다.)
   
 * Can capture the enemy pieces with the same movements (적 잡는 것은 위에 명시되어 있는 움직임과 동일하다.)
   
 * Can jump the enemy or same color pieces while moving (적의 돌들이나 아군의 돌들을 뛰어 넘을 수 있다.)


<*Bishop(비숍)*>

<img src="https://github.com/marcos-commits/chess_project/blob/main/img/blackBishop.png" width="50px" height="50px" title="blackBishop" />

 * Can only move diagonally (대각선으로만 자유자재로 움직임이 가능하다.)
   
 * Can capture the enemy pieces with the same movements (위의 명시되어 있는대로 대각선으로 적들을 잡을 수 있다.)


<*Queen(여왕)*>

<img src="https://github.com/marcos-commits/chess_project/blob/main/img/blackQueen.png" width="50px" height="50px" title="blackQueen" />

 * Movement is a combination of rook and bishop(Can move forward, downward, left, right, and diagonally) [비숍과 룩의 움직임들을 합쳐 놓은 것이라고 볼 수 있다.)
   
 * Can capture the enemy pieces with the same movements (위의 명시되어 있는 움직임으로 적들을 잡을 수 있다.)
   

<*King(왕)*>

<img src="https://github.com/marcos-commits/chess_project/blob/main/img/blackKing.png" width="50px" height="50px" title="blackKing" />

 * Movement is a combination of rook and bishop, but it can only move only one spot(Can move 1 forward, 1 downward, 1 left, 1 right, and 1 diagonal movement [여왕의 움직임과 동일하나 왕은 한 칸만 이동이 가능하다.]
   
 * Can capture the enemy pieces with the same movements (위의 명시되어 있는 움직임으로 적들을 잡을 수 있다.)

 * When the King and Rook didn't move once and no pieces are at the sideways without being checked. Rook can move next to the King. King moves leftwards two times and Rook moves rightward to the King. It's called `castling`. (아군의 왕과 룩이 한번도 움직이지 않는 상태이고 왕과 룩 사이에 돌들이 비어 있고, 체크가 되어 있지 않는 상태여야 하고, 룩과 왕 사이에 적이 공격하지 않는 상태이면, 왕은 오른쪽이나 왼쪽으로 두 칸 움직이는 것이 가능하다. 왕이 두 칸 움직이면 룩은 왕 바로 옆에 보호한다.)
   
   







