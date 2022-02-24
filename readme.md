# Drag & Drop Event

먼저 드래그할 요소에 draggable="true" 속성을 입력한다

## **일단 사용했던 drag drop 이벤트들..**

## **1. dragstart**

- 요소가 드래그 시작 될 때 발생

## **2. dragstop**

- 요소가 드래그 끝나면 발생

## **3. dragenter**

- 요소가 드랍이 될수있는 적합한 요소 위에 있으면 발생 하는듯..

## **4. dragover**

- 요소가 드랍될 요소위로 지나가면 발생

## **6. drop**

- 요소가 드랍될 대상과 바뀌면 발생

- 이때 **envet.target** 은 **드래그 대상**이 아니라 **드랍된 대상**

## **7. drop, dragover Event**

- event.preventDefault()를 호출 해줘야 한다고 함
- touch event, pointer event 안좋은 상황이 발생 할 수도 있다고..?

## 결과적으로 버그도 많고 썩 좋은 api는 아니라고 함...
