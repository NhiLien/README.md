# README.md
**DỰ BÁO GIÁ CỔ PHIẾU CỦA NGÂN HÀNG PT BANK CENTRAL AISA TBK (BCA)**

**1. Giới thiệu**

PT Bank Central Asia Tbk (BCA) là một trong những ngân hàng lớn nhất tại Indonesia với hoạt động kinh doanh đa dạng trong lĩnh vực tài chính và ngân hàng. Giá cổ phiếu của BCA phản ánh hiệu suất hoạt động của ngân hàng và bị ảnh hưởng bởi nhiều yếu tố kinh tế, tài chính, và thị trường. Mục tiêu của nghiên cứu này là dự báo giá cổ phiếu của BCA trong giai đoạn 2020 - 2024 bằng cách sử dụng các phương pháp phân tích dữ liệu và mô hình dự báo.

**2. Phương pháp nghiên cứu**

Nghiên cứu sử dụng phương pháp phân tích dữ liệu thời gian và mô hình dự báo dựa trên:

**3. Nguồn dữ liệu**

●	Source: https://www.kaggle.com/datasets/brmil07/bank-stock-price/code 

●	Description: Dữ liệu bao gồm giá cổ phiếu theo ngày, khối lượng giao dịch, và một số số liệu tài chính liên quan khác. Giá cổ phiếu trong dữ liệu được thu thập theo đơn vị tiền tệ IDR – Rupiah Indonesia. 

●	Structure:
  
    Date: Ngày giao dịch.
  
    Open Price: Giá mở cửa của cổ phiếu.
  
    Close Price: Giá đóng cửa của cổ phiếu.
  
    High Price: Giá cao nhất mà cổ phiếu của ngân hàng đạt được trong ngày giao dịch.
  
    Low Price: Giá thấp nhất mà cổ phiếu của ngân hàng đạt được trong ngày giao dịch.
  
    Adjusted Low Price: Giá đóng cửa trong ngày giao dịch, được điều chỉnh để phản ánh các hoạt động của ngân hàng, chẳng hạn như chia tách cổ phiếu, cổ tức, quyền chào bán, hoặc những sự điều chỉnh khác có thể ảnh hưởng đến giá cổ phiếu của ngân hàng.
   
    Volume: Số lượng cổ phiếu giao dịch trong một ngày.

**3. Phân tích dữ liệu**

__📊__  _Xu hướng giá cổ phiếu BCA_

