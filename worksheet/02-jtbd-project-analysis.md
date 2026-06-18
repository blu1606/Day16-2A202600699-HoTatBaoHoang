---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** EduGap (Adaptive Socratic Tutor)  

> Đây là **file duy nhất** của Lab 2.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải brainstorm thêm thật nhiều tính năng AI.
Mục tiêu là:

1. **xác định người dùng thực sự đang cố hoàn thành job gì**
2. **hiểu họ đang dùng giải pháp nào để hoàn thành job đó hôm nay**
3. **chỉ ra AI nên chen vào đúng bước nào trong workflow**
4. **viết ra product hypothesis và assumption còn phải validate**

Quy tắc xuyên suốt: **không rõ job thì đừng bàn feature.**

---

## Cần mở song song 2 thứ

1. **File này** — để điền trực tiếp
2. **`Strategyn_JTBD_Playbook.pdf`** — giảng viên gửi kèm

### Cách dùng playbook cho đúng

Bạn **không cần đọc hết 48 trang**.  
Trong bài này, playbook chủ yếu dùng để tra 4 thứ:

1. **Cách nhìn thị trường qua JTBD lens**
2. **`Job executor` là ai**
3. **Cách viết `job statement`: `verb + object + contextual clarifier`**
4. **8 bước của `job map`**:
   `define -> locate -> prepare -> confirm -> execute -> monitor -> modify -> conclude`

### 2 chương nên mở nhiều nhất

- **Chapter 2 — Define Your Market**
- **Chapter 3 — Build Your Job Map**

> Dùng playbook để **tra framework và ví dụ**.  
> Dùng file này để **làm bài và chốt output**.

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 6 phần trong chính file này:

1. **`Project slice` + market context**
2. **`Job executor` + `core JTBD`**
3. **3 `job stories`**
4. **`JTBD lite map` + pain points**
5. **`AI leverage point` + `product hypothesis`**
6. **`Assumptions to validate` + verdict cuối sau thảo luận**

Nếu thiếu một trong sáu phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (25 phút)

```text
3'  Chốt 1 lát cắt cụ thể của dự án
7'  Viết market context + job executor + core JTBD
6'  Viết 3 job stories + current alternatives
6'  Điền JTBD lite map + AI leverage point + hypothesis
3'  Share trong bàn và sửa version cuối
```

> Nếu dự án làm theo nhóm, cả nhóm có thể thảo luận chung.  
> Nhưng file này vẫn nên có **version chốt rõ ràng** của người nộp.

---

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

Phần lớn dự án nhóm viết quá rộng ở bước này, rồi sau đó mọi thứ mơ hồ theo.

### Khoanh đúng 1 lát cắt theo 4 điểm

- [x] **1 nhóm người dùng chính**
- [x] **1 hoàn cảnh / tình huống rõ**
- [x] **1 job cốt lõi**
- [x] **1 workflow đủ cụ thể để vẽ ra được**

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:** EduGap — Hệ thống gia sư học thuật cá nhân hóa 24/7 tích hợp Socratic RAG và Adaptive Quiz.
- **Lát cắt tôi chọn để phân tích hôm nay là:** Học viên khoá AI Thực chiến 20K tự ôn tập kiến thức và thực hành sau buổi học để lấp đầy lỗ hổng concept (Concept Gap).
- **Vì sao tôi chọn lát cắt này:**  
  > Đây là nhóm người dùng cốt lõi có tần suất sử dụng hàng ngày và gặp khó khăn ngay lập tức (immediate pain) khi phải tiếp thu lượng kiến thức rất lớn trong thời gian ngắn mà không có người kèm cặp sát sao.

### Viết quá rộng vs viết sắc hơn

