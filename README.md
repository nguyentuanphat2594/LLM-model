# Hỏi Đáp Tài Liệu Pandas Dựa Trên Mô Hình Ngôn Ngữ Lớn (LLM)

## Thông tin chung
**Chủ đề: Ứng dụng mô hình ngôn ngữ để hỏi đáp tài liệu**
Dữ liệu: Tài liệu PDF pandas.pdf
Mô hình: FLAN-T5 Large (transformers)
Thư viện chính: LangChain, FAISS, HuggingFace

## Mục tiêu
Xây dựng một hệ thống QA có khả năng:
Tiếp nhận file PDF (tài liệu Pandas)
Tách văn bản thành các đoạn ngắn
Dùng mô hình embedding sinh vector
Lưu trữ vector bằng FAISS
Dùng FLAN-T5 + LangChain truy vấn theo ng cảnh
Trả lời ngắn gọn theo phong cách trợ lý AI
