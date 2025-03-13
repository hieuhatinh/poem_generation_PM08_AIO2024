# Project: Poem Generation - PM08 - AIO2024

Project này triển khai một chương trình sử dụng mô hình Text Generation với chủ đề sinh thơ Tiếng Việt, chủ yếu là thể thơ năm chữ dựa vào một từ tiếng Việt đầu vào
 từ người dùng. **Input/Output** của chương trình là:
 - **Input:** Một chuỗi gồm các kí tự mở đầu cho bài thơ.
 - **Output:** Bài thơ hoàn chỉnh.

!["Pipeline Poem Generation using GPT-2"](/readme_img/pipeline.png "AIO2024")

Project này sử dụng mô hình GPT-2 pre-trained và thực hiện fine-tuning với tập dữ liệu thơ tiếng việt được Crawl từ trang web [thivien.net](https://www.thivien.net/) sử dụng thư viện Selenium của python