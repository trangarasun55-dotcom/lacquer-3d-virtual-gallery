# lacquer-3d-virtual-gallery

1. CẤU TRÚC THƯ MỤC
   📂 BlenderFiles/ (hoặc Source/)

- Dùng để: Chứa các file gốc .blend mà bạn đang làm dở.
- Tại sao cần: Để tách biệt file đang chỉnh sửa với các file thành phẩm, tránh bị rối mắt khi dự án có hàng chục model khác nhau.

📂 Textures/

- Dùng để: Chứa toàn bộ ảnh vật liệu (Color, Normal map, Roughness, ảnh gỗ, ảnh sơn mài...).
- Tại sao cần: Blender và Unity quản lý ảnh theo đường dẫn. Gom hết ảnh vào đây giúp quản lý tập trung và không bị thất lạc file ảnh.

📂 Exports/ (hoặc FBX/)

- Dùng để: Chứa các file định dạng .fbx hoặc .obj sau khi bạn đã dựng xong và xuất ra (export) để gửi cho lập trình viên Unity.
- Tại sao cần: Người làm VR/Unity chỉ cần vào đây lấy file .fbx về dùng, họ không cần đụng vào file .blend gốc của bạn.

📂 References/

- Dùng để: Chứa ảnh mẫu, ý tưởng vẽ tranh sơn mài hoặc không gian phòng triển lãm ảo mà bạn thu thập trên mạng để nhìn theo lúc dựng hình.
