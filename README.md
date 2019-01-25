# Start-Vdev
Lộ Trình vào địa ngục
+   Lộ trình học python cho kỹ sư backend và kỹ sư tích hợp hệ thống  bao gồm những kiến thức tổng quan về hệ thống từ bước design, build hệ thống website lớn (theo mô hình microservice và Flask / Django framework)
    có tính scale cao kèm theo các công nghệ deploy trên nhiều server và data center dùng các tools: Docker, Nginx, Kong, Kubernetes, Rancher2, Consul, Rabbitmq, Redis.
+   Python basic
 
1. Cài đặt python, Pycharm

2. Các dạng dữ liệu cơ bản: number, string, bool, list, dict, tuples, set.

3. Các toán tử trong python

4. If, elif, else, for, while.

5. Hàm trong python, các hàm built-in

6. Làm quen với cách viết class trong python, phân biệt class method, static method, instance method, các trường hợp sử dụng tương ứng.

7. Thao tác với các database (Mysql, Mongo)
################################################################################################
Python advance
 
1. Python OOP với các ví dụ về đa hình, trừu tượng, đóng gói và kế thừa

2. Python list comprehension, dict comprehension.

3. Lambda function

4. Python multi-threading, multi processes

5. Python data structure - Thư viện chuẩn

6. Python decorator

7. Các design pattern cơ bản trong python (singleton, factory)
################################################################################################
Python best practice
 
1. Thiết lập pycharm để viết code theo chuẩn PEP8

2. Dùng Pycharm để debug python code

3. Unit test

4. Integration test

5. Cách phát hiện lỗi memory leak và cách fix

6. Cách quản lý các gói phụ trợ, cách build source code, mã hóa source code để phân phối cho bên thứ 3.
################################################################################################
Flask
 
1. Giới thiệu về Flask, so sánh với Django

2. Giới thiệu về REST API.

3. Flask basic routing

4. Flask Dynamic routing

5. Flask Debug mode

6. SQL database với FLask

7. Kết hợp chạy Flask application với Gunicorn, Nginx.
################################################################################################ 
Docker
 
1. Docker là gì, sự khác biệt giữa docker và VM

2. Các lệnh thao tác với docker: docker run, docker exec.

3. Docker image vs Dockerfile, sự khác biệt.

4. Cú pháp viết Dockerfile, cách build Dockerfile thành docker image, cách viết Dockerfile để tránh cache ở một số bước để docker image được update với những thay đổi mới nhất.

5. Cách tạo docker network, docker container hostname, docker container name, expose port từ trong docker ra ngoài.

6. Docker compose, chạy nhiều docker containers cùng một lúc với docker-compose
################################################################################################ 
Rancher2 - Kubernetes
 
1. Gioi thieu Rancher2, cách cài đặt single node trên máy local

2. Cách khái niệm cluster, node, pod, deployment, namespace

3. Cách tạo một custome cluster với Rancher2

4. Tạo một deployment, gán tài nguyên phần cứng cho các pod, kiểm tra hoạt động của pod qua Rancher GUI

5. Cài đặt Prometheus, Grafana qua Rancher catalog để theo dõi cluster (CPU, RAM, Network)

6. Tìm hiểu về rancher load balancer
################################################################################################
Python Deployment - Thiết kế và triển khai hệ thống
 
1. Gioi thiệu mô hình microservice, Những ứng dụng nào cần tới mô hình này.

2. Tại sao Nginx và Flask lại phù hợp với mô hình Microservice.

3. Giới thiệu Rabbitmq, khi nào dùng REST, khi nào dùng message queue.

4. Viết một microservice có phần gửi và nhận task qua rabbitmq.

5. Kiểm thử hoạt động của microservice bằng postman

6. Redis, Các cách sử dụng. Chương trình minh họa với python code.

7. Celery architecture. Chương trình hoàn chỉnh sử dụng celery với các microservice sử dụng Flask framework, rabbitmq như broker, redis để lưu trữ dữ liệu

8. Viết Dockerfile và build docker images cho mỗi microservices.

9. Deploy toàn bộ hệ thống với Docker-compose

10. Deploy toàn bộ hệ thống với Rancher2

11. Test hiệu năng của hệ thống bằng Jmeter
