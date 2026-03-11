# Sử dụng Node.js version 18 làm base image
FROM node:18

# Tạo thư mục làm việc trong container
WORKDIR /app

# Copy file ứng dụng vào container
COPY app.js .

# Mở cổng 3000
EXPOSE 3000

# Chạy ứng dụng
CMD ["node", "app.js"]