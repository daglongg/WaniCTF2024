# bad Worker 

![image](https://github.com/j10nelop/m3d1r/assets/152776722/48a982fe-a8f3-463e-8ae7-31d74e8118c1)

- bài này ta có 2 cách để làm:

=> check chức năng của web trong đó có chức năng fetch data thì ta nhận được flag 

![image](https://github.com/j10nelop/m3d1r/assets/152776722/abb2eee2-6b62-4b98-8330-302c6381d948)

=> ta có thể check qua source ctrl u thì ta thấy chức năng 

![image](https://github.com/j10nelop/m3d1r/assets/152776722/3e9f5cb4-ef70-4bef-96b8-a8f21ff67dd6)

```
<script>navigator.serviceWorker.register('service-worker.js');</script>
```

check qua path thì ta thấy được 2 file FLAG.txt và dummy.txt thì chạy path FLAG.txt thi ta được

=> flag=FLAG{pr0gr3ssiv3_w3b_4pp_1s_us3fu1} 
