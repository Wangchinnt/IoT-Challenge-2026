# 🏥 IOT CHALLENGE 2026 - SMART HEALTHCARE WITH EDGE AI
## Hướng Dẫn Toàn Diện Từ Thể Lệ Đến Triển Khai

---

## 📋 PHẦN 1: TỔNG QUAN CUỘC THI

### Thông Tin Cơ Bản
| Thuộc tính | Chi tiết |
|------------|----------|
| **Tên cuộc thi** | IoT Challenge 2026 - Smart Healthcare with Edge AI |
| **Quy mô** | Toàn cầu (Việt Nam, Hungary, Vương quốc Anh, Ấn Độ) |
| **Đối tượng** | Sinh viên năm 3-4 ngành IoT, Embedded Systems & Engineering |
| **Số thành viên** | 3-5 ngườí/đội |
| **Tổng giải thưởng** | 5,000 USD |
| **Nhà tài trợ** | FPT Software & Silicon Labs (USA) |

### Chủ Đề
> **"Smart Healthcare with Edge AI"** - Giải pháp chăm sóc sức khỏe thông minh với AI tại biên

### Mục Tiêu Cuộc Thi
- Thiết bị & hệ thống giám sát sức khỏe thông minh
- Phát hiện sớm và phản hồi theo thờí gian thực
- Ứng dụng AI trực tiếp trên thiết bị biên (Edge Devices)
- Đảm bảo độ trễ thấp, bảo mật cao, vận hành ổn định trong môi trường kết nối hạn chế

---

## ⚠️ PHẦN 2: YÊU CẦU KỸ THUẬT BẮT BUỘC

### 1. Hardware Requirements
| Yêu cầu | Chi tiết | Mức độ |
|---------|----------|--------|
| **Silicon Labs Chip** | Bắt buộc dùng EFR32 hoặc EFM32 series | 🔴 Bắt buộc |
| **Wireless Connectivity** | Ít nhất 1: BLE/Zigbee/Thread/Matter/Wi-SUN | 🔴 Bắt buộc |
| **Edge AI** | Phải có AI/ML chạy trên Silicon Labs chip | 🔴 Bắt buộc |
| **Components bổ sung** | Có thể thêm: Raspberry Pi, sensors, cloud, mobile apps | 🟢 Tùy chọn |

### 2. Software & Documentation Requirements
| Yêu cầu | Chi tiết | Mức độ |
|---------|----------|--------|
| **Source Code License** | Apache License 2.0 | 🔴 Bắt buộc |
| **Ngôn ngữ** | Tất cả code, tài liệu, presentation bằng **Tiếng Anh** | 🔴 Bắt buộc |
| **GitHub Repository** | Source code sẽ được review bởi mentors | 🔴 Bắt buộc |
| **Code Quality** | Tuân thủ coding standards, có documentation | 🟡 Khuyến nghị |

### 3. GitHub Repository Chính Thức
🔗 **Silicon Labs Sandbox:** https://github.com/SiliconLabsSandBox

---

## 🔧 PHẦN 3: ECOSYSTEM SILICON LABS CẦN BIẾT

### Dev Kits Khuyến Nghị (Có thể bị thay đổi phụ thuộc vào ban tổ chức, cần lưu ý)

| Dev Kit | Tính năng | Giá ~ | Phù hợp cho |
|---------|-----------|-------|-------------|
| **EFR32xG24 Dev Kit or newest** | AI/ML hardware accelerator, multi-protocol wireless | $79 | Tất cả ideas |
| **EFR32xG24 Explorer Kit or newest** | Basic dev, BLE/Zigbee/Thread | $35 | Prototyping |
| **SparkFun Thing Plus MGM240P or newest** | Arduino-compatible, Qwiic sensors | $25 | Rapid prototyping |
| **Seeed Studio XIAO MG24 Sense or newest** | Siêu nhỏ gọn, có IMU built-in | $15 | Wearable projects |

### Software Development Kit (SDK)

```
📦 Gecko SDK Suite (GSDK)
├── 📁 platform - CMSIS, drivers, peripheral
├── 📁 protocol - Bluetooth, Zigbee, Thread, Matter
├── 📁 hardware - Kit drivers, config
└── 📁 ml - TensorFlow Lite Micro, model deployment
```

### Repositories Quan Trọng

| Repository | Mô tả | Link |
|------------|-------|------|
| **machine_learning_applications** | Code mẫu ML: keyword spotting, sensor inference | siliconlabs/machine_learning_applications |
| **application_examples** | Ứng dụng mẫu đầy đủ | siliconlabs/application_examples |
| **peripheral_examples** | Examples cho GPIO, ADC, I2C, SPI | siliconlabs/peripheral_examples |
| **bluetooth_stack** | Bluetooth LE stack | siliconlabs/bluetooth_stack |

### Wireless Protocols Hỗ Trợ

