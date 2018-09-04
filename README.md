elasticsearch로그를 자동으로 지우기 

1. pip install elasticsearch-curator
2. find / -name curator
3. 찾은 경로를 test.sh에 수정 ( /home/ubuntu/.local/bin/curator 이부분 )
4. crontab -e  에서 00 02 * * * sh /home/ubuntu/test/test.sh 이런식으로 추가 
5. crontab -l 로 확인  