| Viết quá rộng | Viết sắc hơn |
|---|---|
| Giúp SME dùng AI để marketing | Giúp chủ shop online phản hồi câu hỏi trước mua hàng nhanh và nhất quán trong giờ cao điểm |
| Dùng AI để làm slide | Tạo bản nháp deck nội bộ mạch lạc cho buổi họp gấp trong thời gian rất ngắn |
| AI cho tuyển dụng | Giúp recruiter sàng lọc CV đầu vào nhanh hơn trước vòng gọi sơ bộ |

> Nếu bạn không mô tả được **một hoàn cảnh cụ thể**, khả năng cao bạn đang viết quá rộng.

---

## Bước 1 — Viết `Project Snapshot`

### Tóm tắt dự án trong 3 dòng

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > Học viên học các khóa học công nghệ chuyên sâu (tech intensive) bị ngợp trước lượng kiến thức lớn, không tự chẩn đoán được lỗ hổng kiến thức của bản thân và dễ lạm dụng AI để chép code/đáp án thay vì tự suy luận.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Học viên các khóa học AI thực chiến 20K (ví dụ: học viên khóa AI20K Cohort 2).

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Xem lại video record buổi học, đọc slide bài giảng, tự đặt câu hỏi cho các chatbot AI đại trà (như ChatGPT, Claude).

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > Học viên các khóa học AI/Tech chuyên sâu và các Mentor/Giảng viên quản lý lớp học.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Sau mỗi buổi học lý thuyết phức tạp, khi học viên tự làm bài tập/lab cá nhân vào buổi tối hoặc cuối tuần mà không có trợ giúp trực tiếp.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > Tự xem lại slide/video, hỏi bạn học trong nhóm chat, hỏi chatbot AI miễn phí.

4. **Vì sao đây là thời điểm đáng giải?**  
   > Nhu cầu học AI tăng vọt nhưng tỷ lệ bỏ cuộc cao vì kiến thức khó; đồng thời việc lạm dụng LLM chép code làm mất phản xạ tự học và tư duy của học viên.

### Tóm tắt market context trong 3-4 dòng

> Trong các khóa học công nghệ chuyên sâu như AI20K, học viên thường bị quá tải bởi lượng kiến thức học thuật dày đặc (ví dụ: Backpropagation, Chain Rule). Do thiếu công cụ tự luyện tập vừa sức và thói quen hỏi AI đại trà để lấy code ăn liền, học viên không thực sự hiểu bản chất khái niệm và Mentor cũng không nắm bắt được lỗ hổng kiến thức thực tế của lớp để kịp thời điều chỉnh bài giảng.

---

## Bước 3 — Xác định `Job Executor`

`Job executor` là người **trực tiếp dùng một giải pháp để hoàn thành job**.

### Đừng nhầm với:

- người mua tiền nhưng không trực tiếp làm job
- người ảnh hưởng quyết định
- cả một công ty hay một phòng ban quá rộng

### Gợi ý viết cho đúng

- Sai hoặc quá rộng: `SME`, `doanh nghiệp`, `thị trường`
- Tốt hơn: `chủ shop online`, `nhân viên CSKH`, `recruiter`, `sales ops manager`

### Điền

- **Job executor của dự án này là:** Học viên khoá học AI thực chiến (ví dụ: AI20K Cohort 2).
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Họ là người trực tiếp đối mặt với áp lực học tập hàng ngày, cần tự ôn bài, làm lab và vượt qua các bài kiểm tra của khóa học để hoàn thành mục tiêu học tập.

---

## Bước 4 — Viết `Core JTBD`

`Core JTBD` là công việc cốt lõi người dùng đang cố hoàn thành.

### Công thức gợi ý

```text
[verb] + [object] + [contextual clarifier]
```

### Ví dụ

- Chưa tốt: `trả lời inbox bằng AI`
- Tốt hơn: `giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm`

- Chưa tốt: `dùng AI để viết nội dung`
- Tốt hơn: `tạo bản nháp nội dung chiến dịch phù hợp với brand trong thời gian rất ngắn`

### 3 tiêu chí tự kiểm

