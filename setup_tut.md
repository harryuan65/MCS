# Mac 設定

1. 下載 server.jar
2. `chmod a+x server.jar`
3. 雙擊點開 server.jar
4. 編輯 eula.txt => true
5. 打開 PortMap，新增 Local Port->Port(25565 -> 25565)，他會顯示你的 Public IP
6. 打開 192.168.0.1，找到 Port Forwarding 設定
7. 新增 TCP/UDP 25565~25565 -> 25565，找這台電腦的 Local IP，設定上去
8. 用指令打開 server `exec java -Xmx2G -Xms2G -jar server.jar nogui`
9. 打開 minecraft -> 多人連線 -> 剛剛顯示的 Public IP
10. DONE!
