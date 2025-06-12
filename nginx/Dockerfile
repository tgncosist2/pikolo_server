FROM nginx:latest

# nginx 설정 파일만 복사 (정적 파일은 volume으로 마운트)
COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 80 443

CMD ["nginx", "-g", "daemon off;"]