- [x] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [x] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [x] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
> Học ôn tập kiến thức AI bằng chatbot và quiz thích ứng.

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: chatbot, quiz.

### Bản chốt

**Core JTBD cuối cùng:**  
> Lấp đầy lỗ hổng kiến thức học thuật chuyên sâu một cách hiệu quả trong suốt khóa học tech intensive.

---

## Bước 5 — Viết 3 `Job Stories`

Nếu `core JTBD` là job ở mức cốt lõi, thì `job story` giúp bạn thấy
**job này xuất hiện trong hoàn cảnh nào**.

### Format

```text
When [trigger], I want to [motivation], so I can [outcome].
```

### Ví dụ

`When inbox đổ dồn vào buổi tối, tôi muốn có câu trả lời nhất quán ngay lập tức, so I can không mất đơn vì phản hồi chậm.`

### Bảng 3 job stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 | Khi tôi ôn tập lý thuyết phức tạp (như Backpropagation) vào buổi tối | được luyện tập các câu hỏi vừa sức với năng lực hiện tại của mình (ZPD) | nắm vững concept đó từng bước mà không cảm thấy ngợp hay chán | Sự cần thiết của công cụ chọn câu hỏi adaptive để duy trì động lực học tập. |
| JS2 | Khi tôi không hiểu một khái niệm kỹ thuật trong slide bài giảng | được giải thích chi tiết theo cách khơi gợi tư duy (Socratic) bám sát tài liệu chính thống | hiểu sâu bản chất khái niệm thay vì chỉ học vẹt để đối phó | Sự cần thiết của Socratic Chat có căn cứ (grounded) để tự học lý thuyết hiệu quả. |
| JS3 | Khi tôi bị kẹt khi debug code bài tập lớn lúc nửa đêm | có một hệ thống gợi ý từng bước (hint ladder) định hướng cách sửa | tự sửa được code mà không bị mất đi tính liêm chính học thuật | Sự cần thiết của cơ chế bảo vệ học thuật (academic integrity) ngăn lười tư duy. |

### Tự kiểm nhanh

- [x] Mỗi story là một **tình huống thật**, không phải slogan chung chung
- [x] 3 story không trùng hệt nhau
- [x] Sau khi đọc 3 story, tôi hình dung được lúc nào product của mình đáng xuất hiện

---

## Bước 6 — Liệt kê `Current Alternatives`

Qua JTBD lens, đối thủ không chỉ là app cùng ngành.
Đối thủ là **bất kỳ thứ gì user đang "thuê" để làm job**:

- thao tác tay
- file Excel / Google Sheets
- intern / nhân viên
- agency
- ChatGPT / Claude / Gemini
- công cụ chuyên dụng khác
- hoặc thậm chí là **không làm gì cả**

### Bảng alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| ChatGPT / Claude đại trà (Free) | Giải thích concept nhanh, viết code hộ, giải hộ bài tập. | Phản hồi tức thì, đa năng, code chạy được ngay. | Hay ảo tưởng (hallucinate), không bám sát giáo trình, cho lời giải trực tiếp làm mất phản xạ tự học. | Rất thấp (chỉ cần đổi tab trình duyệt). |
| Xem lại Slides / Video record | Xem lại kiến thức lý thuyết đã học trên lớp. | Nội dung chính thống 100% từ giảng viên. | Thụ động, tốn thời gian tua video tìm nội dung, không có tính tương tác. | Trung bình (ngại tìm và xem lại). |
| Hỏi Mentor hoặc bạn học qua Discord/Zalo | Hỏi đáp các phần bị kẹt khi làm bài tập/lab. | Câu trả lời chính xác, giải thích mang tính cá nhân. | Không online 24/7 (bị trễ giờ), học viên thường ngại hỏi những câu cơ bản. | Cao (do rào cản tâm lý ngại làm phiền và độ trễ). |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> Sử dụng ChatGPT/Claude để làm bài hộ và hỏi mentor/bạn học qua chat khi gặp lỗi quá phức tạp.

