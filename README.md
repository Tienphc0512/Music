# 🎵 Music App – Upload & Streaming MP3

Đồ án Lập Trình – Nhóm 4 người
Ứng dụng nghe nhạc và upload nhạc, gồm Mobile App (React Native – Expo) và Backend API (Node.js), sử dụng Cloudinary để lưu file nhạc và Firebase Firestore để lưu metadata.

## 👥 Thông tin nhóm

  - Số lượng thành viên: 4
  
  - Môn học: Lập trình ứng dụng
  
  - Loại đồ án: Mobile App + Backend API
  
  - Công nghệ chính: React Native (Expo), Node.js, Cloudinary, Firebase Firestore

## 📌 Mục tiêu dự án

* Cho phép người dùng:

  - Upload file nhạc (.mp3)
  
  - Lưu trữ nhạc trên cloud
  
  - Phát nhạc trực tiếp từ app Android

* Áp dụng kiến thức:

  - REST API
  
  - Cloud Storage
  
  - NoSQL Database
  
  - Mobile App Development

 ## Kiến trúc tổng thể
  [ Mobile App (Expo - Android) ]
            |
            |  HTTP (Axios)
            v
[ Node.js Upload API (Express) ]
            |
     ------------------
     |                |
Cloudinary        Firestore
(Lưu file mp3)   (Lưu metadata)

## Công nghệ sử dụng
📱 Frontend (Mobile App)

  - React Native
  
  - Expo SDK 53
  
  - Expo AV (phát nhạc)
  
  - Axios (gọi API)
  
  - Firebase Authentication
  
  - React Navigation

🌐 Backend (API Upload)

  - Node.js
  
  - Express.js
  
  - Multer (upload file)
  
  - Cloudinary SDK
  
  - Firebase Admin SDK
  
  - Firestore Database

## Kết quả đạt được

  - Upload nhạc thành công lên Cloudinary
  
  - Lưu dữ liệu bài hát vào Firestore
  
  - Phát nhạc trực tiếp trên ứng dụng Android
  
  - API hoạt động ổn định

## License

 - Dự án phục vụ mục đích học tập – không dùng cho thương mại.