| Protocol | Ưu điểm | Use Case Phù Hợp |
|----------|---------|------------------|
| **BLE 5.x** | Tiết kiệm pin, smartphone compatible | Wearables, patient monitoring |
| **Zigbee** | Mesh network, nhiều nodes | Hospital room monitoring |
| **Thread** | IP-based, secure | Smart hospital infrastructure |
| **Matter** | Interoperability | Multi-vendor integration |
| **Wi-SUN** | Long range, outdoor | Remote patient monitoring |

### Frameworks & Tools

| Tool | Mục đích |
|------|----------|
| **Simplicity Studio 5** | IDE chính thức của Silicon Labs |
| **TensorFlow Lite Micro** | Framework ML cho MCU |
| **Edge Impulse** | Platform no-code/low-code ML cho edge |
| **Simplicity Commander** | Flash, debug, config |

---

## 💡 PHẦN 4: 10 Ý TƯỞNG CHI TIẾT

### 📊 Tổng Quan So Sánh

| # | Ý Tưởng | Nhóm | Độ Khó | Độc Đáo | Tiềm Năng | Paper Mới Nhất |
|---|---------|------|--------|---------|-----------|----------------|
| 1 | ECG Arrhythmia + BLE | Cardio | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐ | 2025 |
| 2 | Cuffless Blood Pressure | Cardio | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | 2023 |
| 3 | Tiny Transformer Fall Detection | Safety | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | 2024 |
| 4 | Medication Adherence (Vision) | Medication | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | - |
| 5 | Federated Learning Multi-Patient | Advanced | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | 2025 |
| 6 | Cough Detection + Respiratory | Respiratory | ⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | 2024 |
| 7 | Sleep Apnea Screening | Sleep | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | 2026 |
| 8 | Thermal Fever + Occupancy | Safety | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | 2025 |
| 9 | Multi-Parameter Health SoC | Cardio | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | 2026 |
| 10 | BCG Non-Contact Monitoring | Advanced | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | 2026 |

---

### 🫀 NHÓM 1: CARDIOVASCULAR MONITORING

#### Idea 1: ECG Arrhythmia Detection + BLE Transmission

**📚 Cơ Sở Khoa Học**
- Paper: "Reliable ECG anomaly detection on edge devices for Internet of Medical Things applications" (MDPI Sensors, 2025)
- Dataset: MIT-BIH Arrhythmia Database (gold standard)
- Phương pháp: CNN/RNN đã được tối ưu cho MCU

**🎯 Giá Trị Mới Của Bạn**
1. Multi-lead ECG (3 leads thay vì 1 lead thông thường)
2. Federated learning để cải thiện model theo thờí gian
3. Real-time alert qua BLE 5.0 đến smartphone/central hub

**🔧 Hardware Stack**
```
[EFR32xG24] ←── I2C/SPI ──→ [AD8232 ECG Module]
       ↓
   [BLE 5.0] → Smartphone/Hospital Hub
```

| Component | Chi phí ~ | Link mua |
|-----------|-----------|----------|
| EFR32xG24 Dev Kit | $79 | Silicon Labs/DigiKey |
| AD8232 ECG Module | $15 | SparkFun/Adafruit |
| Electrodes (10pcs) | $5 | Amazon |
| **Tổng** | **~$100** | |

**✅ Điểm Mạnh**
- Dataset sẵn có, không cần thu thập
- Thuật toán đã được validate nhiều lần
- Demo dễ thực hiện tại chỗ

**❌ Thách Thức**
- Cần hiểu biết về signal processing
- ECG nhạy cảm với motion artifact
- Regulatory (FDA) nếu muốn commercialize

**📈 Đánh Giá**
| Tiêu chí | Score | Lý do |
|----------|-------|-------|
| Độ khó | ⭐⭐⭐ | Signal processing + ML |
| Độc đáo | ⭐⭐⭐ | Nhiều team sẽ chọn |
| Tiềm năng TM | ⭐⭐⭐⭐ | Thị trường lớn |
| Khả thi 8 tuần | ⭐⭐⭐⭐ | Hoàn toàn khả thi |

---

#### Idea 2: Cuffless Blood Pressure Estimation (PPG + ECG)

**📚 Cơ Sở Khoa Học**
- Paper 1: "The case for tinyML in healthcare: CNNs for real-time on-edge blood pressure estimation" (ACM 2023)
- Paper 2: "tinycare: Continuous blood pressure estimation using PPG + ECG" (2022)
- Phương pháp: Pulse Transit Time (PTT) - thờí gian sóng áp huyết từ tim đến ngón tay

**🎯 Giá Trị Mới Của Bạn**
1. **Motion artifact rejection**: Dùng accelerometer để phát hiện và loại bỏ khi ngườí dùng di chuyển
2. **Auto-calibration**: Dùng smartphone camera (PPG-based) để calibrate 1 lần
3. **Continuous monitoring**: Đo liên tục 24/7 thay vì snapshot

**🔧 Hardware Stack**
```
[EFR32xG24]
    ├── I2C → [MAX30102] (PPG + SpO2)
    ├── Analog → [AD8232] (ECG)
    └── I2C → [MPU6050] (Accelerometer)

    BLE → Smartphone (Calibration + Display)
```

