# Git & GitHub Learning Notes

## Module 1: Before Version Control

### 1. Diff & Patch
- `diff`: So sánh sự khác nhau giữa 2 file.
  - `-`: Nội dung bị xóa/thay đổi từ file cũ.
  - `+`: Nội dung mới được thêm vào ở file mới.

  ```bash
  diff -u rearrange1.py rearrange2.py
  ```
  
- Khái niệm này là nền tảng để Git theo dõi sự thay đổi (changes/deltas) trong code sau này.