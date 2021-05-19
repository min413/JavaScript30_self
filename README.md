# JavaScript30_self
 self study by JavaScript30 challenge
 
## 01
- 기존 drum kit에서 피아노 소리와 css를 수정하여 piano kit로 만들었음
- javascript 코드를 응용한게 아니라서 아쉬움   
    
```python
EventTarget.addEventListener(type, listener[, options]);
```
> 지정한 이벤트가 대상에 전달될 때마다 호출할 함수를 설정  
> type - 반응할 이벤트 유형(여기선 'keydown' : 키 누름, 'transitionend' : css 전환)    
    

```python
document.querySelector(`audio[data-key="${e.keyCode}"]`);
```
> 선택자와 일치하는 문서 내 첫번째 Element를 반환  
> 일치하는게 없으면 null 반환    
    

```python
audio.currentTime = 0;
```
> 음악을 정지하고 처음 위치로 이동  
> 빠르게 여러번 눌러도 그때그때 반응함    
    

```python
classList.add // 클래스를 삽입
classList.remove //클래스를 제거
```  


```python
const keys = document.querySelectorAll('.key');
```
> 파라미터(selector) 그룹에 일치하는 다큐먼트의 엘리먼트 리스트의 정적리스트(NodeList)를 얻음  
  
***
## 02
- JS는 굉장히 단순해서 빠르게 이해함
- CSS로 시계바늘을 다루는 것을 배워감

```python
setInterval(setDate, 1000)
```
> setDate() 함수를 일정시간 간격으로(1000 == 1s) 반복 수행

```python
const now = new Date();
const seconds = now.getSeconds();
```
> getSeconds()는 현재 시간의 '초' 부분을 반환함

```python
document.querySelector('.second-hand');
```
> 문서에서 '.second-hand'라는 클래스를 사용하는 첫 번째 요소를 반환

***