| Component | Chi phí ~ |
|-----------|-----------|
| EFR32xG24 Dev Kit | $79 |
| MAX30102 Module | $8 |
| AD8232 Module | $15 |
| MPU6050 Module | $3 |
| **Tổng** | **~$105** |

**✅ Điểm Mạnh**
- Holy grail của wearable health (1.3 tỷ ngườí bị tăng huyết áp)
- Chưa có sản phẩm commercial thực sự chính xác
- Cuffless = thoải mái, continuous monitoring

**❌ Thách Thức**
- Calibration vẫn là vấn đề chưa giải quyết tốt
- Cần so sánh với máy đo huyết áp y tế (ground truth)
- Motion artifact là enemy #1

**📈 Đánh Giá**
| Tiêu chí | Score | Lý do |
|----------|-------|-------|
| Độ khó | ⭐⭐⭐⭐ | Calibration + Sensor fusion |
| Độc đáo | ⭐⭐⭐⭐ | Motion rejection là mới |
| Tiềm năng TM | ⭐⭐⭐⭐⭐ | Cực kỳ lớn |
| Khả thi 8 tuần | ⭐⭐⭐ | Khó nhất trong 10 ideas |

---

### 🚨 NHÓM 2: SAFETY & EMERGENCY

#### Idea 3: Smart Fall Detection với Tiny Transformer

**📚 Cơ Sở Khoa Học**
- Paper: "Edge computing transformers for fall detection in older adults" (2024)
- Kiến trúc: Tiny Inertial Transformer từ Nature 2025
- So sánh: Transformer > CNN/RNN cho time-series IMU data

**🎯 Giá Trị Mới Của Bạn**
1. **Fall PREDICTION** không chỉ detection: Phát hiện trước khi té (loss of balance pattern)
2. Multi-modal: Accelerometer + Barometer (độ cao) + Microphone (tiếng va chạm)
3. First team dùng Transformer ở cuộc thi sinh viên

**🔧 Hardware Stack**
```
[EFR32xG24 - XIAO MG24 Sense]
    ├── Built-in IMU (Accelerometer + Gyroscope)
    ├── I2C → [BMP280] (Barometer - độ cao)
    └── Analog → [MEMS Mic] (Sound detection)

    Zigbee/BLE → Alert to caregiver
```

| Component | Chi phí ~ |
|-----------|-----------|
| XIAO MG24 Sense | $15 |
| BMP280 Barometer | $3 |
| MEMS Microphone | $2 |
| Vibration Motor | $2 |
| **Tổng** | **~$22** |

**✅ Điểm Mạnh**
- Hardware cực rẻ và đơn giản
- Transformer đang trending, reviewers sẽ ấn tượng
- Có thể demo ngay tại chỗ

**❌ Thách Thức**
- Transformer cần nhiều compute hơn CNN
- Phải thu thập data fall (có thể simulate)
- False positive cần tối ưu

**📈 Đánh Giá**
| Tiêu chí | Score | Lý do |
|----------|-------|-------|
| Độ khó | ⭐⭐⭐⭐ | Transformer on MCU |
| Độc đáo | ⭐⭐⭐⭐ | Fall prediction là mới |
| Tiềm năng TM | ⭐⭐⭐⭐ | Aging population |
| Khả thi 8 tuần | ⭐⭐⭐⭐ | Khá khả thi |

---

#### Idea 8: Thermal Camera Fever + Occupancy Detection

**📚 Cơ Sở Khoa Học**
- Paper 1: "Real-Time Thermal and Weight Monitoring for Patient Screening" (IEEE 2025)
- Paper 2: "Edge computing with embedded AI: Thermal image analysis for occupancy" (ACM 2019, 60 citations)

**🎯 Giá Trị Mới Của Bạn**
1. **Privacy-preserving**: Thermal camera (không nhận diện khuôn mặt) thay vì RGB
2. Breathing rate estimation từ thermal: Phát hiện vùng mũi/miệng nóng lạnh theo nhịp thở
3. Fall detection từ thermal: Phát hiện ngườí nằm bất thường

**🔧 Hardware Stack**
```
[EFR32xG24]
    └── I2C → [MLX90640] (32x24 Thermal Array)

    Matter/Zigbee → Smart Hospital System
```

| Component | Chi phí ~ |
|-----------|-----------|
| EFR32xG24 Dev Kit | $79 |
| MLX90640 (32x24) | $60 |
| Lens for MLX90640 | $15 |
| **Tổng** | **~$155** |

**✅ Điểm Mạnh**
- Thermal = privacy (quan trọng cho bệnh viện)
- Một camera làm nhiều việc: fever + occupancy + breathing + fall
- Có thể tích hợp với HVAC (điều hòa) qua Matter

**❌ Thách Thức**
- Giá MLX90640 khá cao
- Resolution thấp (32x24) cần ML để interpret
- Cần hiểu về thermal imaging

