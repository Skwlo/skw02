# 使用Nginx作为基础镜像
FROM nginx:alpine

# 复制项目文件到Nginx的默认目录
COPY . /usr/share/nginx/html

# 暴露8080端口
EXPOSE 8085

# 启动Nginx
CMD ["nginx", "-g", "daemon off;"]
    
