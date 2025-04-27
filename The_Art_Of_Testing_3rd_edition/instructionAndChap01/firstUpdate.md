### Tầm quan trọng của kiểm thử - đúng nhưng chưa đủ

  Ngày nay, tài liệu về kiểm thử đã quá phổ biến. Chỉ với vài thao tác đơn giản trên Google, hoặc đặt vài câu hỏi với AI, bạn có thể dễ dàng gom cho mình kho tàng kiến thức khổng lồ về kiểm thử cũng như các kĩ thuật của chúng. Ngoài ra cũng có không ít các đầu sách đưa ra góc nhìn tổng quan phổ cập về "Testing", cuốn sách "The ART of SOFTWARE TESTING" của tác giả Glenford J. Myers cũng là một trong số chúng.


  Trước hết, với giọng văn nhẹ nhàng, không hoa mĩ, tác giả cũng đã cung cấp kiến thức về kiểm thử cho vùng đối tượng rộng rãi trong ngành "Computer", không chỉ riêng gì những Kĩ thuật viên Kiểm Thử. Đối với Dev, Designer, BA hay PM, cuốn sách cung cấp 1 góc nhìn cụ thể hơn về khái niệm và công việc Kiểm Thử. Từ đó có góc nhìn toàn diện và khách quan hơn để đưa ra các ý kiến đa chiều. Với những Tester, QC, QA, cuốn sách là nguồn tài liệu góp phần củng cố và nâng cao chuyên môn để có thể phối hợp hiệu quả với các nhóm phát triển và nhóm quản lý, đưa chất lượng sản phầm tốt lên từng ngày. Các kiến thức dù được viết cách đây 20 nay 30 năm đều vẫn có sự đúng đắn nhất định và vùng phủ rộng lớn không riêng gì dự án nào.


  Tuy nhiên, có thể do hướng đến quá đối tượng đọc không hoàn toàn là Người Kiểm Thử, cúng như muốn đi sâu hơn vào những khía cạnh khác của kiểm thử, nên ngay ở phần mở đầu và chương 1, tác giả chưa trả lời thực sự toàn diện cho câu hỏi "Vì sao kiểm thử lại quan trọng?"


  "So với thời điểm cuốn sách này ra đời, kiểm thử vừa dễ hơn, lại vừa khó hơn"


  Tuyên ngôn này không thể sai, dù cho bây giờ hay 100 năm nữa cũng vậy. Dễ hơn, theo một số cách, vì các bộ phần mềm và hệ điều hành ngày nay tinh vi hơn nhiều so với trước đây, cung cấp các hàm hoặc framework có sẵn đã được kiểm thử kỹ lưỡng, có thể được tích hợp vào ứng dụng mà không cần lập trình viên phải phát triển từ đầu. Khó hơn, vì sự đa dạng rộng lớn của các ngôn ngữ lập trình, hệ điều hành và nền tảng phần cứng đã đang và ngày càng phát triển. Việc các sản phẩm phần mềm ngày càng tinh vi và ảnh hưởng trực tiếp đến chất lượng sống đòi hỏi trách nhiệm lớn hơn của kiểm thử, cũng như các kĩ thuật kiểm thử ngày càng cần phát triển và cập nhật cho kịp thời đại. Để lấy dẫn chứng, tác giả có đưa ra một ví dụ về 1 chương trình đơn giả và list test case của nó, với mục đích chứng minh rằng việc kiểm thử ngay cả một chương trình đơn giản như thế này cũng không phải là một nhiệm vụ dễ dàng.


  Đúng, nhưng như vậy chưa đủ. Kiểm thử không chỉ dừng lại ở việc kiểm tra logic, mà còn có thể phát hiện ra những điểm "lỗi" về mặt business. Trong thực tế, kể cả những Dev kì cựu hay những người PM tài ba, đôi khi cũng không thể nắm toàn bộ business phức tạp của các domain, từ đó có thể có những thiếu sót, hoặc những mâu thuẫn trong nhiều luồng của một sản phẩm. Việc kiểm thử có thể được dùng trên mọi phương diện, từ yêu cầu cho đến sản phầm, giảm thiểu thời gian và công sức có thể bị lãng phí trong mọi giai đoạn của phát triển phần mềm.


  Áp dụng cho ví dụ mà tác giả đưa ra, kiểm thử k chỉ dừng lại ở việc lập list TCs, mà còn đặt ra những câu hỏi nhằm hoàn thiện các điều kiện của chương trình và định nghĩa cụ thể hơn kết quả phù hợp cho từng trường hợp. Đây đều là những công việc cơ bản và diễn ra hàng ngày của người kiểm thử, giúp cho việc phát triển và quản lí đều dễ dàng và rõ ràng hơn hẳn.


  Dù vậy, ví dụ mà tác giả đưa ra trong cuốn sách cũng là một bài khởi động thú vị dành cho người đọc để tự đánh giá "góc nhìn kiểm thử" của bản thân. Trước khi sang các chương tiếp theo, hãy cũng "khởi động" ở phần cmt, cho tôi biết list TCs của bạn sẽ bao gồm những trường hợp nào của chương trình sau, đáp án và cách chấm điểm sẽ được cập nhật cùng chap 2.

```
The program reads three integer values from an input dialog. The three values represent the lengths of the sides of a triangle. The program displays a message that states whether the triangle is scalene, isosceles, or equilateral.
```

*Tạm dịch: Chương trình đọc ba giá trị số nguyên từ một hộp thoại đầu vào. Ba giá trị này đại diện cho độ dài các cạnh của một tam giác. Chương trình hiển thị một thông báo cho biết tam giác đó là tam giác thường, cân, hay đều.*




