# 🏢 Enterprise Multi-Site Network Simulation

## 📝 Overview
Dự án mô phỏng hạ tầng mạng cho doanh nghiệp gồm 2 tòa nhà (Toà A & Toà B) trên Cisco Packet Tracer. Hệ thống tập trung vào tính ổn định cao (High Availability), bảo mật và quản lý tập trung.

## 🛠 Technical Features
 **High Availability:** Triển khai **HSRP** giữa 2 Switch Core để dự phòng Gateway. Nếu một Core lỗi, mạng vẫn chạy bình thường.
**STP Optimization:** Cấu hình **PVST+**, chủ động bầu chọn **Root Bridge** tại lớp Core để tránh nghẽn cổ chai (Bottlenecks).
**Inter-VLAN Routing:** Sử dụng **SVI** trên Switch Layer 3 giúp các phòng ban giao tiếp với nhau ở tốc độ cao (Wire-speed).
**Security:** Kích hoạt **BPDU Guard** và **Port Security** tại các Switch Access để chống tấn công lớp 2.
**Services:** Tích hợp DHCP Server, DNS và Web nội bộ.
## 🖼 Topology Diagram
<img width="1496" height="551" alt="Image" src="https://github.com/user-attachments/assets/5b42c26d-5feb-4ccf-ade3-83b0d975f6d9" />
