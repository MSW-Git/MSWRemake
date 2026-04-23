# MSWRemake

메이플스토리 월드의 리메이크 월드를 로컬 워크스페이스 형태로 제공하는 저장소입니다.

## 포함된 월드

- [`[Remake] 광부 시뮬레이터`](https://maplestoryworlds.nexon.com/ko/play/bb572bfdb5cc476faea296c2f7ed8060/)
- [`[Remake] 메소전사`](https://maplestoryworlds.nexon.com/ko/play/88418dbd531d4024956888003ca0f7c7/)
- [`[Remake] 메이플듀얼`](https://maplestoryworlds.nexon.com/ko/play/d89013e15df64caf9cf088755c2cb32e/)
- [`[Remake] 메토체스`](https://maplestoryworlds.nexon.com/ko/play/fdf7a8eba2394516aa94b5a0b69394e2/)
- [`[Remake] 몬스터 농장`](https://maplestoryworlds.nexon.com/ko/play/ad9cad8b7930435dbc0a5f176fe13796/)
- [`[Remake] 츄츄버거 1호점`](https://maplestoryworlds.nexon.com/ko/play/06c72f9a0d2f4719aca0b82297d299f7/)

## 사용법

> 로컬 워크스페이스에 대한 자세한 내용은 [가이드](https://maplestoryworlds-creators.nexon.com/ko/docs?postId=1165)를 확인해 주세요.

1. 저장소를 Clone 합니다.
   ```
   git clone https://github.com/MSW-Git/MSWRemake.git
   ```

2. 메이플스토리 월드를 실행하고 메이커에서 새 월드를 만듭니다.

3. **Workspace - WorldConfig - LocalWorkspace**를 활성화합니다.

4. 로컬 워크스페이스로 지정한 폴더를 열고, 폴더에 있는 파일을 모두 삭제합니다.

5. 앞서 Clone 했던 폴더에서 리메이크하고자 하는 월드의 폴더 내 파일을 모두 복사하여 로컬 워크스페이스 폴더에 붙여 넣습니다.

6. 메이커로 돌아와서 **Workspace - MyDesk 우클릭 - Reimport All**을 선택합니다.
