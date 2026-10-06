# 베이스 이ㅣㅣㅣㅣ미ㅣㅣㅣㅣ지ㅣㅣㅣ
FROM ubuntu:24.04

# nginx 설치
RUN apt -y update && apt -y upgrade
RUN apt -y install nginx

# 포트 지지정정
EXPOSE 80

# 서버 실행(foreground 실행)
CMD ["nginx", "-g", "daemon off;"]
