### 43강 SSH 서버 설치와 putty 다운로드 및 접속하기



#### putty 사용하기

* putty를 이용하여 telnet이나 ssh을 사용할 수 있다. 



#### SSH 서버 설치하기

* SSH 설치하기

  * `sudo apt-get install apenssh-server` 
  * 정상 설치가 안되는 경우 `sudo apt-get update` 후 재시도

* SSH 재시작하기

  * `sudo /etc/init.d/ssh restart`

* SSH 제거하기

  * `sudo apt-get remove openssh-server`

* 로컬에서 SSH 접속 테스트

  * `ssh localhost`

    

  