**📈 Đánh Giá**
| Tiêu chí | Score | Lý do |
|----------|-------|-------|
| Độ khó | ⭐⭐⭐⭐ | Thermal + Image processing |
| Độc đáo | ⭐⭐⭐⭐ | Multi-function thermal |
| Tiềm năng TM | ⭐⭐⭐⭐ | Post-COVID fever screening |
| Khả thi 8 tuần | ⭐⭐⭐ | Hardware đắt, khó mua |

---

### 🫁 NHÓM 3: RESPIRATORY & SLEEP

#### Idea 6: Cough Detection + Respiratory Disease Screening

**📚 Cơ Sở Khoa Học**
- Paper: "A TinyML motion-based embedded cough detection system" (IEEE 2024, 6 citations)
- Phương pháp: Multi-modal - microphone (sound) + accelerometer (chest vibration)

**🎯 Giá Trị Mới Của Bạn**
1. Multi-modal fusion: Sound + vibration + SpO2
2. Cough classification: Ho khan / ho có đờm / ho liên tục
3. Automated Cough Diary cho bác sĩ (qua BLE sync)

**🔧 Hardware Stack**
```
[EFR32xG24]
    ├── Analog → [MEMS Microphone]
    ├── I2C → [MPU6050] (Chest vibration)
    └── I2C → [MAX30102] (SpO2)

    BLE → Cough Diary App
```

| Component | Chi phí ~ |
|-----------|-----------|
| EFR32xG24 Dev Kit | $79 |
| MAX30102 | $8 |
| MPU6050 | $3 |
| MEMS Mic | $2 |
| **Tổng** | **~$92** |

**✅ Điểm Mạnh**
- COPD/Asthma/Post-COVID monitoring thị trường lớn
- Dễ demo (có thể ho giả tại chỗ)
- Dataset cough có sẵn (Coswara, etc.)

**❌ Thách Thức**
- Phân biệt ho vs. tiếng ồn khó khăn
- Cần nhiều data để generalize

**📈 Đánh Giá**
| Tiêu chí | Score | Lý do |
|----------|-------|-------|
| Độ khó | ⭐⭐⭐ | Audio + Motion |
| Độc đáo | ⭐⭐⭐⭐ | Multi-modal là mới |
| Tiềm năng TM | ⭐⭐⭐⭐ | Post-COVID demand |
| Khả thi 8 tuần | ⭐⭐⭐⭐⭐ | Rất khả thi |

---

#### Idea 7: Sleep Apnea Screening Wearable

**📚 Cơ Sở Khoa Học**
- Paper 1: "Low-Cost IoT-Integrated Wearable Platform for Home-Based Sleep Apnea Screening" (IEEE 2026)
- Paper 2: "AI-Driven Vibro-Thermal Neckpad for Personalized Insomnia Therapy" (IEEE 2025)
- Thị trường: 1 tỷ ngườí ngáy, 100M+ bị Sleep Apnea, PSG đắt và bất tiện

**🎯 Giá Trị Mới Của Bạn**
1. **Haptic feedback**: Rung nhẹ khi phát hiện ngừng thở >10s để kích thích thở lại
2. Multi-modal: SpO2 + sound (ngáy) + movement
3. Sleep stage detection từ HR variability

**🔧 Hardware Stack**
```
[EFR32xG24]
    ├── I2C → [MAX30102] (SpO2 + HR)
    ├── Analog → [MEMS Mic] (Ngáy detection)
    ├── I2C → [MPU6050] (Movement)
    └── GPIO → [Vibration Motor] (Haptic feedback)

    BLE → Sleep Report App
```

| Component | Chi phí ~ |
|-----------|-----------|
| EFR32xG24 Dev Kit | $79 |
| MAX30102 | $8 |
| MPU6050 | $3 |
| MEMS Mic | $2 |
| Vibration Motor | $2 |
| **Tổng** | **~$94** |

**✅ Điểm Mạnh**
- PSG ($1000+) vs. Wearable ($100) - value proposition rõ ràng
- Wearable hiện tại (Apple Watch) chưa đủ chính xác
- Thị trường khổng lồ nhưng underserved

**❌ Thách Thức**
- Cần validate với PSG (gold standard)
- Comfort khi đeo ngủ cả đêm
- Pin life (cần >8h)

**📈 Đánh Giá**
| Tiêu chí | Score | Lý do |
|----------|-------|-------|
| Độ khó | ⭐⭐⭐⭐ | Multi-modal fusion |
| Độc đáo | ⭐⭐⭐⭐ | Haptic feedback là mới |
| Tiềm năng TM | ⭐⭐⭐⭐⭐ | Thị trường khổng lồ |
| Khả thi 8 tuần | ⭐⭐⭐⭐ | Khá khả thi |

---

### 🔬 NHÓM 4: ADVANCED/RESEARCH-ORIENTED

#### Idea 5: Federated Learning Multi-Patient Monitoring

**📚 Cơ Sở Khoa Học**
- Paper: "Edge-Optimized Federated Learning for Real-Time Patient Monitoring" (IEEE 2025)
- Paper 2: "Federated learning and edge AI for privacy-preserving diabetes prediction" (IEEE 2025)
- Concept: Học chung từ nhiều bệnh nhân mà không chia sẻ raw data

