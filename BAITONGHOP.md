Mình làm sẵn bài giải đầy đủ theo 4 phần để bạn sao chép vào StackEdit. Bài gồm `README.md`, Prompt hỏi AI về API, tài liệu `api_giai_thich.md` và phần sửa lỗi cú pháp.

# **PHẦN 1\. KHUNG SƯỜN README**

Tạo file `README.md` rồi dán đoạn Markdown sau:

*   
* \# 🎓 SmartCampus  
*   
* \*\*SmartCampus\*\* là ứng dụng di động hỗ trợ sinh viên PTIT \*tra cứu lịch học\*, xem phòng học trống và nhận thông báo mới nhất từ nhà trường.  
*   
* \#\# ✨ Tính năng đã hoàn thành  
*   
* \- Tra cứu lịch học theo mã sinh viên.  
*   \- Giúp sinh viên tra cứu lịch học của mình.  
* \- Xem danh sách phòng trống theo tòa nhà.  
*   \- Hỗ trợ tìm phòng học đang trống.  
*   
* \#\# 🔗 Liên kết  
*   
* \[Trang chủ CLB Lập trình\](https\://clblaptrinh.ptit.edu.vn)  
*   
* \!\[Logo SmartCampus\](https\://placehold.co/300x120/2563eb/ffffff?text=SmartCampus)  
*   
* \> ⚠️ Dự án đang trong giai đoạn phát triển, chưa sử dụng cho mục đích chính thức.  
*   
* \---  
*   
* \#\# 🚀 Hướng dẫn cài đặt  
*   
* \#\#\# Các lệnh cài đặt  
*   
* \`\`\`bash  
* git clone https\://github.com/clb-lap-trinh/smartcampus.git  
* npm install  
* npm start  
* \`\`\`  
*   
* \#\#\# 📋 Tiến độ phát triển  
*   
* \- \[x\] Tra cứu lịch học theo mã sinh viên  
* \- \[x\] Xem danh sách phòng trống theo tòa nhà  
* \- \[ \] Thông báo đẩy (push notification)  
* \- \[ \] Đăng nhập bằng tài khoản trường  
*   
* \#\#\# 📦 Thư viện sử dụng  
*   
* | Thư viện | Phiên bản | Mục đích |  
* |:---|:---:|:---|  
* | React Native | 0.74 | Xây giao diện đa nền tảng iOS/Android |  
* | Axios | 1.6 | Gọi API lấy dữ liệu lịch học |  
*   
* \#\#\# Ghi chú cú pháp Markdown  
*   
* Để hiển thị nguyên văn dấu sao \\\*, hãy đặt dấu \`\\\` phía trước nó.


Lưu ý: Logo trên sử dụng URL ảnh minh họa. Bạn có thể thay bằng URL logo thật của dự án khi có.

# **PHẦN 2\. KIỂM TRA CÁC CÚ PHÁP**

README ở trên đã sử dụng đầy đủ các cú pháp bắt buộc:

| Cú pháp | Ví dụ trong bài |
| ----- | ----- |
| Heading H1 | `# 🎓 SmartCampus` |
| In đậm | `**SmartCampus**` |
| In nghiêng | `*tra cứu lịch học*` |
| List lồng nhau | Hai mục ghi chú thụt vào 2 dấu cách |
| Hyperlink | `[Trang chủ CLB Lập trình](...)` |
| Image | `![Logo SmartCampus](...)` |
| Blockquote | `> ⚠️ Dự án...` |
| Horizontal Rule | `---` |
| Inline Code | `npm install` |
| Code Block | Khối `bash` có 3 lệnh |
| Table | Bảng thư viện có cột căn giữa |
| Task List | `- [x]` và `- [ ]` |
| Emoji shortcode | `:rocket:` trong tiêu đề |
| Escape | `\*` |

# **PHẦN 3\. HỎI AI VÀ LƯU TÀI LIỆU**

## **1\. Prompt theo công thức 3 phần**

Sao chép Prompt sau vào ChatGPT hoặc Gemini:

## **Tôi là ai / Bối cảnh**

Tôi là sinh viên năm nhất PTIT, tham gia CLB Lập trình và đang thực hiện dự án SmartCampus. Tôi chưa có nhiều kiến thức về lập trình.

## **Chủ đề / Nội dung cần xử lý**

Giải thích thuật ngữ API (Application Programming Interface).

## **Yêu cầu**

* Giải thích bằng ngôn ngữ đời thường, dễ hiểu.  
* So sánh API với một vật dụng hoặc hoạt động quen thuộc trong cuộc sống.  
* Cho một ví dụ cụ thể liên quan đến ứng dụng SmartCampus.  
* Trình bày ngắn gọn trong khoảng 100-150 từ.  
* Chia nội dung thành các tiêu đề nhỏ và dùng chữ in đậm cho từ khóa quan trọng.

  ## **Không cần**

* Không sử dụng thuật ngữ chuyên ngành phức tạp.  
* Không đưa ra đoạn code lập trình dài.  
* Không giải thích các khái niệm khác ngoài API.

  ## **2\. Câu trả lời mẫu của AI về API**

Đây là câu trả lời mẫu để bạn đưa vào file `api_giai_thich.md`.

# **API là gì?**

## **1\. Khái niệm**

**API** là viết tắt của *Application Programming Interface*, nghĩa là giao diện lập trình ứng dụng. API giúp hai phần mềm trao đổi dữ liệu và yêu cầu với nhau.

## **2\. Ví dụ đời thường**

Hãy tưởng tượng API giống như **nhân viên phục vụ trong nhà hàng**. Bạn gọi món, nhân viên chuyển yêu cầu đến nhà bếp rồi mang kết quả về cho bạn. Bạn không cần trực tiếp vào bếp để lấy món ăn.

## **3\. Ví dụ trong SmartCampus**

Khi sinh viên mở SmartCampus để xem lịch học, ứng dụng có thể gửi yêu cầu qua API đến hệ thống của trường. Hệ thống trả về dữ liệu lịch học để ứng dụng hiển thị cho sinh viên.

**Tóm lại:** API là cầu nối giúp các phần mềm giao tiếp và trao đổi dữ liệu với nhau.

## **3\. Tóm tắt theo chiến lược đọc 3 bước**

* Scan Heading: Xác định ba phần: khái niệm, ví dụ đời thường và ví dụ SmartCampus.  
* Đọc chữ đậm: Chú ý các từ khóa API, nhân viên phục vụ và cầu nối.  
* Xem Bullet List: Đối chiếu các yêu cầu chính trong Prompt với câu trả lời.

Tóm tắt bằng lời của mình (3 câu):

API là cầu nối giúp các phần mềm gửi yêu cầu và trao đổi dữ liệu với nhau. Có thể hình dung API như nhân viên phục vụ chuyển yêu cầu giữa khách hàng và nhà bếp. Trong SmartCampus, API giúp ứng dụng lấy dữ liệu lịch học từ hệ thống của trường để hiển thị cho sinh viên.

## **4\. Quy trình 4 bước lưu file `.md`**

1. Mở [StackEdit](https://stackedit.io/) và tạo tài liệu Markdown mới.  
2. Sao chép toàn bộ câu trả lời về API ở trên vào trình soạn thảo.  
3. Chọn phần xem trước để kiểm tra tiêu đề, chữ đậm và nội dung.  
4. Lưu hoặc xuất tài liệu với tên `api_giai_thich.md`.

   # **PHẦN 4\. BẪY CÚ PHÁP**

   ## **1\. Chỉ ra chính xác 2 lỗi**

Lỗi 1: Bảng thiếu dòng phân cách tiêu đề.

Đoạn ban đầu chưa có dòng `|---|---|` ngay dưới hàng tiêu đề, nên GitHub không nhận diện đúng cấu trúc bảng Markdown.

Lỗi 2: Task List thiếu dấu cách sau dấu gạch ngang.

Đoạn `-[x]` và `-[ ]` sai cú pháp. Phải viết `- [x]` và `- [ ]`, có dấu cách giữa `-` và dấu ngoặc vuông.

## **2\. Đoạn Markdown đã sửa đúng**

*   
* | Tính năng | Trạng thái |  
* |---|---|  
* | Tra cứu lịch học | Xong |  
* | Push notification | Đang làm |  
*   
* \- \[x\] Tra cứu lịch học  
* \- \[ \] Push notification


Kết quả render:

| Tính năng | Trạng thái |
| ----- | ----- |
| Tra cứu lịch học | Xong |
| Push notification | Đang làm |

*   
  Tra cứu lịch học  
* Push notification