---

## Bước 7 — Điền `JTBD Lite Map`

Đây là bản rút gọn của `job map` trong playbook.

### Mục tiêu

Không phải để làm consultant workshop hoàn chỉnh.  
Mục tiêu là nhìn ra:

1. workflow hiện tại của user đi qua những bước nào
2. bước nào đang đau nhất
3. AI có nên chen vào đó không

### 8 bước tham chiếu từ playbook

1. `Define`
2. `Locate`
3. `Prepare`
4. `Confirm`
5. `Execute`
6. `Monitor`
7. `Modify`
8. `Conclude`

> Không nhất thiết bước nào cũng quan trọng như nhau trong dự án của bạn.  
> Nếu ít liên quan, ghi `N/A`, đừng để trống.

### Bảng JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | Xác định phần kiến thức/concept cần học lại | Xem syllabus hoặc slide bài học | Không tự biết mình đang thực sự yếu concept nào để tập trung ôn tập | High |
| Locate | Tìm tài liệu hoặc câu hỏi liên quan đến concept cần ôn | Lục lại Drive tài liệu, video ghi hình lớp học | Mất thời gian tìm kiếm, tài liệu rời rạc không tập trung vào đúng lỗ hổng | Med |
| Prepare | Chuẩn bị môi trường học, bài tập để thực hành | Mở VS Code, mở ChatGPT để chuẩn bị đặt câu hỏi | Không có sẵn bộ bài tập thực hành được phân cấp độ khó phù hợp | Med |
| Confirm | Đánh giá mức độ sẵn sàng trước khi làm bài tập thật | Tự nhẩm lý thuyết hoặc xem lướt qua slide | Đánh giá hoàn toàn cảm tính, không có chỉ số đo lường chính xác | Med |
| Execute | Làm bài tập ôn luyện / viết code kiểm tra kiến thức | Tự làm lab hoặc bài tập lớn của khóa học | Bài quá khó gây nản, quá dễ gây chán; dễ lạm dụng AI chép code làm mất cơ hội tự học | High |
| Monitor | Theo dõi xem mình làm đúng hay sai và tiến bộ ra sao | Đối chiếu đáp án cuối bài hoặc nhờ mentor chấm | Thiếu lịch sử ghi nhận sự tiến bộ chi tiết theo từng concept riêng lẻ | Med |
| Modify | Tìm gợi ý, điều chỉnh hướng đi khi bị kẹt giữa chừng | Hỏi ChatGPT hoặc nhờ bạn học chỉ lỗi hộ | Gợi ý của AI chung chung, dễ lộ luôn đáp án làm mất cơ hội tự suy luận | High |
| Conclude | Đánh giá đã làm chủ (master) concept đó chưa để chuyển bài | Tự đánh giá để quyết định học bài tiếp theo | Thiếu chỉ số định lượng (như điểm Elo) chứng minh sự thuần thục thực sự | High |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** Execute (Tiến hành thực hành và làm bài tập ôn luyện)  
**Bước đau nhất #2:** Conclude (Đánh giá mức độ thuần thục concept để hoàn thành việc học)

**Vì sao đây là nơi đáng chú ý nhất:**  
> Đây là hai điểm cốt lõi quyết định hiệu quả học tập: Học viên dễ nản lòng hoặc chán nản nếu độ khó bài tập không khớp với năng lực thực tế (ZPD), và họ hoàn toàn thiếu một chỉ số định lượng đáng tin cậy để biết mình đã thực sự làm chủ (master) một concept hay chưa để chuyển sang phần tiếp theo.

---

## Bước 8 — Chỉ ra `AI Leverage Point`

Sau khi map workflow, mới hỏi:
**AI nên vào đâu, với vai trò gì, và vì sao là ở đó?**

### Nhắc nhanh

