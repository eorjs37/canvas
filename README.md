# Canvas

## canvas 태그
> 웹 상에 도형과 같은 그래픽적인 것을 표현할때 사용하는 태그


### getContext
> 2D으로 할지 3D로 할지 정하는 부분
```javascript
const canvas = document.querySelector('#tutorial');
const ctx = canvas.getContext('2d');
```

### fillRect(x,y,width,height)
> 도형을 그리는 함수 이며, x,y는 좌표이며 weight,height는 크기이다.

### strokeRect(x,y,width,height)
> 윤곽선을 그리는 함수, x,y는 좌표이며 weight,height는 크기이다.

### clearRect(x, y, width, height)
> 특정 부분을 지우는 함수, x,y는 좌표이며 weight,height는 크기이다.

### beginPath
> 새로운 경로를 만드는 함수. 선 그리기 할때 보통 시작한다.

### stroke
> 경로들의 윤곽선을 채우기 위해 사용

### fill
> 경로들의 내부를 채우기 위해 사용

### moveTo(x, y)
> 펜을 지정된 위치로 이동

### closePath
> 마지막 지점부터 시작지점까지 직선 연결