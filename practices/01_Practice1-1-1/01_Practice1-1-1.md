# IE203 - 01_Practice1-1-1

## Yêu Cầu

- Xác định quy trình và các actor của công ty xây dựng.

Nguồn: [01_Practice1-1-1](01_Practice1-1-1.pdf)

## Ngữ Cảnh
### Equipment Rental Process

BuildIT is a construction company specialized in public works (roads, bridges, pipelines, tunnels, railroads, etc.). Within BuildIT, it often happens that engineers working at a construction site (called site engineers) **need a piece of equipment**, such as a truck, an excavator, a bulldozer, a water pump, etc.

BuildIT **owns very little equipment** and instead **it rents most of its equipment from specialized suppliers**.

The business process for **renting equipment goes as follows**. When a **site engineer** needs to rent a piece of equipment, they fill in a form called “Equipment Rental Request” and sends this request by e-mail to one of the clerks at the company’s depot. The **clerk** at the depot receives the request and, after consulting the catalogues of the equipment suppliers, selects the most cost-eﬀective equipment that complies with the request. Next, the clerk checks the availability of the selected equipment with the **supplier** via phone or e-mail. Sometimes the selected option is not available and the clerk has to select an alternative piece of equipment and check its availability with the corresponding supplier.

Once the clerk has found a suitable piece of equipment available for rental, they add the details of the selected equipment to the rental request. Every rental request has to be approved by a **works engineer**, who also works at the depot. In some cases, the works engineer rejects the equipment rental request. Some rejections lead to the cancellation of the request (no equipment is rented at all). Other rejections are resolved by replacing the selected equipment with another equipment – such as a cheaper piece of equipment or a more appropriate piece of equipment for the job. In this latter case, the clerk needs to perform another availability enquiry.

When a works engineer approves a rental request, the clerk sends a confirmation to the supplier. This confirmation includes a Purchase Order (PO) for renting the equipment. The PO is produced by BuildIT’s **financial information system** using information entered by the clerk. The clerk also records the engagement of the equipment in a spreadsheet that they maintain for the purpose of tracking all equipment rentals.

In the meantime, the site engineer may decide that the equipment is no longer needed. In this case, the engineer asks the clerk to cancel the request for renting the equipment.

In due time, the supplier delivers the rented equipment to the construction site. The **site engineer** then inspects the equipment. If everything is in order, they accept the engagement and the equipment is put into use. In some cases, the equipment is sent back because it does not comply with the requirements of the site engineer. In this case, the site engineer has to start the rental process all over again.

When the rental period expires, the supplier comes to pick up the equipment. Sometimes, the site engineer asks for an extension of the rental period by contacting the supplier via e-mail or phone 1-2 days before pick-up. The supplier may accept or reject this request.

A few days after the equipment is picked up, the equipment’s supplier sends an invoice to the clerk by e-mail. At this point, the clerk asks the site engineer to confirm that the equipment was indeed rented for the period indicated in the invoice. The clerk also checks if the rental prices indicated in the invoice are in accordance with those in the PO. After these checks, the clerk forwards the invoice to the **financial department** and the finance department eventually pays the invoice.

### Questions

1. What type of process is the above one: order-to-cash, procure-to-pay or issue-to-resolution?
2. Who are the actors in this process? Who is the customer?
3. What value does the process deliver to its customer(s)?
4. What are the tasks of this process?
5. What are the possible outcomes of this process?
6. Taking the perspective of the customer, what performance measures can be attached to this process?
7. What potential issues do you foresee this process might have? What information would you need to collect in order to analyze these issues?
8. What possible changes do you think could be made to this process in order to address the above issues? Which performance measure would these changes improve?

## Bài Làm

Yêu cầu ở trên là tương đương 2 câu hỏi trong phần Question của ngữ cảnh:

- What type of process is the above one: order-to-cash, procure-to-pay or issue-to-resolution?
- Who are the actors in this process?

### Quy Trình

Quy trình thuê thiết bị của công ty xây dựng BuildIT thuộc loại Procure-to-pay (Từ Mua Sắm đến Thanh Toán). Với các biểu hiện hoặc miêu tả như sau:

- Bắt đầu: Một Site Engineer (A) đang làm việc tại công trường, phát sinh nhu cầu thuê thiết bị. Site Engineer điền một mẫu gọi là Yêu Cầu Thuê Thiết Bị (Equipment Rental Request - ERR) và gửi tới nhân viên tại kho, gọi là clerk (B).
- Thực thi:
    - Nhân viên tại kho sẽ kiểm tra tính hợp lệ của mẫu yêu cầu, kiểm tra tình trạng sẵn hàng bằng cách liên hệ nhà cung cấp, Supplier (C), nếu không sẵn hàng, sẽ cần thay đổi các thông số hoặc thiết bị tương đương.
    - Nhân viên tại kho sẽ gửi yêu cầu ERR tới Works Engineer (D) để nhận xét duyệt, Works Engineer sẽ duyệt yêu cầu hoặc từ chối. Nếu bị từ chối, có thể diễn tiếp theo 2 tình huống: hủy hoàn toàn yêu cầu thuê thiết bị; thay đổi chi tiết thiết bị cần thuê, nhân viên tại kho B sẽ hành động tương ứng.
    - Nếu ERR được D duyệt, nhân viên tại kho B sẽ gửi xác nhận cung cấp (C), bao gồm một Đơn Mua Hàng (Purchase Order - PO), PO được tạo bởi Hệ Thống Tài Chính (Financial Information System - FIS) của BuildIT, có nghĩa các thông tin về yêu cầu thuê thiết bị này đã được lưu vào hệ thống. Nhân viên kho ghi chú lại các nội dung này vào file để theo dõi quá trình thuê thiết bị.
    - Nếu Site Engineer không muốn tiếp tục thuê thiết bị, sẽ cần yêu cầu cho nhân viên kho hủy ERR tương ứng.
    - Sau khi đã xác nhận, nhà cung cấp (C) sẽ gửi thiết bị tới công trường, khi đó A sẽ kiểm tra, xác nhận hoặc từ chối thiết bị, và nếu xác nhận thì thiết bị được đưa vào sử dụng. Nếu từ chối vì lý do nào đó, sai thiết bị, vv.. thì A cần lặp lại quy trình thuê thiết bị khác từ đầu.
    - Sau hạn thuê, nhà cung cấp sẽ lấy lại thiết bị, nếu A muốn gia hạn, có thể liên hệ trực tiếp nhà cung cấp trước 1-2 ngày để gửi yêu cầu gia hạn, nhà cung cấp sẽ có thể từ chối hoặc chấp nhận yêu cầu gia hạn.
- Kết thúc (Pay):
    - Sau khi thiết bị đã trả lại, có nghĩa yêu cầu thuê thiết bị đã hoàn thành, nhà cung cấp sẽ gửi hóa đơn (Invoice) tới nhân viên kho qua email. Khi đó nhân viên kho B sẽ cần A xác nhận về các thông tin liên quan đến quá trình thuê thiết bị, đồng thời B sẽ kiểm tra các thông tin về chi phí trong hóa đơn, đảm bảo chính xác với PO.
    - Cuối cùng, nhân viên kho chuyển hóa đơn tới phòng kết toán/tài chính (Financial Department - FD) và từ đó phòng kế toán sẽ thanh toán hóa đơn cho nhà cung cấp.

### Các Actor

Các tác nhân tham gia vào quy trình trên bao gồm 6 tác nhân như sau:

1. Site Engineer: là một cá nhân cụ thể, trực tiếp phát sinh nhu cầu, sử dụng dịch vụ/thiết bị, trực tiếp gửi yêu cầu, là điểm đầu của quy trình.
2. Clerk: là một cá nhân cụ thể, tiếp nhận yêu cầu và thực hiện các bước trung gian như một điểm giao tiếp giữa các tác nhân, cũng như đảm bảo quy trình diễn ra chính xác về thời gian, và chi phí.
3. Work Engineer: là một cá nhân cụ thể, có thẩm quyền phê duyệt hoặc từ chối yêu cầu thuê thiết bị, là một tác nhân quan trọng có thể ảnh hưởng/thay đổi chi tiết của quy trình.
4. Supplier: là một nhà cung cấp cụ thể, là một đối tác bên ngoài (external actor); chịu trách nhiệm cung cấp thiết bị, trả lời các câu hỏi/truy vấn về tình trạng, chi phí, v.v. liên quan đến thiết bị.
5. Financial Information System - FIS: là một hệ thống thông tin, không phải là một cá nhân cụ thể; cung cấp khả năng lưu trữ thông tin, xuất đơn hàng (PO) dựa trên các thông tin mà Clerk nhập vào.
6. Financial Department - FD: là một phòng ban, chịu trách nhiệm cuối của quy trình; nhận hóa đơn đã được xác nhận từ Clerk và thanh toán cho nhà cung cấp. Hoàn thành quy trình.