**🎯 Giá Trị Mới Của Bạn**
1. **Privacy-preserving**: Hospital có thể dùng mà không lo HIPAA violation
2. **Personalization layer**: Model tự điều chỉnh cho từng ngườí sau 7 ngày
3. **Mesh network**: Zigbee/Matter để tạo hospital-wide monitoring

**🔧 Hardware Stack (Mỗi Patient Node)**
```
[EFR32xG24]
    ├── I2C → [MAX30102] (HR + SpO2)
    ├── I2C → [MLX90614] (Temperature)
    └── Zigbee/Matter → [Gateway] → [Cloud FL Server]
```

| Component | Chi phí ~ |
|-----------|-----------|
| EFR32xG24 Dev Kit | $79 |
| MAX30102 | $8 |
| MLX90614 | $10 |
| **Tổng/node** | **~$97** |

**Architecture**
```
Patient 1 (EFR32) ──┐
Patient 2 (EFR32) ──┼──→ Gateway (Raspberry Pi) ──→ FL Server
Patient 3 (EFR32) ──┘       (Local aggregation)       (Global model)
```

**✅ Điểm Mạnh**
- Federated Learning còn rất mới ở cuộc thi sinh viên
- Privacy là hot topic trong healthcare
- Scalable từ 1 ngườí đến hospital-wide

**❌ Thách Thức**
- Cần hiểu sâu về FL algorithms
- Setup infrastructure phức tạp hơn
- Nhiều node để demo FL thực sự

**📈 Đánh Giá**
| Tiêu chí | Score | Lý do |
|----------|-------|-------|
| Độ khó | ⭐⭐⭐⭐⭐ | FL + Distributed systems |
| Độc đáo | ⭐⭐⭐⭐⭐ | Cực kỳ mới |
| Tiềm năng TM | ⭐⭐⭐⭐⭐ | Privacy-preserving AI |
| Khả thi 8 tuần | ⭐⭐⭐ | Phức tạp nhất |

---

#### Idea 10: BCG Non-Contact Heart Monitoring ⭐ **TOP PICK**

**📚 Cơ Sở Khoa Học**
- Paper: "On-chip Processing Assisted TinyML for Heart Rate Monitoring Using Non-Contact Ballistocardiogram-Based Bed Sensor" (IEEE 2026 - **MỚI NHẤT!**)
- BCG: Đo rung động do máu bơm qua tim, **không cần đeo thiết bị**

**🎯 Giá Trị Mới Của Bạn**
1. **Dual-sensor triangulation**: 2 piezoelectric sensors (đầu + chân giường) để loại nhiễu
2. **Motion artifact rejection**: Tự động pause khi phát hiện chuyển động lớn
3. **In-bed monitoring**: Dành cho ngườí già không muốn đeo wearable

**🔧 Hardware Stack**
```
[EFR32xG24]
    ├── Analog → [Piezo Sensor 1] (Đầu giường)
    ├── Analog → [Piezo Sensor 2] (Chân giường)
    └── Zigbee → Alert system
```

| Component | Chi phí ~ |
|-----------|-----------|
| EFR32xG24 Dev Kit | $79 |
| Piezo Sensors x2 | $10 |
| Load Cells (optional) | $15 |
| **Tổng** | **~$105** |

**✅ Điểm Mạnh**
- **Độc đáo nhất trong 10 ideas** - Chưa ai làm ở cuộc thi sinh viên
- Paper IEEE 2026 vừa ra - cực kỳ trending
- Giải quyết vấn đề "ngườí già không thích đeo thiết bị"

**❌ Thách Thức**
- Signal rất yếu, cần amplifier tốt
- Nhiễu từ chuyển động khó loại bỏ
- Cần giường để demo

**📈 Đánh Giá**
| Tiêu chí | Score | Lý do |
|----------|-------|-------|
| Độ khó | ⭐⭐⭐⭐⭐ | Weak signal processing |
| Độc đáo | ⭐⭐⭐⭐⭐ | Cực kỳ unique |
| Tiềm năng TM | ⭐⭐⭐⭐⭐ | Geriatric care |
| Khả thi 8 tuần | ⭐⭐⭐ | Cần experiment nhiều |

---

### 💊 NHÓM 5: MEDICATION & VISION

#### Idea 4: Medication Adherence (Vision + NFC)

**🎯 Giá Trị Mới Của Bạn**
1. **Object detection nhẹ**: Nhận diện loại thuốc (viên tròn/vuông, màu sắc)
2. **NFC cho ngườí già**: Chỉ cần chạm thẻ NFC vào thiết bị, không cần thao tác phức tạp
3. **Smart reminder**: Nhắc nhở đúng giờ, theo dõi adherence rate

**🔧 Hardware Stack**
```
[EFR32xG24]
    ├── I2C → [HM01B0] (320x320 Camera - siêu nhỏ)
    ├── SPI → [PN532] (NFC Reader)
    └── BLE → Caregiver notification
```

