---
name: history-tech-explainer
description: Dựng video giải thích bằng hoạt hình 2D màu phẳng, viền đen, nhân vật đầu tròn và bối cảnh đời thường cụ thể. Dùng khi người dùng gửi kịch bản, voice, SRT hoặc video RAW và yêu cầu dựng theo phong cách đã duyệt; phù hợp lịch sử, khoa học, công nghệ và các câu chuyện giải thích khác. Tự thay bối cảnh, nhân vật, trang phục, hành động theo nội dung, quốc gia và thời kỳ; lập phân cảnh, dựng chuyển động, thêm cảnh cận và SFX tiết chế, kiểm tra rồi xuất MP4.
---

# Dựng explainer hoạt hình 2D theo phong cách đã duyệt

Bản chuẩn 2.0 — cập nhật ngày 24/10/2026 theo góp ý của người dùng. Chỉ dẫn mới của người dùng luôn ưu tiên hơn mặc định này.

## Hợp đồng phong cách

Dùng bản demo 57 giây về charpai, kang/ondol và futon làm chuẩn thị giác. Xem [chuẩn đã duyệt](references/phan-tich-mau.md) và [ảnh tham chiếu](assets/style-reference.jpg). Bản 31 giây sau sửa điểm tựa là ví dụ bổ sung.

- Hoạt hình 2D màu phẳng, viền đen rõ, màu dễ nhìn; phối cảnh và đồ vật gần gũi đời thật.
- Nhân vật đầu tròn, mắt chấm, nét mặt đơn giản. Có thể dùng mặt trắng hoặc màu da phù hợp; tay chân có độ dày, áo quần có hình khối rõ.
- Giữ tỷ lệ đầu, độ dày nét và cách diễn nhất quán; đa dạng tóc, tuổi, trang phục, tư thế, nghề nghiệp và đạo cụ theo câu chuyện.
- Bối cảnh có kiến trúc, mặt sàn, cửa, đồ dùng và các lớp không gian cụ thể; tránh nền trống chung chung suốt video.
- Giữ màu phẳng và viền đen đồng bộ giữa nền, nhân vật và đạo cụ. Không mặc định quay lại hình bán hiện thực, ảnh người thật, 3D hoặc nền giấy vẽ màu của các bản thử cũ.
- Giữ cách kể bằng hình, không sao chép nội dung chiếc giường sang kịch bản mới. Không tự chép số liệu, quốc gia, mốc thời gian hoặc nhân vật từ video mẫu.

## Cách xử lý yêu cầu

Khi có kịch bản và voice, chủ động dựng theo chuẩn này, đổi nội dung hình cho phù hợp câu chuyện. Không yêu cầu người dùng chọn lại phong cách đã chốt. Chỉ hỏi khi thiếu thông tin thật sự ngăn cản dựng đúng nội dung.

Nếu người dùng yêu cầu dựng toàn bộ, hoàn thành video theo toàn bộ voice thực tế. Nếu yêu cầu demo, chọn đoạn có ý trọn vẹn, kết thúc trước câu tiếp theo. Nếu chỉ yêu cầu sửa/cập nhật skill, không dựng lại video.

Không dừng ở kế hoạch, danh sách tài sản hay thành công cài công cụ khi người dùng đã yêu cầu MP4. Lưu dự án và hướng dẫn chạy lại; tiếp tục đến kiểm tra và bàn giao hoặc một trở ngại cụ thể không thể tự xử lý.

## 1. Đọc đầu vào và lập bản đồ ý

Đo thời lượng, độ phân giải, fps và audio; không suy từ tên tệp. Voice là trục thời gian. Đối chiếu SRT nếu có, giữ đủ lời đọc và không cắt mất âm cuối. Tận dụng tài liệu đã gửi, không hỏi lại.

Nếu thiếu transcript, dùng công cụ phiên âm hiện có và kiểm tra từ khóa. Không nhận định giọng, nhạc hoặc SFX của file khi chưa có khả năng nghe/kiểm tra. Không nói đã nghe hoặc xem tốc độ thực nếu chỉ kiểm tra khung hình và metadata.

Chia lời nói thành từng đơn vị ý. Mỗi cảnh có tiêu điểm, hành động hoặc thay đổi trạng thái rõ. Tách các phần cần cảnh sinh hoạt, thao tác, cận cảnh cơ chế, bản đồ, số liệu và so sánh. Không chia đều voice thành các ảnh cùng thời lượng.

## 2. Bối cảnh, nhân vật và phục trang theo câu chuyện

Đọc [công thức cảnh](references/cong-thuc-canh.md) trước khi lập shot list hoặc tạo hình.