- Đừng nhét AI vào chỉ vì "có AI thì nghe hay"
- Nếu pain lớn nhất không nằm ở chỗ AI giải tốt, hãy thành thật ghi ra
- Nếu current alternative đã đủ tốt, project cần xem lại

### Bảng leverage point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| Execute | Ước lượng điểm Elo để tự động đề xuất câu hỏi ôn luyện trong ZPD (70-75% success rate). Thiết lập Baseline Elo ban đầu bằng cách cho học viên tự chọn trình độ kết hợp 1 bài test chẩn đoán ngắn (3 câu). | AI có thể tính toán động và tối ưu hóa việc chọn câu hỏi dựa trên lịch sử tương tác thời gian thực của học sinh, điều giáo án tĩnh không làm được. | Thuật toán có thể bị lệch ở những lượt đầu tiên do thiếu dữ liệu lịch sử (cold start) nếu không có bài test chẩn đoán đầu vào. |
| Modify | Đóng vai trò Socratic Tutor, cung cấp các gợi ý từng bước (hint ladder) dẫn dắt tư duy. Cho phép học viên dùng AI nội bộ của hệ thống (vì bám sát giáo trình) thay vì cấm đoán. | LLM có khả năng điều chỉnh giọng điệu giải thích linh hoạt theo ngữ cảnh của tài liệu chính thống và hỗ trợ kiên nhẫn 24/7. | Không thể chặn trực tiếp học sinh dùng AI ngoài (ChatGPT/Claude) để chép code đối phó deadline; cần hướng họ dùng AI hệ thống nhờ độ tiện lợi và bám sát ngữ cảnh. |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> Tự động chọn câu hỏi cá nhân hóa theo ZPD (định vị qua tự chọn trình độ + test chẩn đoán) và hướng dẫn học viên tự học qua Socratic Hint Ladder dựa trên tài liệu khóa học chính thống.

**Vì sao không phải ở bước khác:**  
> Vì đây là hai điểm trực tiếp giải quyết nỗi đau lớn nhất của học viên khi tự học: sự chán nản do bài tập lệch trình độ và sự triệt tiêu tư duy khi dùng AI đại trà.

---

## Bước 9 — Viết `Product Hypothesis`

Bây giờ mới đến lúc viết hypothesis.

### Công thức gợi ý

```text
Nếu chúng ta giúp [job executor] làm [job / sub-job] tốt hơn ở bước [x],
bằng cách [AI leverage],
thì họ sẽ chuyển từ [current alternative] sang [hướng giải pháp của nhóm],
vì [giá trị rõ nhất].
```

### Bản hypothesis của tôi

> Nếu chúng ta giúp học viên các khóa học AI thực chiến lấp đầy lỗ hổng kiến thức tốt hơn ở bước thực hành (Execute) và điều chỉnh học tập (Modify), bằng cách tự động đề xuất câu hỏi cá nhân hóa (ZPD) và hướng dẫn tư duy thông qua Socratic Hint Ladder tích hợp sẵn, thì họ sẽ chuyển từ việc sử dụng các chatbot AI đại trà (ChatGPT/Claude) sang sử dụng AI của hệ thống EduGap, vì họ nhận được sự hỗ trợ tiện lợi, bám sát ngữ cảnh giáo trình và học đúng trình độ mà vẫn đảm bảo tính tự chủ trong học tập.

### Tín hiệu sớm nếu hypothesis này đúng

1. Tỷ lệ hoàn thành câu hỏi (Quiz completion rate) đạt mức ổn định và cao (>80%) do câu hỏi vừa sức.
2. Học viên chủ động sử dụng tính năng Socratic Chat và Hint Ladder tích hợp sẵn thay vì copy-paste từ chatbot ngoài, thể hiện qua việc số lượng hội thoại/lượt dùng hint nội bộ tăng ổn định.

---

## Bước 10 — Liệt kê `Assumptions to Validate`

Job story chưa có research vẫn chỉ là **giả thuyết tốt hơn**, chưa phải sự thật.

### 5 assumption thường đáng kiểm