| Component | Chi phí ~ |
|-----------|-----------|
| EFR32xG24 Dev Kit | $79 |
| HM01B0 Camera | $15 |
| PN532 NFC | $10 |
| NFC Tags (10pcs) | $5 |
| **Tổng** | **~$110** |

**✅ Điểm Mạnh**
- **Ít team nghĩ đến** - vision trong healthcare IoT
- NFC làm cho UX dễ dàng cho elderly
- Adherence là vấn đề billion-dollar

**❌ Thách Thức**
- Vision on MCU khó khăn (low resolution)
- Cần train model nhận diện thuốc
- Lighting conditions ảnh hưởng

**📈 Đánh Giá**
| Tiêu chí | Score | Lý do |
|----------|-------|-------|
| Độ khó | ⭐⭐⭐⭐ | Tiny vision |
| Độc đáo | ⭐⭐⭐⭐⭐ | Rất ít ngườí làm |
| Tiềm năng TM | ⭐⭐⭐⭐ | Adherence market |
| Khả thi 8 tuần | ⭐⭐⭐ | Vision khó nhanh |

---

#### Idea 9: Multi-Parameter Health SoC (All-in-One)

**📚 Cơ Sở Khoa Học**
- Paper: "Design and Implementation of a Multi-Parameter Health Monitoring SoC using RISC-V and TinyML" (IEEE 2026)
- Sensor fusion để tính các chỉ số phức tạp

**🎯 Các Chỉ Số Đo Được**
1. **HR, SpO2** - từ MAX30102
2. **Body Temperature** - từ MLX90614
3. **HRV (Heart Rate Variability)** - chỉ số stress/recovery
4. **PWV (Pulse Wave Velocity)** - độ đàn hồi mạch máu
5. **Sleep stages** - từ HR + movement

**🔧 Hardware Stack**
```
[EFR32xG24]
    ├── I2C → [MAX30102] (PPG + SpO2)
    ├── I2C → [MLX90614] (Temp)
    ├── I2C → [MPU6050] (Movement)
    └── BLE → Dashboard App
```

| Component | Chi phí ~ |
|-----------|-----------|
| EFR32xG24 Dev Kit | $79 |
| MAX30102 | $8 |
| MLX90614 | $10 |
| MPU6050 | $3 |
| **Tổng** | **~$100** |

**✅ Điểm Mạnh**
- One device, nhiều use cases
- Sensor fusion cho insights sâu hơn
- Dễ commercialize (fitness + medical)

**❌ Thách Thức**
- Nhiều sensors = phức tạp hơn
- Power consumption
- "Jack of all trades" risk

**📈 Đánh Giá**
| Tiêu chí | Score | Lý do |
|----------|-------|-------|
| Độ khó | ⭐⭐⭐⭐ | Multi-sensor fusion |
| Độc đáo | ⭐⭐⭐ | Nhiều ngườí làm all-in-one |
| Tiềm năng TM | ⭐⭐⭐⭐⭐ | Consumer health |
| Khả thi 8 tuần | ⭐⭐⭐⭐ | Khá khả thi |

---

## 🎯 PHẦN 5: KHUYẾN NGHỊ CHỌN Ý TƯỞNG

### Theo Tiêu Chí Cụ Thể

| Nếu bạn muốn... | Hãy chọn | Lý do |
|----------------|----------|-------|
| 🏆 **Đoạt giải cao** (độc đáo nhất) | Idea 10: BCG hoặc Idea 5: Federated Learning | Chưa ai làm, trending topic |
| ✅ **Chắc ăn, dễ demo** | Idea 6: Cough hoặc Idea 7: Sleep Apnea | Hardware đơn giản, demo tại chỗ |
| 💰 **Thương mại hóa sau cuộc thi** | Idea 2: Cuffless BP hoặc Idea 9: Multi-Parameter | Thị trường rõ ràng, khách trả tiền |
| 🤖 **Leverage kinh nghiệm ML** | Idea 3: Tiny Transformer Fall Detection | State-of-the-art architecture |
| 🔧 **Leverage kinh nghiệm Embedded** | Idea 1: ECG hoặc Idea 8: Thermal | Signal processing, hardware focus |
| 👴 **Giúp ngườí già** | Idea 10: BCG hoặc Idea 4: Medication | Non-contact, elderly-friendly |
| 🏥 **Hospital deployment** | Idea 5: Federated Learning hoặc Idea 8: Thermal | Scalable, privacy-compliant |

### Khuyến Nghị Theo Thờí Gian Có

| Thờí gian còn lại | Ý tưởng phù hợp | Lý do |
|-------------------|-----------------|-------|
| **< 6 tuần** | Idea 1, 6 | Code mẫu sẵn, dễ triển khai |
| **6-10 tuần** | Idea 2, 3, 7 | Cần thờí gian cho data collection |
| **> 10 tuần** | Idea 5, 10 | Phức tạp, cần experiment nhiều |

---

## 📅 PHẦN 6: LỘ TRÌNH THỰC HIỆN (8 TUẦN)

