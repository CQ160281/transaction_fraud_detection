# Transaction Fraud Detection

Model chống giả mạo giao dịch

# Một số khái niệm
- Fraud: trong ngân hàng được gọi là giao dịch giả  mạo (trong trường hợp bị mất thẻ mà kẻ trộm muốn sử dụng tiền trong thẻ).
- Normal: trong ngân hàng gọi là gia dịch thông thường.
- Autoencoder là mạng ANN có khả năng học hiệu quả các biểu diễn của dữ liệu input mà không cần label.

# Data attributes - Thuộc tính của dữ liệu.
- Time: Cột thời gian (tăng dần).
- v1 - v28: là các cột đã được làm mờ (dữ liệu ngân hàng quan trọng, không thể public ra bên ngoài). Có thể xem là các đặt tính của dữ liệu.
- Amount: Số tiền giao dịch.
- Class: Fraud: 1, Normal: 0

