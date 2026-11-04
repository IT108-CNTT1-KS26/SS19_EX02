## 1. Phân tích rủi ro kỹ thuật "Đuôi file kép" (Double Extension)
- Tệp `Job_Offer.pdf.exe`: Windows chỉ nhận đuôi mở rộng cuối cùng `.exe` làm định dạng thực thi nhị phân. Chuỗi `.pdf` ở giữa chỉ là tên tệp nhằm đánh lừa thị giác.
- Cơ chế ẩn đuôi mặc định (*Hide extensions for known file types*) của Windows khiến tệp hiển thị thành `Job_Offer.pdf`.
- Tin tặc đổi icon thành biểu tượng Adobe Acrobat để nạn nhân nhấp đúp chạy mã độc (Infostealer, Ransomware, Keylogger).

## 2. Bẫy tắt Antivirus / Windows Defender
- Là đòn tấn công tâm lý kỹ nghệ xã hội (Social Engineering).
- Mục đích: Vô hiệu hóa hàng rào bảo vệ theo thời gian thực (Real-time Protection) và Heuristic Analysis để mã độc thâm nhập mà không bị chặn.

## 3. Công cụ kiểm tra an toàn
- **VirusTotal (https://www.virustotal.com):** Quét đối chiếu qua 70+ engine diệt virus.
- **Hộp cát trực tuyến (ANY.RUN, Hybrid Analysis):** Chạy thử nghiệm trong máy ảo độc lập để theo dõi hành vi tệp.
