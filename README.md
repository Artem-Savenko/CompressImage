# 🎵 CompressImage

A Qt-based C++ application featuring **custom lossless image compression algorithms** with detailed metrics and comparisons against standard formats. Some algorithms achieve up to **100x compression**, outperforming PNG in certain cases.

<img width="807" height="424" alt="Main window screenshot" src="https://github.com/user-attachments/assets/c9d51d2c-4274-461c-8286-68748ee27069" />

## 📍 Background

This project started as an experiment: I wanted to see if I could **reduce the size of my images** beyond standard formats. After designing custom load/save routines, I implemented algorithms that, for simple images like icons, **compress more efficiently than PNG**.

## ✨ Technologies

- C++  
- Qt  

## 🚀 Key Features

- Load common image types (PNG, JPEG, etc.)  
- Display image metadata: color count, dimensions, pixel count, original vs compressed size, compression ratios  
- Save/load custom compressed image format  
- Display images in the UI  
- 8 custom lossless compression algorithms  
- Custom `DynamicInt` type for memory-efficient storage  
- Compression ratios up to **100×**, sometimes surpassing PNG and JPEG  

## 👩🏻‍🎓 Skills & Learning

- UI design (title bar, buttons, dialogs)  
- Image rendering and interaction  
- File system integration  
- Designing and optimizing custom algorithms  
- Implementing a dynamic integer type  

## 🚀 Future Improvements

- CMake support for easier building and cross-platform compatibility  
- Full support for transparent images  
- Refined algorithm efficiency and edge-case handling  
- Suggestions welcome for new features or optimizations  

## 🎞️ Preview

https://github.com/user-attachments/assets/ce8d4895-0953-47a9-b89f-75b2f2aa5e2e
