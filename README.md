# Đồ án môn Nhận dạng thị giác và ứng dụng

## Giới thiệu

Đề tài "Low-Rank Adaptation for fine-tuning Stable Diffusion". Trong đề tài lần này, tôi sẽ giới thiệu mô hình Stable Diffusion và kỹ thuật Low-Rank Adapation để giảm chi phí và thời gian huấn luyện.

**Thành viên:**

Lê Trần Trọng Khiêm, mã HV 230101050

## Dataset

Để huấn luyện mô hình Stable Diffusion, cần chuẩn bị dữ liệu dưới dạng ảnh + caption.

Các bộ dữ liệu được sử dụng bao gồm:
- Lego: Norod78/lego-blip-captions-512
- Naruto: lambdalabs/naruto-blip-captions
- Logo: Babypotatotang/logo-captioning-blip
- Doodles: julianmoraes/doodles-captions-BLIP

Sau đó, dựa theo hướng dẫn [chính thức trên trang blog của HuggingFace](https://huggingface.co/blog/lora) để huấn luyện mô hình.
