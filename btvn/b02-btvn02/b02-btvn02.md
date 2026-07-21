# IE203 - Buổi 02 - Bài Tập Về Nhà 02

## Yêu Cầu

Consider a company that sells electronic equipment (TVs. Laptops and accessories, home appliances, etc.) online.

Enumerate at least 10 processes or process groups in this company, distributed more or less evenly across management, core and support processes.

Specify a core value chain in this company.

Processes or Processes Groups:

- Management Processes
- Core Processes
- Support Processes

![](assets/b02-btvn02-groups.png)

Core Values Chain:
![](assets/core-values-chain.png)

## Bài Làm

### Danh Sách Các Bộ Phận

Tổng quan các bộ phận của một Công Ty Thương Mại Điện Tử, kinh doanh hàng điện tử, điện lạnh bao gồm:

| **STT** | **Tên**                                               | **STT** | **Tên**                                           |
| ------: | ----------------------------------------------------- | ------: | ------------------------------------------------- |
|       1 | Strategic Management: Quản lý chiến lược kinh doanh   |       8 | Digital Marketing: Tiếp thị & Quảng cáo           |
|       2 | Risk Management: Quản trị rủi ro                      |       9 | Order Processing: Xử lý đơn hàng                  |
|       3 | Performance Management: Đánh giá & Quản trị hiệu suất |      10 | Fulfillment & Delivery: Đóng gói & Vận chuyển     |
|       4 | Vendor Management: Quản lý đối tác & Nhà cung cấp     |      11 | Customer Service: Chăm sóc khách hàng & Bảo hành  |
|       5 | Human Resources: Quản trị nhân sự                     |      12 | Finance & Accounting: Quản lý tài chính & Kế toán |
|       6 | Direct Procurement: Tìm kiếm nguồn hàng & Mua sắm     |      13 | IT Operations: Vận hành & Bảo trì hệ thống IT     |
|       7 | Inventory & Warehouse Management: Quản lý kho bãi     |      14 | Indirect Procurement: Mua sắm gián tiếp           |

### Processes or Processes Groups

Có thể sắp xếp, phân bổ thành các nhóm quy trình chính yếu:

| **Management Processes** | **Core Processes**     | **Support Processes** |
| ------------------------ | ---------------------- | --------------------- |
| Strategic Management     | Direct Procuremen      | Human Resources       |
| Risk Management          | Inventory & Warehouse  | Finance & Accounting  |
| Vendor Management        | Digital Marketing      | IT Operations         |
|                          | Order Processing       | Indirect Procurement  |
|                          | Fulfillment & Delivery |                       |
|                          | Customer Service       |                       |

### Core Value Chain

Đối với một doanh nghiệp thương mại điện tử bán đồ điện tử, chuỗi giá trị nằm trong phần cốt lõi của Core Processes là hành trình từ lúc tiếp cận khách hàng cho đến khi hoàn tất giao dịch và hậu mãi, đây là một quy trình liên kết trực tiếp với khách hàng bên ngoài để tạo ra giá trị, như ví dụ dưới đây.

```mermaid
graph LR
  nodea("Tiếp thị & Bán hàng<br>Marketing & Sales")
  nodeb("Tiếp nhận đơn hàng<br>Receive Order")
  nodec("Xác duyệt đơn hàng<br>Approve Order")
  noded("Xử lý & Đóng gói<br>Fill Order")
  nodee("Giao hàng<br>Deliver Order")
  nodef("Hỗ trợ & Bảo hành<br>Customer Service")

nodea --> nodeb --> nodec --> noded --> nodee --> nodef
```