- Tôi đã chọn đúng `job executor`
- Pain này thật sự đủ đau và xảy ra đủ thường xuyên
- User sẽ đổi khỏi alternative hiện tại nếu có giải pháp tốt hơn
- AI thực sự tạo giá trị ở step tôi chọn
- User đủ tin kết quả AI để đưa vào workflow thật

### Bảng assumptions

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| A1 | Học viên sẵn sàng dùng AI Socratic của hệ thống vì nó tiện lợi và sát ngữ cảnh học tập hơn là dùng AI ngoài để chép đối phó. | Rất cao, vì áp lực deadline bài tập lớn có thể khiến họ ưu tiên chép code ăn liền từ AI ngoài. | Quan sát hành vi sử dụng thực tế: theo dõi tỉ lệ tương tác Socratic Chat nội bộ vs số lần copy code trên hệ thống thử nghiệm. |
| A2 | Bài test chẩn đoán ngắn (3 câu) kết hợp tự chọn trình độ giúp định vị Elo nền tảng chính xác và loại bỏ được cold start. | Trung bình, 3 câu test có thể chưa đủ để đánh giá đúng phổ năng lực ban đầu. | Thử nghiệm thuật toán chọn câu hỏi với nhóm nhỏ học viên (Alpha test) và tối ưu hóa hệ số K-factor. |
| A3 | Pipeline RAG tự động hóa việc re-ingest tài liệu thay đổi giữa các cohort mà không làm gián đoạn hệ thống dữ liệu Elo của học viên. | Cao, tài liệu của cohort mới có thể thay đổi cấu trúc hoặc concept graph làm lệch RAG. | Lập bộ câu hỏi Golden Test để đánh giá tự động độ chính xác của RAG ngay sau khi re-ingest tài liệu khóa học mới. |
| A4 | Mentor thực sự sử dụng Class Insight Dashboard để điều chỉnh bài giảng tuần sau. | Trung bình, mentor có thể bận hoặc bỏ qua dashboard nếu insights không dễ hiểu. | Phỏng vấn trực tiếp Mentor sau tuần đầu thử nghiệm để tối ưu hiển thị dữ liệu Class Insight. |
| A5 | Nhà trường/Ban tổ chức khóa học sẵn sàng tích hợp EduGap vào quy trình đào tạo chính thức (B2B2C). | Cao, ảnh hưởng trực tiếp đến mô hình kinh doanh và khả năng phân phối dự án. | Thỏa thuận thử nghiệm miễn phí với khóa AI20K Cohort 2 để chứng minh hiệu quả thực tế trước khi đề xuất hợp tác chính thức. |

### Assumption nguy hiểm nhất nếu tôi đang sai

> **A1:** Học viên sẵn sàng sử dụng AI Socratic của hệ thống thay vì lạm dụng AI ngoài để chép lời giải đối phó deadline. Nếu tính năng Socratic nội bộ không đủ tiện lợi hoặc lôi cuốn, học viên vẫn sẽ dùng ChatGPT/Claude bên ngoài để lấy đáp án nhanh qua môn.

---

## Bước 11 — Share trong bàn (3')

### Mỗi người / mỗi nhóm chỉ nói 4 thứ

1. **Job executor của bạn là ai**
2. **Core JTBD của bạn là gì**
3. **Step đau nhất đang nằm ở đâu**
4. **AI leverage point + assumption rủi ro nhất là gì**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Câu JTBD này có đang lỡ nhét solution vào không?"**
2. **"Alternative hiện tại của user là gì, và tại sao họ chưa bỏ nó?"**
3. **"Pain mạnh nhất nằm ở bước nào trong workflow, có chắc AI giải tốt được không?"**
4. **"Assumption nào nếu sai thì cả hypothesis sẽ sập?"**