### Tuần 1-2: Research & Hardware Setup
**Mục tiêu**: Có prototype hardware chạy được

| Ngày | Task | Output |
|------|------|--------|
| 1-3 | Đọc papers liên quan | Summary notes |
| 4-5 | Order hardware | Tracking numbers |
| 6-7 | Setup Simplicity Studio | Blink LED thành công |
| 8-10 | Test từng sensor riêng lẻ | Sensor readings valid |
| 11-14 | Tích hợp hardware hoàn chỉnh | Prototype v0.1 |

### Tuần 3-4: Data Collection & Model Training
**Mục tiêu**: Có model chạy trên PC với accuracy >85%

| Ngày | Task | Output |
|------|------|--------|
| 15-18 | Thu thập/clean data | Dataset ready |
| 19-21 | Train model (Python/TensorFlow) | Model .h5 file |
| 22-24 | Validate model | Accuracy report |
| 25-28 | Convert to TFLite | .tflite file |

### Tuần 5-6: Edge Deployment & Optimization
**Mục tiêu**: Model chạy trên EFR32 với latency <1s

| Ngày | Task | Output |
|------|------|--------|
| 29-32 | Integrate TFLite Micro | Build thành công |
| 33-35 | Optimize model (quantization) | Model nhỏ hơn 256KB |
| 36-38 | Test latency & accuracy | Performance report |
| 39-42 | Debug và optimize | v0.9 working |

### Tuần 7-8: Integration & Demo Preparation
**Mục tiêu**: Demo hoàn chỉnh, tài liệu đầy đủ

| Ngày | Task | Output |
|------|------|--------|
| 43-45 | Wireless connectivity | BLE/Zigbee hoạt động |
| 46-49 | Mobile app/dashboard (nếu cần) | UI hoàn chỉnh |
| 50-53 | Viết documentation | README + Report |
| 54-56 | Quay video demo | Demo video |
| 57-60 | Final polish & submit | All deliverables |

---

## 📚 PHẦN 7: RESOURCES CẦN THIẾT

### Datasets Công Khai

| Dataset | Dùng cho | Link |
|---------|----------|------|
| **MIT-BIH Arrhythmia** | ECG classification | physionet.org/content/mitdb |
| **PhysioNet** | Đa dạng physiological signals | physionet.org |
| **MIMIC-III** | ICU data (cần apply) | mimic.physionet.org |
| **Coswara** | Cough sounds | github.com/iiscleap/Coswara-Data |
| **UCI ML Repository** | Various health datasets | archive.ics.uci.edu/ml |
| **Edge Impulse Datasets** | Pre-built for tinyML | edgeimpulse.com |

### Tools & Platforms

| Tool | Mục đích | Link |
|------|----------|------|
| **Simplicity Studio 5** | IDE cho Silicon Labs | silabs.com/simplicity-studio |
| **TensorFlow Lite Micro** | ML framework | tensorflow.org/lite/microcontrollers |
| **Edge Impulse Studio** | No-code ML platform | edgeimpulse.com |
| **Google Colab** | Train model miễn phí | colab.research.google.com |
| **Kaggle** | Datasets + Notebooks | kaggle.com |
| **STM32Cube.AI** | Alternative tool | stm32ai.st.com |

### Tài Liệu Tham Khảo

| Tài liệu | Mô tả |
|----------|-------|
| Silicon Labs ML User Guide | Hướng dẫn deploy model |
| EFR32xG24 Reference Manual | Technical specs |
| TensorFlow Lite for Microcontrollers Book | Pete Warden & Daniel Situnayake |
| TinyML Book | Hariharan Ganesan |

### Community & Support

| Resource | Link |
|----------|------|
| Silicon Labs Community | community.silabs.com |
| TinyML Foundation | tinyml.org |
| Edge AI + Vision Alliance | edge-ai-vision.com |
| Reddit r/tinyML | reddit.com/r/tinyML |

---

## ✅ PHẦN 8: CHECKLIST TRƯỚC KHI NỘP

### Technical Requirements Checklist

- [ ] **Silicon Labs Chip**: Sử dụng EFR32 hoặc EFM32 series
- [ ] **Wireless Connectivity**: BLE/Zigbee/Thread/Matter/Wi-SUN hoạt động
- [ ] **Edge AI**: Model chạy trực tiếp trên Silicon Labs chip (không phải cloud)
- [ ] **Code Quality**: Clean, documented, well-structured
- [ ] **Apache 2.0 License**: File LICENSE đúng format

### Documentation Checklist

- [ ] **README.md**: Project overview, setup instructions, usage
- [ ] **Technical Report**: Design decisions, methodology, results
- [ ] **Code Comments**: Inline documentation
- [ ] **API Documentation** (nếu có): Endpoints, parameters
- [ ] **All in English**: Không có tiếng Việt trong code/docs

### Demo Checklist

- [ ] **Video Demo**: 3-5 phút, show workflow hoàn chỉnh
- [ ] **Live Demo Ready**: Có thể demo tại chỗ nếu cần
- [ ] **Test Cases**: Các scenario đã test
- [ ] **Performance Metrics**: Accuracy, latency, power consumption

