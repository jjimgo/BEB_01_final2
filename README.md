BEB_01기 Project_3

프론트 : 장현서, 임우철

컨트랙트 : 이형기

서버 및 DB : 유호진

기본 홈페이지 구조
- 현재 GroundX의 요청에 따라서 web3를 caver-js로 변경하는 작업을 진행하고 있기 떄문에 코드가 일부 수정되어 작동을 하지 않을수 있습니다.
- caver-js로 변경을 하게 되면 1초에 블록이 생성이 되기 떄문에 따로 betchServer를 구현할 필요가 없고 그러기 떄문에 가스비를 절감할수 있는 부분에서는 DAo형태로 구현을 해보고자 합니다.
- 따로 Solidity를 학습하였던 경험이 있어서 unchecked, create2같으 부분도 활용할 부분ㅇ 있으면 활용해보고자 합니다.