### Ghi nhanh sau khi nghe bàn phản biện

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| Không thể chặn trực tiếp việc học sinh dùng AI ngoài để chép bài, cách tốt nhất là cho phép và điều hướng họ dùng AI nội bộ tiện lợi hơn. | Academic Integrity / Step 10 (A1) | Giữ nguyên việc không chặn cứng AI ngoài, cho phép dùng AI hệ thống nhưng định hướng bằng Socratic và bám sát tài liệu khóa học để tạo giá trị vượt trội. |
| Việc chọn Elo mặc định dễ gây lỗi cold-start làm học sinh chán nản ngay từ những câu hỏi đầu tiên. | ZPD Selector / Step 10 (A2) | Sửa thuật toán: Cho học viên tự chọn level ban đầu (Beginner/Intermediate/Advanced) kết hợp bài test chẩn đoán ngắn (3 câu) để có baseline Elo ngay. |
| Giáo án và tài liệu của mỗi cohort thay đổi liên tục, dữ liệu Elo và RAG sẽ bị lỗi thời. | Content Ingestion / Step 10 (A3) | Sửa cơ chế cập nhật: Khi sang cohort mới, thực hiện re-ingest/RAG lại toàn bộ các tài liệu thay đổi để cập nhật nội dung tương ứng. |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [x] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [x] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [ ] Giữ nguyên `AI leverage point`
- [x] Sửa `AI leverage point`
- [ ] Giữ nguyên `product hypothesis`
- [x] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> Tôi cập nhật AI leverage point và các giả thuyết theo phản hồi thảo luận để giải quyết thực tế: không thể chặn cứng AI ngoài mà tập trung tối ưu sự tiện dụng của AI nội bộ, sửa bài toán cold-start bằng test chẩn đoán + tự chọn trình độ, và xử lý thay đổi giáo án bằng pipeline tự động RAG lại tài liệu mới.

### Version cuối cùng tôi nộp

**Job executor:**  
> Học viên khoá học AI thực chiến (ví dụ: AI20K Cohort 2).

**Core JTBD:**  
> Lấp đầy lỗ hổng kiến thức học thuật chuyên sâu một cách hiệu quả trong suốt khóa học tech intensive.

**2 bước đau nhất trong workflow:**  
> Execute (Luyện tập và kiểm tra kiến thức) & Conclude (Đánh giá mức độ thuần thục concept).

**AI leverage point chính:**  
> Đề xuất câu hỏi ZPD dựa trên điểm Elo (xác định qua tự chọn level + bài test chẩn đoán ngắn đầu vào) và hướng dẫn qua Socratic Hint Ladder tích hợp sẵn (cho phép sử dụng AI nội bộ tối ưu theo ngữ cảnh thay vì cấm đoán dùng AI ngoài).

**Product hypothesis:**  
> Nếu chúng ta giúp học viên các khóa học AI thực chiến lấp đầy lỗ hổng kiến thức tốt hơn ở bước thực hành (Execute) và tự điều chỉnh (Modify) bằng cách đề xuất câu hỏi ZPD cá nhân hóa và Socratic Hint Ladder tích hợp sẵn, thì họ sẽ chuyển từ dùng chatbot AI ngoài sang sử dụng AI của EduGap, vì họ được ôn tập đúng trình độ, giải thích bám sát tài liệu khóa học mà vẫn giữ được tính chủ động học tập.

**Assumption cần validate đầu tiên:**  
> Học viên ưu tiên dùng AI Socratic của hệ thống thay vì lạm dụng chatbot ngoài nhờ tính tiện dụng, cá nhân hóa và bám sát ngữ cảnh giáo trình của hệ thống.

---

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [x] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 người dùng thật để kiểm xem `job story` nào là sát nhất.
- So sánh `current alternatives` với project của nhóm theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn.
- Tự hỏi lại một câu khó: **nếu không dùng AI, project này còn tạo giá trị không?**
- Nếu câu trả lời là "không", hãy xem lại liệu nhóm đang giải **job thật** hay chỉ đang tìm chỗ để nhét AI.