### GitHub Repository Checklist

- [ ] **Public Repository**: Mentors có thể access
- [ ] **Complete Source Code**: Không thiếu file
- [ ] **Build Instructions**: Cách compile và flash
- [ ] **Hardware List**: BOM (Bill of Materials)
- [ ] **Schematics** (nếu custom PCB): KiCad/EasyEDA files

### Final Review

- [ ] **Test lần cuối**: Everything works end-to-end
- [ ] **Proofread**: Không có lỗi chính tả
- [ ] **Video xem lại**: Audio clear, visual clear
- [ ] **Backup**: Lưu trữ nhiều nơi

---

## 🏆 PHẦN 9: TOP 3 KHUYẾN NGHỊ CUỐI CÙNG

Dựa trên phân tích toàn diện, đây là 3 ý tưởng tôi khuyến nghị cao nhất:

### 🥇 #1: BCG Non-Contact Heart Monitoring (Idea 10)
**Độc đáo**: ⭐⭐⭐⭐⭐ | **Tiềm năng**: ⭐⭐⭐⭐⭐ | **Độ khó**: ⭐⭐⭐⭐⭐

**Tại sao**: Paper IEEE 2026 mới nhất, chưa ai làm ở cuộc thi sinh viên, giải quyết vấn đề thực tế (elderly không thích đeo device).

**Rủi ro**: Cần experiment nhiều, signal yếu.

---

### 🥈 #2: Cuffless Blood Pressure Estimation (Idea 2)
**Độc đáo**: ⭐⭐⭐⭐ | **Tiềm năng**: ⭐⭐⭐⭐⭐ | **Độ khó**: ⭐⭐⭐⭐

**Tại sao**: Thị trường cực lớn (1.3 tỷ ngườí bị tăng huyết áp), holy grail của wearables, chưa có sản phẩm commercial tốt.

**Giá trị mới**: Motion artifact rejection + auto-calibration.

---

### 🥉 #3: Sleep Apnea Screening (Idea 7)
**Độc đáo**: ⭐⭐⭐⭐ | **Tiềm năng**: ⭐⭐⭐⭐⭐ | **Độ khó**: ⭐⭐⭐⭐

**Tại sao**: Paper IEEE 2026 mới, haptic feedback là innovation, underserved market (100M+ ngườí bị sleep apnea).

**Lợi thế**: Dễ demo, hardware đơn giản.

---

## 📝 KẾT LUẬN

Cuộc thi IoT Challenge 2026 là cơ hội tuyệt vờí để:
1. **Học hỏi**: Làm việc với cutting-edge Edge AI technology
2. **Networking**: Kết nối với mentors từ FPT Software & Silicon Labs
3. **Portfolio**: Có project thực tế để show trong CV
4. **Prize**: 5,000 USD giải thưởng

**Lờí khuyên cuối cùng**:
- Chọn ý tưởng phù hợp với skillset của team
- Bắt đầu sớm, iterate nhanh
- Focus vào demo hoàn chỉnh hơn là feature nhiều
- Đừng quên yêu cầu bắt buộc: Silicon Labs + Wireless + Edge AI

**Good luck! 🚀**

---

## 📎 APPENDIX

### A. Reference Papers

| # | Paper | Year | Ý tưởng liên quan |
|---|-------|------|-------------------|
| 1 | Reliable ECG anomaly detection on edge devices | 2025 | Idea 1 |
| 2 | TinyML for real-time on-edge BP estimation | 2023 | Idea 2 |
| 3 | Edge computing transformers for fall detection | 2024 | Idea 3 |
| 4 | TinyML motion-based cough detection | 2024 | Idea 6 |
| 5 | Sleep Apnea Screening wearable | 2026 | Idea 7 |
| 6 | Real-Time Thermal Monitoring | 2025 | Idea 8 |
| 7 | Multi-Parameter Health Monitoring SoC | 2026 | Idea 9 |
| 8 | BCG-Based Bed Sensor | 2026 | Idea 10 |
| 9 | Federated Learning for patient monitoring | 2025 | Idea 5 |

### B. Quick Hardware Shopping List

| Nhà cung cấp | Website | Ưu điểm |
|--------------|---------|---------|
| DigiKey | digikey.com | Đầy đủ, ship nhanh |
| Mouser | mouser.com | Giá tốt, stock tốt |
| SparkFun | sparkfun.com | Modules sẵn, tutorial tốt |
| Adafruit | adafruit.com | Quality tốt, community |
| Seeed Studio | seeedstudio.com | XIAO series, giá rẻ |
| Lazada/Shopee VN | - | Ship nhanh trong VN |

### C. Contact Information

- **IoT Challenge 2026**: https://community.silabs.com/s/share/a5UVm000001SlLBMA0
- **Registration**: https://forms.office.com/r/UYY5NtkYBY
- **Silicon Labs Community**: community.silabs.com

---

*Document created for IoT Challenge 2026 preparation*
*Last updated: April 2026*