Với mỗi cụm cảnh, xác định địa điểm/quốc gia, thời kỳ, khí hậu, môi trường sinh hoạt và nghề nghiệp. Chọn kiến trúc, vật liệu, đồ dùng, quần áo, kiểu tóc, mũ và giày dép phù hợp các thông tin đó.

Không dùng một nhân vật mặc cùng bộ đồ xuyên mọi quốc gia/thời đại. Nhân vật dẫn chuyện có thể giữ nhận diện riêng, nhưng phải tách vai trò dẫn chuyện khỏi nhân vật trong câu chuyện. Giữ liên tục trang phục và đạo cụ của cùng người trong cùng phân đoạn.

Đa dạng tư thế theo ý nghĩa: đứng, ngồi, quỳ, cúi, đi, bê, đan, kéo, mở, gấp, rót, chỉ, quan sát, phản ứng hoặc nghỉ ngơi khi phù hợp. Không đổi tóc hoặc màu áo rồi coi là đã đổi hành động.

Với chi tiết lịch sử không chắc, tra nguồn đáng tin khi có thể. Không biến một suy đoán thành phục dựng chính xác. Không dùng trang phục rập khuôn để đại diện mọi người của một quốc gia.

## 3. Shot list và cảnh cận bắt buộc theo ý nghĩa

Sao chép [mẫu dữ liệu cảnh](assets/shot-list.template.json) và thay toàn bộ nội dung mẫu theo dự án. Ghi mốc voice, loại cảnh, tiêu điểm, hành động, camera, chữ, chuyển cảnh, SFX và điểm tiếp xúc.

- Thiết lập không gian bằng toàn cảnh rồi cắt vào trung/cận cảnh khi lời đọc nhắc tới đồ vật, bàn tay, thao tác hoặc cơ chế quan trọng.
- Mỗi cụm giải thích thao tác/cơ chế phải xem xét một cận cảnh hữu ích. Thể hiện rõ cảnh nào sẽ zoom in hoặc cắt đặc tả, không chỉ ghi chung là zoom nhẹ.
- Cảnh cận phải đúng đồ vật hoặc điểm tay đang tác động; giữ liên hệ vị trí với cảnh trước, có thể quay ra toàn cảnh để thấy kết quả.
- Luân phiên cỡ cảnh và góc nhìn, tránh nhiều cảnh liên tiếp cùng bố cục và cùng kiểu zoom. Thay bối cảnh khi địa điểm, thời kỳ hoặc ý chính đổi.
- Nếu quay lại bối cảnh cũ, thêm hành động, góc nhìn, chi tiết hoặc chức năng mới có lý do. Không thay nền tùy tiện trong cùng một thao tác liên tục.

Khoảng 3–8 giây/cảnh là điểm khởi đầu để thử, không phải quy tắc chia đều hay số đo video mẫu. Cho người xem đủ thời gian đọc sơ đồ; cảnh dài phải có thay đổi có ý nghĩa.

## 4. Tạo và tách tài sản

Tạo nền dư biên cho camera, đúng phối cảnh và không lẫn phong cách. Tách nhân vật, các bộ phận cần chuyển động, vật cầm, đạo cụ thao tác, chữ và các lớp nền khi cần.

Yêu cầu nền không chứa sẵn người hoặc đạo cụ sẽ được vẽ động ở cùng vị trí. Kiểm tra để không có hai ngọn lửa, hai tấm nệm hoặc nhân vật bị nhân đôi khi ghép.

Với atlas, kiểm tra ranh giới từng ô, crop đúng, giữ tỷ lệ, xem alpha trên nền tương phản; không coi ảnh tạo ra luôn tuân thủ lưới. Không tạo chữ trong ảnh AI khi có thể dựng chữ bằng lớp riêng.

Nếu chỉ có ảnh phẳng, chỉ dùng chuyển động thật sự làm được từ ảnh đó. Không hứa chuyển động tay chân độc lập, parallax nhiều lớp hoặc xoay 3D khi chưa có tài sản phù hợp.

## 5. Dựng chuyển động và điểm tiếp xúc

Đọc [triển khai và kiểm tra](references/trien-khai.md). Đặt hành động trước, camera theo hành động sau. Không thay hành động bằng việc trượt cả ảnh nhân vật qua nền.

