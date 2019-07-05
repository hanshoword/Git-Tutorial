## Git-Tutorial

소스코드 블록은 다음과 같이 작성할 수 있습니다.

```c
#inlcude <stdio.h>

int main()
{
  printf("Hello World\n");
  retnru 0;
}

```

링크는 다음과 같이 작성할 수 있습니다.

[주소](https://www.naver.com)

순서 없는 목록은 다음과 같이 작성할 수 있습니다.

* 깃 튜토리얼
  * 깃 Clone
  * 깃 Pull
  * 깃 Commit
    * 깃 Commit 1)
    * 깃 Commit 2)
    
인용 구문은 다음과 같이 작성할 수 있습니다.

> '공부합시다.'

테이블은 다음과 같이 작성할 수 있습니다.

이름|영어|정보|수학
---|---|---|---|
한상훈|98점|87점|100점|
홍길동|97점|78점|93점|
이순신|89점|89점|79점|

강조는 다음과 같이 할 수 있습니다.

**강조선** ~~취소선~~ 

### python read frame code
```c
import cv2

cap = cv2.VideoCapture('video.mp4')

while True:
  # 프레임을 읽습니다.
  ret, frame = cap.read()
  if ret == True:
    cv2.imshow('FaceDetection', frame)

    if cv2.waitKey(30) & 0xFF == ord('q'):
        break
  else:
    break

cap.release()
cv2.destroyAllWindows()
```

### jupyter notebook upload folder

```c
import zipfile as zf

files = zf.ZipFile("find-a-car-park.zip", 'r')
files.extractall('data')
files.close()
```
### Github upload image [HTML]

```
<img src="https://~.png"  width="90%"></img>
Issues -> new Issue -> 이미지 드래그 후 html주소 
```
