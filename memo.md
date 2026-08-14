# Memo Teardown — ChatGPT

**Nhóm:** K4-Lab16 · **Thành viên:** Vũ Nguyễn Bảo Sơn, Trần Chí Hiển, Hồ Lương An

**Vì sao chọn sản phẩm này:** ChatGPT là sản phẩm AI tiêu biểu nhất định hình lại toàn bộ ngành công nghệ và thói quen làm việc của hàng trăm triệu người dùng trên toàn thế giới, sở hữu tốc độ tăng trưởng và chu kỳ dịch chuyển sản phẩm điển hình nhất để phân tích Product Sense.

---

## §1. Timeline các cập nhật lớn

| Thời điểm | Cập nhật | Context lúc đó | Cốt lõi chiến lược | Link dẫn chứng |
| :--- | :--- | :--- | :--- | :--- |
| **11/2022** | OpenAI ra mắt ChatGPT (dựa trên GPT-3.5) miễn phí. | Các mô hình LLM trước đó chủ yếu dưới dạng API cho dev/researcher, chưa có giao diện thân thiện. AI tạo sinh chưa phổ cập đại chúng. | **x10 Trải nghiệm & Vòng lặp học:** Biến giao diện từ API khô khan thành cửa sổ chat dễ dùng gấp 10 lần. Mở miễn phí cho mọi người để đổi lấy lượng dữ liệu khổng lồ giúp AI tự học và thông minh hơn mỗi ngày. | [OpenAI Blog](https://openai.com/index/chatgpt/) |
| **03/2023** | Ra mắt GPT-4 và gói trả phí ChatGPT Plus. | Lượng user tăng bùng nổ gây sập server liên tục. Các đối thủ rục rịch ra mắt. OpenAI cần mô hình mạnh hơn và thu phí để bù đắp chi phí. | **Định nghĩa lại "Tốt" & Hào cản công nghệ (Tech Moat):** Nâng cấp chuẩn AI "tốt" (logic hơn, bớt bịa chuyện). Dùng công nghệ lõi mạnh mẽ làm hào cản để các đối thủ đi sau không thể theo kịp. | [OpenAI Blog](https://openai.com/index/gpt-4-research/) |
| **05/2023** | Tích hợp Web Browsing và Plugins cho người dùng Plus. | Điểm yếu lớn nhất của ChatGPT lúc bấy giờ là bị giới hạn dữ liệu (cut-off 2021) và không thể thao tác với bên thứ ba. | **Hào cản từ Hệ sinh thái (Ecosystem Moat):** Không chỉ là chatbot, mà biến thành một nền tảng (giống App Store). Bằng cách kết nối với các ứng dụng người dùng đang xài, ChatGPT giữ chân họ chặt hơn. | [OpenAI Blog](https://openai.com/index/chatgpt-plugins/) |
| **08/2023** | Ra mắt ChatGPT Enterprise (Bảo mật cấp doanh nghiệp). | Các tập đoàn lớn cấm nhân viên dùng ChatGPT vì lo ngại rò rỉ dữ liệu nội bộ. Microsoft đang đẩy mạnh Copilot. | **Đánh sâu vào ngách (Vertical AI) & Hào cản B2B:** Giải quyết nỗi đau lớn nhất của doanh nghiệp là "bảo mật". Qua đó, tạo ra dòng tiền khổng lồ và một nhóm khách hàng trung thành, khó rời đi. | [OpenAI Blog](https://openai.com/index/introducing-chatgpt-enterprise/) |
| **09/2023** | Cập nhật Đa phương thức: Nghe (Voice) và Nhìn (Image). | Cuộc đua LLM không chỉ dừng ở Text. Google chuẩn bị tung ra siêu mô hình Gemini đa phương thức tự nhiên. | **x10 Trải nghiệm & Mở rộng định nghĩa "Tốt":** Một AI "tốt" không chỉ biết gõ phím, mà phải biết nghe, nhìn và nói chuyện. Việc này nâng cấp trải nghiệm giao tiếp tự nhiên hơn gấp 10 lần. | [OpenAI Blog](https://openai.com/index/chatgpt-can-now-see-hear-and-speak/) |
| **01/2024** | Ra mắt tự tạo GPTs cá nhân và GPT Store. | Nhiều startup ra đời kiếm tiền chỉ bằng cách làm "vỏ bọc" (wrapper) quanh API OpenAI. Nhu cầu cá nhân hóa prompt cực cao. | **Hấp thụ Wrapper & Hào cản Mạng lưới:** Thay vì để bên khác làm "vỏ bọc" kiếm tiền, OpenAI tự làm luôn. Người dùng càng đông tự tạo GPTs -> kho ứng dụng càng lớn -> càng khó bỏ ChatGPT. | [OpenAI Blog](https://openai.com/index/introducing-the-gpt-store/) |
| **05/2024** | Ra mắt GPT-4o xử lý realtime và miễn phí lại cho mọi user. | Anthropic ra mắt Claude 3 vượt mặt GPT-4. Google I/O sắp diễn ra. OpenAI cần một cú hích phủ đầu để giữ vị thế độc tôn. | **x10 Tốc độ & Vòng lặp học Đa phương thức:** Đưa mô hình xịn nhất (phản hồi siêu tốc) cho người dùng miễn phí để nhanh chóng gom kho dữ liệu âm thanh/hình ảnh khổng lồ, tiếp tục train AI mạnh hơn. | [OpenAI Blog](https://openai.com/index/hello-gpt-4o/) |
| **09/2024** | Ra mắt dòng mô hình o1 (Reasoning) có khả năng "suy nghĩ". | Các mô hình LLM truyền thống chạm trần trong các bài toán suy luận phức tạp. Thị trường cần AI tư duy sâu, lập luận từng bước. | **Định nghĩa lại "Sự thông minh":** Thay đổi cách AI hoạt động: Không cần trả lời ngay (phản xạ), mà biết dành thời gian để suy nghĩ, lập kế hoạch và tự sửa lỗi ngầm trước khi đưa ra kết quả. | [OpenAI Blog](https://openai.com/index/introducing-openai-o1-preview/) |

**Vì sao chọn những mốc này:**

- Đây là những cột mốc chính trong sự phát triển của Open AI trong kể từ khi ra mắt ChatGpt cho tới bây giờ. Việc ra mắt Chatgpt Enterprise cho thấy công ty đang scale ra tệp khách hàng B2B, giải quyết được vấn đề về bảo mật thông tin của các công ty. 

- Những cột mốc này cho thấy Open AI nắm bắt được đúng **nhu cầu và nỗi đau** của người dùng trên thị trường. Nhu cầu cải thiện thời gian và chất lượng công việc.

---

## §2. Tệp user & JTBD

| Tiêu chí | Early Adopters (Những lập trình viên - cuối 2022) | Tệp người dùng hiện tại (Người dùng đại chúng - Hiện nay) |
| :--- | :--- | :--- |
| **Đặc điểm** | Frontend dev ở các startup nhỏ, người làm nội dung (copywriter), học sinh/sinh viên mê công nghệ, hay lướt Twitter AI, Reddit, Hacker News. | Nhân viên văn phòng (marketing, HR, bán hàng), giáo viên, học sinh sinh viên, quản lý doanh nghiệp, người dùng phổ thông. |
| **JTBD chính** | - **Lập trình:** Viết nhanh đoạn code mẫu hoặc tìm lỗi code để không phải lướt vài trang StackOverflow.<br>- **Viết lách:** Lên ý tưởng và viết nháp bài đăng mạng xã hội, email chào hàng để đỡ tốn thời gian ngồi nghĩ từ đầu. | - **Soạn văn bản:** Soạn email, làm báo cáo hoặc sửa câu từ cho lịch sự, đúng chuẩn công sở.<br>- **Xử lý tài liệu:** Tóm tắt tài liệu dài, dịch văn bản hoặc biên bản cuộc họp.<br>- **Kiểm tra code:** Đã có AI code cho nên việc giờ chuyển sang kiểm tra. |
| **Trước đó họ làm bằng cách nào** | Tra Google, đọc tài liệu API, tìm bài hướng dẫn trên StackOverflow/GitHub; tự ngồi vò đầu bứt tai nghĩ ý tưởng bài viết. | Tự gõ email thủ công (mất nhiều thời gian sửa câu từ), dùng Google Dịch (dịch thô), đọc từng trang tài liệu dài, lập trình, viết code thủ công. |

**Dịch chuyển tệp:**  
Cột mốc GPT-4 (03/2023) tăng độ chính xác và ứng dụng di động iOS/Android (05/2023) giúp AI bớt sai sót và dễ tiếp cận hơn trên điện thoại, tạo hiệu ứng lan truyền xã hội từ nhóm công nghệ sang giới văn phòng đại chúng.

**Switching cost (Map 4 forces):**
- **Push từ hiện tại:** Google Search nhiễu quảng cáo, thông tin lan man; công việc văn phòng lặp đi lặp lại tốn thời gian.
- **Pull từ ChatGPT:** Trả lời trực tiếp, chat tự nhiên như người thật, đa năng (code, dịch, viết văn).
- **Anxiety (Lo ngại):** Sợ AI trả lời sai sự thật; sợ lộ thông tin nội bộ doanh nghiệp; sợ phụ thuộc vào AI.
- **Inertia (Thói quen cũ):** Thói quen tra Google từ khóa ngắn; chưa quen viết prompt hiệu quả; quy trình công ty chưa chính thức cho phép.

---

## §3. Ba dự đoán hướng đi (6–12 tháng tới)

**Dự đoán 1** *(loại: mở rộng tính năng — Chuyển từ Chat sang Autonomous AI Agent)*  
- **Dự đoán:** OpenAI sẽ nâng cấp ChatGPT từ một khung chat thụ động thành một **AI Agent tự vận hành (Autonomous Agent)** có khả năng tự thao tác trình duyệt, gửi email, thực thi quy trình công việc đa bước trên máy tính (Computer Use) mà không cần người dùng can thiệp từng câu lệnh.  
- **Lập luận:**  
  - *Dẫn từ §1 (Timeline):* Sự tiến hóa công nghệ của ChatGPT đi từ lướt web tra cứu thông tin (05/2023), ra mắt GPTs/Store (01/2024) đến mô hình o1 biết lập luận suy nghĩ (09/2024). Khi bài toán "tư duy & suy luận" đã được giải quyết, bước đi tất yếu tiếp theo là "hành động tự động" (Action-oriented AI).  
  - *Dẫn từ §2 (Tệp User & JTBD):* Tệp người dùng hiện tại (nhân viên văn phòng, doanh nghiệp) có JTBD là "tiết kiệm thời gian xử lý công việc lặp đi lặp lại". Lực cản hiện tại (Inertia) là họ vẫn phải copy-paste kết quả từ ChatGPT sang các phần mềm khác thủ công. Tính năng AI Agent sẽ giải quyết triệt để điểm nghẽn này.  

**Dự đoán 2** *(loại: mở rộng segment & mô hình kiếm tiền — Vertical AI cho doanh nghiệp vừa và nhỏ)*  
- **Dự đoán:** OpenAI sẽ tung ra các gói **"Vertical ChatGPT" chuyên sâu cho từng ngành** (Luật, Y tế, Tài chính, Giáo dục) với chính sách bảo mật dữ liệu tuyệt đối và mô hình thu phí linh hoạt theo mức độ sử dụng (Usage-based) dành riêng cho tệp doanh nghiệp vừa và nhỏ (SMBs).  
- **Lập luận:**  
  - *Dẫn từ §1 (Timeline):* Mốc ra mắt ChatGPT Enterprise (08/2023) cho thấy khao khát thâm nhập thị trường doanh nghiệp. Tuy nhiên, các startup làm AI ngách (như Harvey trong ngành luật, Klarna trong CSKH) đang dần ăn mất thị phần ở từng lĩnh vực cụ thể. OpenAI bắt buộc phải mở rộng gói chuyên biệt để giữ thế độc tôn.  
  - *Dẫn từ §2 (Tệp User & JTBD):* Ở §2, hai lực cản lớn nhất níu giữ doanh nghiệp là **Sự lo ngại (Anxiety)** về rò rỉ dữ liệu nội bộ và độ chính xác của AI. Việc đóng gói giải pháp chuyên ngành kèm cam kết bảo mật pháp lý sẽ xóa bỏ rào cản này, biến các doanh nghiệp truyền thống thành tệp khách hàng trả phí ổn định.  

**Dự đoán 3** *(loại: đe dọa từ Big Tech & phản ứng chiến lược — Trợ lý giọng nói & tích hợp sâu vào hệ điều hành)*  
- **Dự đoán:** Trước sức ép Big Tech tích hợp AI trực tiếp vào hệ điều hành (Apple Intelligence, Google Gemini trên Android/Chrome), OpenAI sẽ biến ChatGPT thành một **Trợ lý giọng nói thời gian thực (Voice Assistant)** chạy ngầm trên Desktop và Mobile, cạnh tranh sòng phẳng về mặt trải nghiệm tương tác với Siri và Google Assistant.  
- **Lập luận:**  
  - *Dẫn từ §1 (Timeline):* Mốc ra mắt GPT-4o (05/2024) với khả năng xử lý âm thanh/hình ảnh realtime miễn phí cho toàn bộ user là bước đi phủ đầu cực kỳ chiến lược. OpenAI chấp nhận tốn chi phí hạ tầng để phủ rộng tính năng giọng nói trước khi Apple và Google kịp hoàn thiện AI tích hợp sẵn trên thiết bị.  
  - *Dẫn từ §2 (Tệp User & JTBD):* Phân tích 4 Forces ở §2 chỉ ra rằng người dùng rất dễ bị kéo về các công cụ mặc định trên hệ điều hành do **Lực cản thói quen (Inertia)**. Nếu ChatGPT không có một "Lực kéo (Pull)" đủ mạnh là khả năng giao tiếp giọng nói siêu tự nhiên mọi lúc mọi nơi, họ sẽ dần mất tệp người dùng phổ thông vào tay Big Tech.  

---

## §4. AI Log

| Việc | AI làm hay nhóm làm? | Nhóm kiểm chứng/phán đoán lại thế nào? |
| :--- | :--- | :--- |
| Tra cứu & tổng hợp 8 cột mốc timeline sản phẩm ChatGPT | AI làm nháp | Nhóm đối chiếu lại với OpenAI Official Blog, lọc bỏ các bản vá lỗi nhỏ và chỉ giữ lại 8 bước ngoặt chiến lược có tác động lớn. |
| Phân tích tệp user (Early Adopters vs Hiện tại) & 4 Forces | Nhóm thảo luận & định hình | AI gợi ý cấu trúc bảng 4 forces, nhóm điều chỉnh ngôn ngữ thực tế, gần gũi với môi trường người dùng Việt Nam. |
| Xây dựng 3 dự đoán chiến lược (Step 3) | Nhóm phán đoán cốt lõi | Nhóm đưa ra định hướng 3 dự đoán (AI Agent, Vertical AI, Voice OS integration), AI hỗ trợ diễn đạt thành lập luận chặt chẽ trỏ về §1 và §2. |
| Biên tập & kiểm tra hoàn thiện Memo | Cả nhóm & AI | Đọc rà soát lại toàn bộ văn bản để đảm bảo không bị văn phong AI gượng ép, kiểm tra tính logic giữa các phần. |