- Xác định mặt đất/mặt ghế/mặt giường và các điểm tựa trong tọa độ cảnh.
- Giữ bàn chân, đầu gối, hông, cẳng tay hoặc lưng chạm đúng mặt đỡ theo tư thế; đặt bóng tiếp xúc ngay dưới điểm đó.
- Khi đổi tư thế, thiết kế chuyển động từng khớp hoặc dùng tư thế thay thế có kiểm soát. Không xoay/nâng cả thân rồi để tay chân và bóng ở vị trí cũ.
- Vật cầm đi cùng điểm nắm. Hai người mang một vật phải chia sẻ điểm nắm, chiều cao và nhịp, không animate ba lớp độc lập gây tách tay.
- Khi rót, gấp, kéo, trải, đan hoặc mở, quan hệ tay–vật, bản lề, trọng lực, che khuất và bóng phải nhất quán.
- Không dùng mảng nền hoặc bóng hình học để che một tư thế sai. Không để tay chân xuyên vật, cổ rời thân, đồ vật lơ lửng hoặc người ngồi không có mặt đỡ.

Cho camera cắt cận hoặc zoom vào chi tiết khi cần giải thích. Giữ vật được nhấn trong khung, kiểm tra mép nền, lề chữ và hình trong suốt chuyển động. Không để camera trôi suốt mọi cảnh.

## 6. Chuyển cảnh, SFX và chữ

Lập SFX cho mỗi lần chuyển cảnh. Mặc định dùng một tín hiệu nhẹ phù hợp cho chuyển cảnh rõ ràng hoặc đổi ý/địa điểm/thời gian. Cut nội bộ cùng thao tác có thể nối bằng âm hành động hoặc chủ động im lặng để giữ tự nhiên; ghi lý do thay vì bỏ qua mặc định.

Dùng cut, match cut, pan/zoom nối, wipe hoặc mở tròn khi có quan hệ kể chuyện. Không lặp một whoosh lớn ở mọi điểm cắt. Với các cut rất sát nhau, dùng một cầu âm thanh thay vì chồng nhiều hiệu ứng.

SFX hành động gắn đúng lúc chạm, bước, kéo vải, đan dây, mở đồ hoặc đặt vật xuống. Chọn âm hợp chất liệu/bối cảnh; không lạm dụng beep, pop, va đập hay rung máy. Giữ voice rõ, giảm/duck SFX dưới lời nói; mặc định không thêm nhạc nếu chưa có nhu cầu phù hợp.

Dùng nhãn ngắn cho địa điểm, thời kỳ, vật, số liệu và luận điểm. Không phủ phụ đề lớn liên tục trừ khi người dùng yêu cầu. Font đủ dấu tiếng Việt, lề an toàn, không chồng chữ hoặc che hành động. Chữ phải theo đúng kịch bản và giữ mức độ chắc chắn của phát biểu.

## 7. Kiểm tra bản xuất

Trước khi render dài, xuất thử nội bộ một cảnh bối cảnh, một cảnh thao tác và một cảnh cơ chế/đặc tả. Nếu người dùng chỉ cần cập nhật skill thì bỏ bước render.

Kiểm tra file xuất thực tế, không chỉ mã nguồn hoặc một still đẹp. Xem trước/giữa/sau mọi chuyển tư thế và điểm cắt; đặc biệt kiểm tra đi, bê, ngồi, quỳ, nằm, gấp, rót, điểm nắm và bóng. Kiểm tra cận cảnh, khuôn mặt, tay, cổ, viền alpha, chữ và mép nền.

Nghe kiểm tra voice/SFX và nhịp ở tốc độ thực nếu công cụ cho phép. Contact sheet chỉ là kiểm tra mẫu khung hình, không thay cho xem chuyển động. Công khai giới hạn kiểm tra nếu không thể nghe/xem trực tiếp; không khẳng định những bước chưa thực hiện.

Mặc định xuất MP4 H.264, 1920×1080, 30 fps với audio tương thích; theo yêu cầu khác của người dùng nếu có. Xác minh số frame/thời lượng theo audio thực, đầu và âm cuối, codec, khả năng giải mã, loudness và true peak. Sửa lỗi thị giác trước khi bàn giao.

## 8. Bàn giao và tái sử dụng

Bàn giao video khi đã được yêu cầu dựng, kèm link tải hoạt động. Dùng nơi tải mà người dùng đã chọn/cho phép, như GitHub trong dự án hiện tại; không tự công khai mọi dự án chỉ vì skill có ví dụ GitHub. Giữ các bản cũ để đối chiếu khi sửa.

Lưu shot list, tài sản, mã dự án, lệnh render và mốc voice. Phân biệt tài sản thật, hình AI, placeholder, hoạt hình theo lớp và các tính năng chưa kiểm tra. Báo ngắn gọn thời lượng, độ phân giải, nội dung đã dựng và giới hạn quan trọng.

Với kịch bản/voice mới: tái sử dụng phong cách, quy tắc chuyển động và quy trình kiểm tra; dựng lại bối cảnh, nhân vật, phục trang, đạo cụ, hành động và số liệu theo câu chuyện mới.
