A broadcast is a way of sending a message from a sprite which can be heard by all sprites. Think of it like an announcement made over a loudspeaker.

### ブロードキャストを送る

You can send a broadcast by creating a broadcast block and giving it a name:

+ Find the **broadcast** block under **Events**

+ Select **New Message** in the drop-down menu.

![broadcast block dropdown](images/broadcast-block.png)

+ Then type your message

![ブロードキャストを作成する](images/new-broadcast.png)

The message text can be anything you like, but it is useful to give the broadcast a sensible description. What happens when the message is received depends on the code you write.

### ブロードキャストを受け取る

スプライトはこのブロックを使用してブロードキャストに反応することができます：

![ブロードキャストを受け取る](images/receive-a-broadcast.png)

このブロックの下にブロックを追加して、スプライトがブロードキャスト信号を受け取ったときに何をすべきかを指示できます。

![受け取りの例](images/receive-example.png)