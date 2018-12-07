A broadcast is a way of sending a message from a sprite which can be heard by all sprites. Think of it like an announcement made over a loudspeaker.

### 브로드캐스트 전송

You can send a broadcast by creating a broadcast block and giving it a name:

+ Find the **broadcast** block under **Events**

+ Select **New Message** in the drop-down menu.

![broadcast block dropdown](images/broadcast-block.png)

+ Then type your message

![방송 만들기](images/new-broadcast.png)

The message text can be anything you like, but it is useful to give the broadcast a sensible description. What happens when the message is received depends on the code you write.

### 메시지 받기

스프라이트는 이 블록을 사용하여 방송된 메시지에 반응합니다.

![메시지 받기](images/receive-a-broadcast.png)

아래에 블록을 추가하면, 스프라이트가 특정 메시지를 받았을 때 어떤 작업을 수행할지 지시할 수 있습니다.

![수신 예제](images/receive-example.png)