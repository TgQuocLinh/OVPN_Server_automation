# OVPN_Server_automation

Các bước setup:
1. Cài đặt OpenVPN trên phía Server.
2. Tạo các user cho các client.
3. Cài đặt OpenVPN trên phía client.
4. Phát các file config tương ứng tới các client và kết nối vpn tới sever với các file config đã nhận.

* Script cài OpenVPN trên server đã được sửa để chạy được thông qua playbook (hoặc có thể chạy thủ công với 1 lệnh duy nhất).
* Ở đây chỉ test kết nối trên 1 client, nếu có nhiều client thì phải có các playbook riêng cho từng host, vì mỗi client phải có một file config riêng (tức là phải có một user riêng) để kết nối vpn, nếu dùng chung 1 file (chung 1 user) sẽ bị trùng ip (đã test).
