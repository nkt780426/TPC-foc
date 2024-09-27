# Ảnh "Copy of quy trình nghiệp vụy TPC.png"
TPC: thinh phat company. Là tập đoàn tài chính, phát triển về lĩnh vực cho vay.
Bài toán: Làm thế nào để phát hiện ra khách hàng tiềm năng đang muốn vay tiền và có khả năng trả nợ (gọi là leadgen). Dựa vào thông tin từ bên thứ 3 như mobifone cung cấp dữ liệu của khách hàng như số điện thoại, ... tính ra điểm tín dung, khả năng trả nợ, ...

1. Leadgen (Khách hàng tiềm năng) là số điện thoại của người muốn/có thể vay tiền. Làm thế nào để lấy được số điện thoại khách hàng tiềm năng ?
    Khách hàng vốn dĩ muốn vay tìm và tìm đến các tập đoàn có uy tín lớn để lại SĐT
    Lấy được SĐT từ 1 bên thứ 3 và cách hành vi vay tiền của họ từ đó suy luận họ có nhu cầu vay tiền và gửi tin nhắn mời gọi.
    ... (Bên họ lấy thế nào kệ họ)

2. CCA - Customer Care Agent (bộ phận chăm sóc khách hàng)
    Bản thân phòng ban CCA bao gồm rất nhiều team, mỗi team được đại diện bởi 1 team lead và làm việc với PM.
    Sau khi PM đã có danh sách các lead, họ sẽ sử dụng 1 phần mềm nào đó để tự động phân bổ lead đến các team lead (coi như KPI của họ).
    Team lead sau khi có danh sách các lead thực hiện phân bổ lead đến các agent (nhân viên) để họ gọi điện/sms đến khách hàng, giao tiếp với khách hàng.
    Nếu khách h àng đồng ý vay tiền thì gửi lại cho team lead duyệt, không duyệt thì agent giao tiếp lại.
    Sau khi thăm dò xong, nếu khách hàng quyết định vay tiền, CCA thực hiện "chốt khóa" chuyển lead này đi cho các phòng ban khác và lên lịch hẹn

3. Chốt khóa
    Là 1 team khác nhận các lead từ phòng ban CCA, hỏi lại khách hàng xem có chắc chắn vay tiền không.
    Kết quả sau cùng là danh sách các lead đã đồng ý tham gia vay tiền với team này. Các lead sẽ được phân bổ tự động bằng 1 phần mềm nào đó đến các Team leader FSA

4. FSA:
    Bản thân phòng ban này cũng bao gồm nhiều team và được quản lý bởi các team lead. Nhiệm vụ phòng ban này là liên lạc lại với khách hàng, yêu cầu khách hàng cung cấp các hồ sơ để vay tiền (ekyc).
    Team lead phân bổ lead đến các nhân viên (agent)
    Các agent liên lạc lại với khách hàng và tiếp nhận các giấy tờ của khách hàng.
    Kết quả sau cùng là 1 hồ sơ toàn diện về lead.

5. BO:
    Là 1 team có trách nhiệm đánh giá hồ sơ của khách hàng xem có đủ điều kiện vay tiền không.
    Nếu hồ sơ đạt thì cho khách hàng mở thẻ tín dụng và giải ngân số tiền mà khách hàng vay.

# File word "Copy of [CRM+-+TPC]+-+Tài+liệu+mô+tả+bảng+dữ+liệu+CRM+-+TPC"

Mô tả: Chứa tài liệu các bảng đữ liệu đang sử dụng cho báo cáo.