게임이름 : 그시절 운동회 3종경기

게임의 간단한 소개
- 1vs1대전게임으로 학창시절 운동회를 하면 하던 3가지 경기(계주, 줄다리기, 박터트리기)를 한판식 플레이 하여 3경기중 2가지 경기를 먼저 이기는 플레이어가 최종 승리하는 게임입니다.
1. 계주
계주Scene에는 player1과player2캐릭터를 운동장track의 백그라운드에 넣어 player1은 q랑 w를 연타하면 앞으로 달려가고 player 2는 <와>를 연타하면 앞으로 달려가, 3000의 거리에 결승선을 두고 그 결승선 까지 화면이 스크롤되면서 tkinter창으로 먼저 도착한 player와 도착시간을 알려주는 코드를 짜보왔습니다.

pygame.Rect를 사용하여 캐릭터와 결승선을 그렸는데, 캐릭터는 게임프레임워크를 제작할 때 이미지로 바꿀 예정입니다.
또 pygame.time.Clock을 사용하여 게임프레임의 속도를 제어하여 달리는 것을 나타내고 도착시간을 도출하였고 tkinter.TK와 tkinter.messagebox를 사용하여 어느 player가 승리하였고 얼마나 걸렸는지 알려주는 코드를 짰습니다.

2.줄다리기
계주Scene과 마찬가지로 운동장track의 백그라운드에 각각의 player를 여러명 복사하고임이름 : 그시절 운동회 3종경기

게임의 간단한 소개
- 1vs1대전게임으로 학창시절 운동회를 하면 하던 3가지 경기(계주, 줄다리기, 박터트리기)를 한판식 플레이 하여 3경기중 2가지 경기를 먼저 이기는 플레이어가 최종 승리하는 게임입니다.
1. 계주
계주Scene에는 player1과player2캐릭터를 운동장track의 백그라운드에 넣어 player1은 q랑 w를 연타하면 앞으로 달려가고 player 2는 <와>를 연타하면 앞으로 달려가, 3000의 거리에 결승선을 두고 그 결승선 까지 화면이 스크롤되면서 tkinter창으로 먼저 도착한 player와 도착시간을 알려주는 코드를 짜보왔습니다.

pygame.Rect를 사용하여 캐릭터와 결승선을 그렸는데, 캐릭터는 게임프레임워크를 제작할 때 이미지로 바꿀 예정입니다.
또 pygame.time.Clock을 사용하여 게임프레임의 속도를 제어하여 달리는 것을 나타내고 도착시간을 도출하였고 tkinter.TK와 tkinter.messagebox를 사용하여 어느 player가 승리하였고 얼마나 걸렸는지 알려주는 코드를 짰습니다.

2.줄다리기
계주Scene과 마찬가지로 운동장track의 백그라운드에 각각의 player를 여러명 복사하고 리듬에 맞추어 줄을 당기는 코드를 짤예정입니다.
위 게임에서 사용할 리듬에 맞추는 프로그램은 닌텐도게임의<도와줘! 리듬히어로>를 참고 하였고 player1d은 a 키를 player2는 ' 키를 줄어드는 바깥쪽 원이 안쪽원과 정확히 겹치는 순간 키를 눌러서 맞출 때 마다 캐릭터들이 줄을 당기고 5번 먼저 맞추는 플레이어가 승리하는데, 5번을 양쪽 모두 맞출경우 한명의 player는 성공했지만 다른 player가 실패했을때, 성공한 player의 승리로 끝나게 되는 코드를 짤 예정입니다.

clock을 사용하여 원이 줄어드는 프레임 속도를 제어해야하고 circles를 사용하여 줄어드는 원과 점수를 획득할 수 있는 원을 생성해야합니다.또 계주게임과 마찬가지로 tkinter.TK와 tkinter.messagebox를 사용하여 어느 플레이어가 이겼는지 결과를 알려주는 오브젝트도 만들어야 할 것 같습니다.

3.박터트리기
Scene에는 각 player의 팀의 색상의 박 2개만 입력 할 예정이고 화면에 랜덤한 위치에 각각의player가 눌러야할 랜덤의 키를 랜덤하게 뛰어서 각 턴마다 먼저 누르는 player의 박이 조금씩 열리다가 6번 먼저 키를 찾아서 누르는 플레이어가 승리하는 코드를 짤 예정입니다.

player의 정보, 색상 등을 알려줄 수 있는 player클래스와 key를
