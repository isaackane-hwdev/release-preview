# START32RF-E DevKit

![Platform](https://img.shields.io/badge/Platform-ESP32--S3-blue?style=flat-square&logo=espressif)
![Arduino](https://img.shields.io/badge/Arduino-Compatible-brightgreen?style=flat-square&logo=arduino)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Version](https://img.shields.io/badge/Version-1.0.0-orange?style=flat-square)

**Modern touch UI framework with real Frosted Glass effect for ESP32-S3**  
**Framework giao diện cảm ứng hiện đại với hiệu ứng Frosted Glass thật cho ESP32-S3**

A lightweight and extensible UI framework designed for 320×480 touch displays on ESP32-S3.  
Framework UI nhẹ, dễ mở rộng dành cho màn hình cảm ứng 320×480 trên ESP32-S3.

> 📱 iOS-like interaction on embedded hardware — smooth and responsive (~30 FPS with blur)  
> 📱 Trải nghiệm giống iOS trên phần cứng nhúng — mượt mà (~30 FPS với hiệu ứng blur)

---

## ✨ Highlights | Tính năng nổi bật

- **Frosted Glass Overlay**  
  Real blur + dim + tint effect (not fake alpha blending)  
  → Hiệu ứng mờ kính thật (blur + dim + tint), không phải alpha giả

- **Gesture Navigation**  
  Swipe-up-from-bottom with multi-level interaction  
  → Điều hướng bằng cử chỉ vuốt từ cạnh dưới, hỗ trợ nhiều cấp độ

- **App Grid Home**  
  Icon layout with auto text wrapping & ellipsis  
  → Trang chủ dạng icon, tự động xuống dòng và cắt chữ

- **Settings UI**  
  Smooth vertical scrolling with modern card design  
  → Trang cài đặt scroll mượt, thiết kế dạng card hiện đại

- **Dynamic Themes**  
  Dark / Light mode configurable via `app_config.h`  
  → Hỗ trợ Dark / Light, cấu hình nhanh qua `app_config.h`

- **Optimized Rendering**  
  Direct RGB565 processing (~22ms/frame with overlay)  
  → Tối ưu hiệu năng, xử lý trực tiếp RGB565 (~22ms/frame)

- **Modular Architecture**  
  Easy to extend with PageManager & Overlay system  
  → Kiến trúc module, dễ mở rộng thêm app/trang mới

---

## 📸 Demo

- Home screen with app grid  
- Frosted Glass overlay interaction  
- Gesture navigation  
- Scrollable settings UI  

*(Add GIF/video demo here)*  
*(Thêm GIF/video demo tại đây)*

---

## 🛠️ Hardware Requirements | Yêu cầu phần cứng

- **MCU**: ESP32-S3  
- **Display**: 320×480 RGB565 (ILI9488 / ST7796 hoặc tương tự)  
- **PSRAM**: Recommended 8MB+ (khuyến khích 8MB+)  
- **Touch**: Capacitive (GT911 / FT6336 hoặc tương tự)

---