![Screenshot 2025-02-16 010411](https://github.com/user-attachments/assets/a6eda686-5b27-4460-bbf7-45491664d681)

Nhìn chung, cổ phiếu BCA có xu hướng tăng trưởng mạnh mẽ trong dài hạn, bất chấp những biến động ngắn hạn do các yếu tố kinh tế cũng như thị trường:

  * Giai đoạn 2014 - 2019:

Trong giai đoạn này, giá cổ phiếu BCA tăng trưởng ổn định, từ khoảng 2.000 Rp năm 2014 lên mức đỉnh 6.900 Rp vào 2019. Xu hướng này được thúc đẩy bởi môi trường kinh tế thuận lợi, chính sách tiền tệ hợp lý và lãi suất ổn định. Ngoài ra, chiến lược kinh doanh hiệu quả và quản trị rủi ro chặt chẽ của BCA giúp duy trì tính thanh khoản cao, thu hút sự quan tâm mạnh mẽ từ nhà đầu tư trong và ngoài nước.

  * Giai đoạn 2020 - 2021:

Biểu đồ cho thấy giá cổ phiếu của BCA đã giảm mạnh từ 6.900 Rp xuống còn 4.400 Rp do ảnh hưởng của đại dịch COVID-19. Tuy nhiên, sau khi chính phủ Indonesia triển khai các chính sách phục hồi kinh tế, hoạt động ngân hàng của BCA dần được cải thiện. Nhờ đó, giá cổ phiếu tăng lên 7.300 Rp vào năm 2021, vượt qua mức trước đại dịch.

  * Giai đoạn 2022 - 2024:

Trong giai đoạn này, giá cổ phiếu BCA tăng mạnh nhưng biến động lớn. Sau đại dịch, giá đạt 8.200 Rp vào 2022 trước khi điều chỉnh xuống 7.000 Rp. Từ 2023-2024, giá tiếp tục tăng, chạm 9.700 Rp đầu 2024. Sự tăng trưởng này nhờ ngành ngân hàng mở rộng, niềm tin nhà đầu tư phục hồi và chính sách tiền tệ thuận lợi, dù vẫn chịu ảnh hưởng từ lãi suất, lạm phát và xu hướng chốt lời.

__📊__  _Xu hướng về khối lượng giao dịch của cổ phiếu BCA_

<img width="289" alt="image" src="https://github.com/user-attachments/assets/bc797720-b6ad-4cf9-8ba8-91a23b8707e1" />

Nhìn chung, tổng khối lượng giao dịch cổ phiếu BCA trải qua nhiều giai đoạn biến động, với những đợt tăng mạnh vào 2016 và 2020, cụ thể:
 
  * Giai đoạn 2014 - 2018: 

Trong giai đoạn này, tổng khối lượng giao dịch cổ phiếu BCA tăng trưởng ổn định qua từng năm, đạt đỉnh vào năm 2016 với 23,000 cổ phiếu. Giai đoạn 2017-2018 ghi nhận mức giao dịch cao nhất trong 10 năm, đạt đỉnh 1.06 tỷ cổ phiếu. Nguyên nhân có thể do các sự kiện quan trọng của BCA như thay đổi chiến lược, điều chỉnh cổ tức, hoặc tăng vốn; tác động từ kinh tế vĩ mô và chính sách tài chính; cũng như hoạt động mua/bán của các quỹ đầu tư lớn.

  * Giai đoạn 2019 - 2021:

Sau đợt tăng mạnh năm 2018, khối lượng giao dịch giảm nhẹ nhưng vẫn duy trì ở mức cao. Năm 2020, giao dịch tăng vọt, có thể do tác động của đại dịch COVID-19, khi dòng vốn đổ mạnh vào thị trường chứng khoán. Đỉnh điểm trong năm đạt 0.54 tỷ cổ phiếu, có thể liên quan đến các biện pháp kích thích kinh tế của chính phủ Indonesia.

  * Giai đoạn 2022 - 2023:

Khối lượng giao dịch tiếp tục tăng mạnh, đạt đỉnh khoảng 0.72 tỷ cổ phiếu vào năm 2023. Nguyên nhân có thể đến từ sự phục hồi của thị trường chứng khoán sau đại dịch, sức hút của cổ phiếu BCA nhờ kết quả kinh doanh khả quan hoặc chính sách cổ tức hấp dẫn, cùng với dòng vốn từ nhà đầu tư nước ngoài và các quỹ đầu tư gia tăng.

  * Giai đoạn 2014:

Những tháng đầu năm 2024, khối lượng giao dịch có dấu hiệu giảm. Điều này có thể do tâm lý thận trọng của nhà đầu tư trước những biến động kinh tế toàn cầu, cùng với giai đoạn điều chỉnh tự nhiên sau các đợt giao dịch sôi động trước đó.

__📊__  _Xu hướng giá cổ phiếu BCA bằng MA (Moving Average)_

Trong bài nghiên cứu này, tác giả dùng đường trung bình động MA để xác định xu hướng giá của cổ phiếu BCA trong giai đoạn 2014 - 2024. Và MA được tính dựa trên giá đóng cửa trung bình trong một khoảng thời gian nhất định.

* Nhận xét chung:

![Screenshot 2025-02-16 134349](https://github.com/user-attachments/assets/7670b0b5-64e9-4493-859a-7e0b8452a618)

Nhìn chung, giá trị trung bình của giá đóng cửa cổ phiếu BCA có xu hướng tăng dần theo thời gian. Bên cạnh đó, đường MA 20, MA 50, MA 100 trên biểu đồ đều có xu hướng tăng lên trong dài hạn. Cụ thể là:

  * Giai đoạn 2014 - 2020: 

Trong giai đoạn này, đường MA 20 thường di chuyển gần MA 50, cho thấy giá cổ phiếu BCA có xu hướng tăng ổn định.

Tín hiệu mua: Xuất hiện khi MA 20 cắt lên MA 50 và MA 100, thể hiện sự tăng trưởng mạnh của cổ phiếu.

Chiến lược: Nhà đầu tư có thể cân nhắc mua vào khi xuất hiện tín hiệu cắt lên để tối ưu lợi nhuận.

  * Giai đoạn 2021 - 2023:

Trong suốt giai đoạn này, MA 20 duy trì trên MA 50 và MA 100, xác nhận xu hướng tăng mạnh của cổ phiếu BCA.

Chiến lược:
Nhà đầu tư dài hạn có thể giữ vị thế mua khi xu hướng tăng vẫn tiếp diễn.

Nhà đầu tư ngắn hạn có thể chốt lời dần khi giá đạt mức cao và cách xa MA 20.




  






**4. Kết quả dự báo**



**5. Kết luận**



**6. Khuyến nghị**









