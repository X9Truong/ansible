### 1. Ansible

*Ansible là một platform opensource, nghĩa là bạn có thể viết thêm hay chỉnh sửa tuỳ ý. Ansible khá đơn giản để sử dụng. Nôm na bạn có thể hình dung là chỉ việc khai báo địa chỉ server và những điều muốn làm với server đó vào ansible, rồi sau đó chỉ cần chạy script bạn vừa viết trên và ngồi uống trà chờ hoàn thành.*

### 2. Đặc điểm

* Ansible miễn phí và là 1 opensource

* Ansible sử dụng phương thức ssh

* Việc cài đặt không tốn nhiều tài nguyên

* Được phát triển bởi ngôn ngữ python. Nên nếu bạn muốn tạo thêm module thì cũng sử dụng bằng python

* Khá nhẹ và dễ setup

* Các sciprt thường được dùng định dạng YAML

* Ansible có một cộng đồng tương tác lớn

### 3. Thành phần

* Playbooks - Là nơi bạn sẽ khai báo kịch bản chạy cho server

* Tasks - Là những công việc nhỏ trong cuốn sổ Playbooks trên

* Inventory - Khai báo địa chỉ server cần được setup

* Modules - Những chức năng hỗ trợ cho việc thực thi tasks dễ và đang dạng





Note:
```
ssh-keygen
ssh-copy-id root@192.168.100.99
```


https://docs.ansible.com/ansible/latest/user_guide/vault.html