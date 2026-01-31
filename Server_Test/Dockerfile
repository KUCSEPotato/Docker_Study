FROM node:lts-alpine3.23

WORKDIR /app
# RUN npm install express
COPY . .
# 1번 방법
# os에 있는 shell을 이용
# 취약점 발생 가능
# RUN npm install

# 2번 방법 (추천)
RUN ["npm", "install"]

# memo용
EXPOSE 8080

# 마지막 명령어
CMD [ "node", "server.js"]