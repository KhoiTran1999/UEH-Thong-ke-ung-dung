# MASTER_CONTEXT - THỐNG KÊ ỨNG DỤNG TRONG KINH TẾ & KINH DOANH (UEH)
> **Chuẩn hóa tri thức theo mô hình thực thể (Entity-based Hierarchical Knowledge Framework)**  
> **Giáo trình quy chuẩn**: *Statistics for Business and Economics* (David R. Anderson, Dennis J. Sweeney, Thomas A. Williams - University of Cincinnati)  
> **Lưu trữ & Kế thừa**: Định nghĩa 1 lần (`Define Once`) → Mở rộng tuần tự (`Expand Later`) → Liên kết toàn diện (`Link Everywhere`).

---

## 1. ENTITY REGISTRY (DANH MỤC THỰC THỂ HỆ THỐNG)

| Entity ID | Tên Thực thể (Tiếng Việt) | Tên Quốc tế (English Name) | Miền Phân loại (System Domain) | Định nghĩa & Sứ mệnh Cốt lõi | Chương Giới thiệu | Trạng thái |
| :---: | :--- | :--- | :--- | :--- | :---: | :---: |
| **[E1]** | **Dữ liệu & Hệ thống Thang đo** | Data & Measurement Scales | Foundational Input Layer | Nguyên liệu thô đầu vào của tư duy thống kê; quy định cấu trúc thực thể, biến số, quan sát và 4 cấp độ đo lường quyết định giới hạn toán học và công cụ trực quan hóa tương thích. | Chương 1 | Active (Mở rộng Ch2) |
| **[E2]** | **Nguồn Dữ liệu & Quy trình Thu thập** | Data Sources & Acquisition | Data Supply & Ingestion Layer | Cơ chế khai thác dữ liệu thứ cấp có sẵn và thiết lập nghiên cứu sơ cấp (thực nghiệm / quan sát) gắn liền nguyên tắc kinh tế (Cost < Benefit). | Chương 1 | Active |
| **[E3]** | **Phương pháp Bảng & Đồ thị Định tính** | Categorical Tabular & Graphical Engine | Analytical Processing Engine | Bộ công cụ tóm tắt, tổ chức và trực quan hóa dữ liệu định tính: Bảng tần số, tần suất, tần suất %, Biểu đồ thanh, Biểu đồ Pareto (80/20) và Biểu đồ tròn. | Chương 1 | Active (Mở rộng Ch2) |
| **[E4]** | **Suy diễn Thống kê** | Statistical Inference | Core Deductive Engine | Phương pháp luận sử dụng dữ liệu từ mẫu đại diện ($n$) để ước lượng tham số và kiểm định các giả thuyết về toàn bộ tổng thể ($N$). | Chương 1 | Active |
| **[E5]** | **Trụ cột Ứng dụng Quản trị & Thị giác Dữ liệu** | Business & Visualization Pillars | Managerial Decision Layer | Điểm đích của chuỗi giá trị thống kê: biến đổi thông tin định lượng thành các quyết định chiến lược trong Kế toán, Tài chính, Tiếp thị, Sản xuất (SQC) và chuẩn mực đạo đức đồ họa. | Chương 1 | Active (Mở rộng Ch2) |
| **[E6]** | **Phương pháp Bảng & Đồ thị Định lượng** | Quantitative Tabular & Graphical Engine | Continuous Analytical Engine | Động cơ tổ chức và trực quan hóa biến số định lượng: Quy trình 3 bước lập lớp ($k$, Width, Class Limits), Biểu đồ Histogram, Đồ thị điểm (Dot plot), Đường cong tích lũy (Ogive) và Đồ thị Nhánh - Lá (Stem-and-Leaf). | Chương 2 | Active |
| **[E7]** | **Phân tích Đa biến & Nghịch lý Simpson** | Bivariate Analysis & Simpson's Paradox Engine | Multidimensional Analytical Engine | Công cụ phân tích mối quan hệ đồng thời giữa 2 hoặc nhiều biến số: Bảng chéo 2 chiều (Crosstabulation), Đồ thị phân tán (Scatter diagram) & Đường xu hướng (Trendline), kiểm soát Biến ẩn (Confounding) và Nghịch lý Simpson. | Chương 2 | Active |

---

## 2. SYSTEM HIERARCHY (CẤU TRÚC PHÂN CẤP HỆ THỐNG TOÀN KHÓA HỌC)

```text
HỆ THỐNG THỐNG KÊ ỨNG DỤNG TRONG KINH TẾ & KINH DOANH (UEH)
│
├── [TIER 0] HẠ TẦNG DỮ LIỆU ĐẦU VÀO (INPUT & FOUNDATION TIER)
│   ├── [E1] DỮ LIỆU & HỆ THỐNG THANG ĐO (DATA & SCALES)
│   │   ├── Ch1: Cấu trúc Dữ liệu & Hệ thống 4 Thang đo (Nominal, Ordinal, Interval, Ratio)
│   │   ├── Ch2: Bộ lọc Thang đo (Data & Scale Filter) & Bộ đôi Số tuyệt đối (f) / Số tương đối (rf, pf)
│   │   └── Ch2: Nguyên tắc Data-ink ratio & Thiết kế Đồ thị Chuẩn mực (Edward Tufte)
│   │
│   └── [E2] NGUỒN DỮ LIỆU & QUY TRÌNH THU THẬP (DATA SOURCES & ACQUISITION)
│       ├── Ch1: Dữ liệu Thứ cấp (Nội bộ, Bloomberg, GSO) & Sơ cấp (Thực nghiệm vs. Quan sát)
│       └── Ch1: Ràng buộc Kinh tế (Cost < Benefit) & Kiểm soát Sai số Dữ liệu (Outliers)
│
├── [TIER 1] ĐỘNG CƠ XỬ LÝ & TRỰC QUAN HÓA (ANALYTICAL & VISUALIZATION ENGINES)
│   ├── [E3] PHƯƠNG PHÁP BẢNG & ĐỒ THỊ ĐỊNH TÍNH (CATEGORICAL ENGINE)
│   │   ├── Ch2: Bảng phân phối Tần số, Tần suất & Tần suất phần trăm định tính
│   │   ├── Ch2: Biểu đồ Thanh (Bar Chart) & Biểu đồ Pareto (Nguyên lý 80/20 Vital Few)
│   │   └── Ch2: Biểu đồ Tròn (Pie Chart), Góc hình quạt & Cảnh báo bóp méo thị giác 3D
│   │
│   ├── [E6] PHƯƠNG PHÁP BẢNG & ĐỒ THỊ ĐỊNH LƯỢNG (QUANTITATIVE ENGINE)
│   │   ├── Ch2: Quy trình 3 Bước Lập lớp (Số lớp k, Độ rộng Width, Giới hạn Class Limits)
│   │   ├── Ch2: Biểu đồ Histogram, Đồ thị Điểm (Dot plot) & Nhận diện Hình dáng Phân phối (Skewness)
│   │   └── Ch2: Phân phối Tích lũy (Ogive) & Đồ thị Nhánh - Lá (Stem-and-Leaf bảo toàn 100% dữ liệu gốc)
│   │
│   ├── [E7] PHÂN TÍCH ĐA BIẾN & NGHỊCH LÝ SIMPSON (BIVARIATE & SIMPSON'S PARADOX)
│   │   ├── Ch2: Bảng chéo 2 chiều (Crosstabulation / Contingency Table, Row % vs Col %)
│   │   ├── Ch2: Nghịch lý Simpson & Cảnh báo Biến ẩn (Confounding Variable - Case 2 Bác sĩ)
│   │   └── Ch2: Đồ thị Phân tán (Scatter Diagram) & Đường xu hướng (Trendline)
│   │
│   └── [E4] SUY DIỄN THỐNG KÊ (STATISTICAL INFERENCE - NỀN TẢNG CHƯƠNG 1)
│       ├── Ch1: Cặp đôi Nền tảng Tổng thể (N, μ) vs Mẫu (n, x̄)
│       └── Ch1: Quy trình 4 Bước Suy diễn Mẫu & Hàng rào Đạo đức Nghề nghiệp
│
└── [TIER 2] ĐẦU RA RA QUYẾT ĐỊNH & THỊ GIÁC QUẢN TRỊ (DECISION & VISUALIZATION TIER)
    └── [E5] TRỤ CỘT ỨNG DỤNG QUẢN TRỊ & THỊ GIÁC DỮ LIỆU (BUSINESS & VISUALIZATION PILLARS)
        ├── Ch1: Ứng dụng Kiểm toán (Accounting), Định giá P/E (Finance) & Hồi quy Vĩ mô (Economics)
        ├── Ch2: Kiểm soát Dung sai Quy trình Sản xuất (SQC) bằng Histogram & Tối ưu hóa Pareto trong TQM
        ├── Ch2: Đồ thị Phân tán Tài chính (Risk vs Return) & Đồ thị Tích lũy (Ogive) trong Kiểm toán thời gian
        └── Ch2: Chuẩn mực Đạo đức Đồ họa: Nghiêm cấm Cắt xén Trục tung (Truncated Axis) & Trách nhiệm Giải trình
```

---

## 3. ENTITY KNOWLEDGE BASE (KHO TRI THỨC THỰC THỂ)

### 3.1. KHO TRI THỨC THỰC THỂ CHƯƠNG 1: DỮ LIỆU & THỐNG KÊ (DATA & STATISTICS)

### [E1] DỮ LIỆU & HỆ THỐNG THANG ĐO (DATA & MEASUREMENT SCALES)
- **Bản chất Khoa học**:
  - Dữ liệu (*Data*): Các sự kiện và số liệu được thu thập, phân tích và tóm tắt để phục vụ việc trình bày, diễn giải và ra quyết định.
  - Phân biệt Toán học vs Thống kê: Toán học nghiên cứu các con số trừu tượng thuần túy; Thống kê nghiên cứu các con số gắn liền với ngữ cảnh thực tiễn, số liệu chỉ có ý nghĩa khi so sánh giữa các thực thể có cùng bản chất đồng nhất.
  - Phần tử (*Elements* - ký hiệu $n$): Các thực thể cụ thể được thu thập dữ liệu (doanh nghiệp, nhân viên, sản phẩm, hộ gia đình).
  - Biến số (*Variables* - ký hiệu $k$): Các đặc tính quan tâm được đo lường trên từng phần tử.
  - Quan sát (*Observations*): Tập hợp các giá trị đo lường của tất cả $k$ biến số trên một phần tử duy nhất.
  - Tập dữ liệu hoàn chỉnh (*Data Set*): Chứa tổng cộng $n \times k$ giá trị dữ liệu số học/nhãn.
- **Hệ thống 4 Cấp độ Thang đo (Scales of Measurement)**:
  1. **Thang đo Danh nghĩa (Nominal Scale)**:
     - Đặc trưng: Chỉ gán nhãn, tên gọi, mã hóa định danh; không tồn tại quan hệ thứ tự hơn kém.
     - Ví dụ: Giới tính (Nam/Nữ), Tình trạng hôn nhân, Mã chứng khoán, Sàn niêm yết (NYSE/Nasdaq).
     - Phép toán hợp lệ: Chỉ đếm tần số (*Frequency*), tính tỷ lệ phần trăm (*Percentage*), yếu vị (*Mode*). Tuyệt đối không thực hiện cộng trừ hay tính Mean.
  2. **Thang đo Thứ bậc (Ordinal Scale)**:
     - Đặc trưng: Các giá trị có quan hệ so sánh thứ tự hơn kém, cấp bậc; tuy nhiên khoảng cách số học giữa các bậc không bằng nhau và không đo lường được.
     - Ví dụ: Xếp loại học lực (Giỏi > Khá > Trung bình), Xếp hạng tín nhiệm trái phiếu (AAA, AA, A, BBB), Đánh giá độ hài lòng dịch vụ (1 sao - 5 sao), Xếp hạng trường kinh doanh của BusinessWeek.
     - Phép toán hợp lệ: Đếm tần số, phân vị, trung vị (*Median*).
  3. **Thang đo Khoảng (Interval Scale)**:
     - Đặc trưng: Dữ liệu luôn ở dạng số, khoảng cách giữa các giá trị có ý nghĩa toán học cố định và bằng nhau, **KHÔNG CÓ GỐC 0 TUYỆT ĐỐI** (điểm 0 chỉ mang tính quy ước do con người đặt ra).
     - Ví dụ: Nhiệt độ Celsius/Fahrenheit ($0^\circ C$ không có nghĩa là "không có nhiệt độ"), Điểm thi chuẩn hóa SAT, Điểm đánh giá năng lực GRE/GMAT, Thời gian lịch dương.
     - Hệ quả: Cho phép so sánh khoảng chênh lệch ($40^\circ C - 20^\circ C = 20^\circ C$), nhưng không được so sánh tỷ lệ phép chia ($40^\circ C$ không thể nói nóng gấp đôi $20^\circ C$).
  4. **Thang đo Tỷ lệ (Ratio Scale)**:
     - Đặc trưng: Thang đo hoàn thiện và mạnh nhất trong khoa học đo lường; dữ liệu số, khoảng cách cố định và **BẮT BUỘC CÓ GỐC 0 TUYỆT ĐỐI** (0 biểu thị sự hoàn toàn vắng mặt của đặc tính đo lường).
     - Ví dụ: Doanh thu, Chi phí, Lợi nhuận, Thu nhập, Giá cổ phiếu, Tuổi tác, Trọng lượng, Khoảng cách địa lý.
     - Hệ quả: Cho phép tính toán toàn bộ các phép tính số học (+, -, $\times$, $\div$); tỷ lệ so sánh được bảo toàn khi thay đổi đơn vị đo lường (100 triệu VNĐ gấp đôi 50 triệu VNĐ).
- **Phân loại Dữ liệu theo Bản chất**:
  - Dữ liệu Định tính (*Categorical/Qualitative*): Đo bằng thang Nominal hoặc Ordinal; mô tả thuộc tính, đặc điểm; phân tích bằng bảng tần số, biểu đồ thanh/tròn.
  - Dữ liệu Định lượng (*Quantitative*): Đo bằng thang Interval hoặc Ratio; biểu thị số lượng hoặc mức độ; chia làm Biến rời rạc (*Discrete* - đếm được: số nhân viên, số lỗi) và Biến liên tục (*Continuous* - đo được trên trục số: thời gian, cân nặng, tỷ suất lợi nhuận).
- **Phân loại Dữ liệu theo Chiều Thời gian**:
  - Dữ liệu Thời điểm (*Cross-Sectional Data*): Thu thập trên nhiều phần tử tại cùng một thời điểm xác định (Ví dụ: Doanh thu quý 1/2026 của 100 công ty niêm yết).
  - Dữ liệu Chuỗi thời gian (*Time Series Data*): Thu thập trên một phần tử duy nhất qua nhiều mốc thời gian liên tiếp (Ví dụ: Chỉ số CPI của Việt Nam qua từng tháng từ 2015 đến 2026).
- **Quy tắc Thiết kế Khảo sát & Đo lường Quản trị**:
  - *Nguyên lý Bất khả Hoàn tác*: Dữ liệu thu thập ở thang đo cao hơn (Ratio) có thể quy đổi hạ cấp xuống thang đo thấp hơn (Ordinal/Nominal), nhưng dữ liệu đã thu thập ở thang thấp thì vĩnh viễn không thể khôi phục lại giá trị chính xác ở thang cao.
  - *Quy tắc thực hành*: Nếu muốn tính giá trị trung bình (Mean), người thiết kế khảo sát bắt buộc phải hỏi dữ liệu dạng Ratio ngay từ đầu (Ví dụ: hỏi chính xác số tiền thu nhập hàng tháng, thay vì chỉ yêu cầu chọn khoảng nhóm thu nhập).

---

### [E2] NGUỒN DỮ LIỆU & QUY TRÌNH THU THẬP (DATA SOURCES & ACQUISITION)
- **Dữ liệu Thứ cấp (Secondary / Existing Data - Phép so sánh "Đi ăn tiệm")**:
  - Khái niệm: Dữ liệu đã được người khác thu thập, tổng hợp sẵn cho các mục đích trước đó.
  - Các nguồn cung cấp điển hình:
    1. *Hồ sơ nội bộ doanh nghiệp*: Dữ liệu ERP, hệ thống kế toán, quản lý quan hệ khách hàng (CRM), hồ sơ hiệu suất nhân viên.
    2. *Tổ chức cung cấp dữ liệu thương mại*: Bloomberg, Dow Jones, S&P Capital IQ, ACNielsen (dữ liệu máy quét POS bán lẻ).
    3. *Cơ quan chính phủ & định chế quốc tế*: Cục Thống kê (GSO/BLS), Ngân hàng Nhà nước/Federal Reserve, Cục Điều tra dân số (Census), Ngân hàng Thế giới (World Bank), Quỹ Tiền tệ Quốc tế (IMF).
    4. *Hiệp hội ngành nghề & Internet*: Hiệp hội Vận tải Hàng không, cổng thông tin tài chính doanh nghiệp niêm yết.
- **Dữ liệu Sơ cấp (Primary Data - Phép so sánh "Tự nấu ăn")**:
  - Khái niệm: Dữ liệu do chính nhóm nghiên cứu tự thiết kế và thu thập lần đầu nhằm giải quyết mục tiêu cụ thể.
  - Hai hình thức nghiên cứu cơ bản:
    1. *Nghiên cứu Thực nghiệm (Experimental Study)*: Nhà nghiên cứu chủ động kiểm soát và thao túng một hoặc nhiều biến độc lập để quan sát sự thay đổi trên biến phụ thuộc nhằm xác lập quan hệ nhân quả. Ví dụ: Thử nghiệm lâm sàng vắc-xin Salk phòng bại liệt (nhóm tiêm vắc-xin thật vs nhóm dùng giả dược Placebo).
    2. *Nghiên cứu Quan sát (Observational Study / Survey)*: Nhà nghiên cứu ghi nhận hiện trạng tự nhiên mà không có bất kỳ sự can thiệp hay áp đặt nào lên các đối tượng khảo sát. Ví dụ: Khảo sát mức độ hài lòng khách hàng tại nhà hàng Lobster Pot.
- **Ràng buộc Kinh tế & Quản trị Rủi ro Dữ liệu**:
  - *Ràng buộc Thời gian*: Nguy cơ dữ liệu bị lỗi thời (*obsolete*) trước khi công tác phân tích và ra quyết định hoàn tất.
  - *Nguyên tắc Kinh tế Cốt lõi*: Chi phí thu thập dữ liệu (*Cost*) bắt buộc phải nhỏ hơn Giá trị lợi ích tạo ra từ quyết định được cải thiện (*Expected Benefit*).
  - *Kiểm soát Sai số (Data Error Audit)*: Dữ liệu sai lệch còn nguy hiểm gấp nhiều lần việc không có dữ liệu. Doanh nghiệp cần quy trình kiểm tra tính nhất quán logic (*Internal consistency check*) và nhận diện giá trị ngoại lệ bất thường (*Outliers screen*).

---

### [E3] THỐNG KÊ MÔ TẢ (DESCRIPTIVE STATISTICS)
- **Sứ mệnh & Nguyên tắc Cốt lõi**:
  - Nhiệm vụ: Chuyển đổi các bảng biểu số liệu thô đồ sộ, rối rắm thành các bảng tóm tắt, biểu đồ trực quan và chỉ số cô đọng giúp người quản lý nắm bắt nhanh bức tranh toàn cảnh.
  - *Nguyên tắc Tương thích Thang đo*: Phương pháp mô tả được phép áp dụng phụ thuộc 100% vào bản chất thang đo của biến số.
  - *Cảnh báo Phần mềm*: Các công cụ tính toán (Excel, SPSS, Minitab, Python, R) đều là cỗ máy vô hồn, sẵn sàng thực hiện mọi công thức người dùng yêu cầu kể cả khi công thức đó hoàn toàn vô nghĩa về mặt thống kê (như tính Mean cho biến giới tính được mã hóa 1 = Nam, 2 = Nữ).
- **Hệ thống Bảng biểu & Đồ thị Trực quan**:
  1. *Đối với Dữ liệu Định tính (Categorical Data)*:
     - Bảng phân phối tần số (*Frequency Distribution*), bảng tần suất (*Relative Frequency*) và bảng tần suất phần trăm (*Percent Frequency*).
     - Biểu đồ thanh (*Bar Chart*): Các cột cách rời nhau, biểu diễn tần số/phần trăm từng nhóm phân loại.
     - Biểu đồ tròn (*Pie Chart*): Biểu diễn cơ cấu tỷ trọng tương đối của từng nhóm trong tổng thể 100%.
  2. *Đối với Dữ liệu Định lượng (Quantitative Data)*:
     - Bảng phân phối tần số theo khoảng/lớp: Chia dải dữ liệu thành các khoảng bằng nhau không chồng lấn.
     - Biểu đồ phân phối tần số (*Histogram*): Các cột liền kề sát nhau phản ánh tính liên tục của dữ liệu số; hình dạng cột cho biết phân phối chuẩn đối xứng hay phân phối lệch (*skewness*).
     - Đồ thị điểm (*Dot Plot*), Đồ thị thân và lá (*Stem-and-Leaf Display* - giữ nguyên vẹn giá trị số thô ban đầu), Đồ thị tích lũy (*Ogive*).
     - Đồ thị phân tán (*Scatter Diagram*): Biểu diễn mối quan hệ tương quan giữa hai biến định lượng trên hệ tọa độ Descartes.
- **Đại lượng Đo lường Tóm tắt (Numerical Measures)**:
  - Số đo xu hướng trung tâm: Giá trị trung bình mẫu ($\bar{x} = \frac{\sum x_i}{n}$), Trung vị (*Median* - giá trị đứng giữa mảng sắp xếp), Yếu vị (*Mode* - giá trị xuất hiện nhiều nhất).
  - Nghiên cứu điển hình giáo trình: Case-study Hudson Auto Repair tóm tắt 50 hóa đơn chi phí phụ tùng xe thành bảng phân phối lớp và biểu đồ Histogram, giúp chủ xưởng nắm rõ 80% khách hàng chi trả dưới 100 USD.

---

### [E4] SUY DIỄN THỐNG KÊ (STATISTICAL INFERENCE)
- **Bộ đôi Nền tảng: Tổng thể vs Mẫu**:
  - *Tổng thể (Population)*: Tập hợp toàn bộ các phần tử được quan tâm trong một nghiên cứu cụ thể, quy mô ký hiệu là $N$. Đặc trưng số của tổng thể gọi là **Tham số (Parameter)**, ví dụ: Trung bình tổng thể $\mu$, Tỷ lệ tổng thể $p$.
  - *Mẫu (Sample)*: Tập hợp con gồm các phần tử được chọn lọc từ tổng thể để tiến hành thu thập dữ liệu trực tiếp, quy mô ký hiệu là $n$ ($n \ll N$). Đặc trưng số tính toán từ mẫu gọi là **Thống kê mẫu (Statistic)**, ví dụ: Trung bình mẫu $\bar{x}$, Tỷ lệ mẫu $\bar{p}$.
  - Điều tra toàn bộ (*Census*) vs Điều tra chọn mẫu (*Sample Survey*): Tổng điều tra dân số/kinh tế tiêu tốn hàng triệu USD và nhiều năm xử lý, trong khi điều tra chọn mẫu tiết kiệm chi phí, cung cấp kết quả kịp thời và đảm bảo độ chính xác nhờ đội ngũ điều tra viên tinh gọn, chuyên sâu.
- **Quy trình 4 Bước Suy diễn Thống kê**:
  1. *Bước 1: Xác định Tổng thể & Tham số cần nghiên cứu*: Xác định rõ phạm vi tổng thể $N$ và tham số chưa biết (ví dụ: tuổi thọ trung bình $\mu$ của lô sản xuất bóng đèn).
  2. *Bước 2: Thu thập Mẫu đại diện ngẫu nhiên*: Trích xuất mẫu ngẫu nhiên gồm $n$ phần tử đại diện khách quan (ví dụ: kiểm định $n = 200$ bóng đèn của hãng Norris Electronics).
  3. *Bước 3: Tính toán Thống kê mẫu*: Vận hành thống kê mô tả trên mẫu để tính giá trị tóm tắt (ví dụ: tuổi thọ trung bình mẫu đạt $\bar{x} = 76$ giờ).
  4. *Bước 4: Suy diễn ra Tổng thể & Lượng hóa Sai số*: Sử dụng $\bar{x} = 76$ giờ làm ước lượng điểm (*Point Estimate*) cho $\mu$; đồng thời công bố kèm sai số biên (*Margin of Error*, ví dụ: $76 \pm 4$ giờ tại độ tin cậy 95%).
- **Bẫy Sai lệch Chọn mẫu & Tiêu chuẩn Đạo đức Nghề nghiệp**:
  - *Bẫy Mẫu không Đại diện*: Mẫu thông báo trước (như thanh tra an toàn thực phẩm hay kiểm tra trường học báo lịch trước) khiến đối tượng đối phó, biến mẫu thành sai lệch, vô giá trị.
  - *Tội lỗi Thống kê 1: Khai thác lặp mẫu (Cherry-picking)*: Tiến hành lấy mẫu liên tục nhiều lần rồi chỉ chọn duy nhất mẫu có kết quả phù hợp với định kiến chủ quan để báo cáo.
  - *Tội lỗi Thống kê 2: Tùy tiện gọt giũa dữ liệu (Data Trimming)*: Tự ý loại bỏ các quan sát ngoại lệ bất lợi ra khỏi tập dữ liệu mà không có cơ sở khoa học và giải trình minh bạch.

---

### [E5] TRỤ CỘT ỨNG DỤNG QUẢN TRỊ & KINH TẾ (BUSINESS & ECONOMIC PILLARS)
- **5 Trọng tâm Ứng dụng Thực tiễn trong Doanh nghiệp**:
  1. **Kế toán & Kiểm toán (Accounting)**:
     - Các hãng kiểm toán (Big 4) không thể kiểm tra từng hóa đơn trong hàng triệu giao dịch của khách hàng.
     - Ứng dụng: Lấy mẫu kiểm toán (*Audit Sampling*) chọn ngẫu nhiên một tỷ lệ nhỏ các tài khoản phải thu (*Accounts Receivable*) để gửi thư xác nhận; từ tỷ lệ sai lệch mẫu suy diễn ra tính trung thực của toàn bộ báo cáo tài chính.
  2. **Tài chính & Đầu tư (Finance)**:
     - Các nhà phân tích tài chính theo dõi tỷ số Giá trên Thu nhập mỗi cổ phần ($P/E$).
     - Ứng dụng: So sánh chỉ số $P/E$ của một cổ phiếu riêng lẻ với $P/E$ trung bình ngành hoặc chỉ số Dow Jones Industrial Average để đánh giá cổ phiếu đang bị định giá thấp (*Undervalued*) hay quá cao (*Overvalued*).
  3. **Tiếp thị & Phân tích Người tiêu dùng (Marketing)**:
     - Tích hợp dữ liệu từ máy quét mã vạch POS (*Point of Sale Scanners*) tại quầy thu ngân với lịch trình phát hành phiếu giảm giá (coupons) hoặc khuyến mãi trên truyền hình.
     - Ứng dụng: Đánh giá chính xác độ co giãn của nhu cầu và hiệu quả hoàn vốn đầu tư (ROI) của từng chiến dịch tiếp thị.
  4. **Quản lý Sản xuất & Kiểm soát Chất lượng (Production & SQC)**:
     - Sản xuất công nghiệp hàng loạt quy định dung sai sản phẩm cực kỳ khắt khe.
     - Ứng dụng: Kiểm soát chất lượng bằng thống kê (*Statistical Quality Control - SQC*); định kỳ rút mẫu kiểm tra kích thước chi tiết và lập biểu đồ kiểm soát trung bình ($\bar{x}$-chart) với giới hạn kiểm soát trên (UCL) và giới hạn kiểm soát dưới (LCL) để phát hiện và ngăn chặn nguy cơ máy hỏng/sai lệch trước khi tạo ra hàng loạt phế phẩm.
  5. **Kinh tế học & Dự báo Vĩ mô (Economics)**:
     - Các nhà hoạch định chính sách và kinh tế gia sử dụng các chỉ số giá sản xuất (PPI), tỷ lệ thất nghiệp, năng lực khai thác nhà xưởng.
     - Ứng dụng: Xây dựng mô hình hồi quy kinh tế lượng dự báo tỷ lệ lạm phát tương lai, làm cơ sở điều hành lãi suất tiền tệ và tỷ giá hối đoái.
- **Tư duy Quản trị Dựa trên Dữ liệu (Data-driven Mindset)**:
  - Nhà quản trị hiện đại thay thế các tuyên bố định tính mơ hồ ("chất lượng tốt", "bán chạy") bằng các cam kết định lượng chính xác (tỷ lệ lỗi $\le 0.1\%$, tăng trưởng thị phần $15\% \pm 1.2\%$).
  - Sử dụng ngôn ngữ thống kê làm công cụ thuyết phục đối tác, bảo vệ ngân sách trước hội đồng quản trị và giải trình minh bạch trước các cơ quan quản lý nhà nước.

---

### 3.2. KHO TRI THỨC THỰC THỂ CHƯƠNG 2: THỐNG KÊ MÔ TẢ: BẢNG BIỂU & ĐỒ THỊ (TABULAR & GRAPHICAL DISPLAYS)

#### [E1] DỮ LIỆU & ĐIỀU KIỆN THANG ĐO (DATA & SCALE FILTER - MỞ RỘNG CHƯƠNG 2)
- **Quy chuẩn Ánh xạ Thang đo (Scale-to-Tool Mapping)**:
  - Thang đo quyết định tuyệt đối công cụ hiển thị hợp lệ:
    - *Nominal & Ordinal*: Bắt buộc dùng Bảng tần số/tần suất, Biểu đồ thanh (Bar chart), Biểu đồ Pareto, Biểu đồ tròn (Pie chart) và Bảng chéo (Crosstabulation).
    - *Interval & Ratio*: Dùng Bảng phân phối theo lớp, Biểu đồ Histogram, Đồ thị điểm (Dot plot), Đường cong tích lũy (Ogive), Đồ thị Nhánh - Lá (Stem-and-Leaf) và Đồ thị phân tán (Scatter diagram).
  - *Điều cấm kỵ*: Tuyệt đối không vẽ Histogram cho dữ liệu định tính; không tính Mean cho mã danh nghĩa (1 = Coke, 2 = Pepsi).
- **Bộ đôi Số Tuyệt đối & Số Tương đối**:
  - *Tần số (Frequency - $f_i$)*: Số quan sát thuộc một tổ/lớp; phản ánh quy mô tuyệt đối nhưng che khuất cơ cấu tỷ trọng khi so sánh.
  - *Tần suất (Relative Frequency - $rf_i$)*: $rf_i = \frac{f_i}{n}$. Tổng các tần suất trong bảng luôn luôn bằng $1.00$ ($\sum rf_i = 1.00$).
  - *Tần suất phần trăm (Percent Frequency - $pf_i$)*: $pf_i = rf_i \times 100\%$. Phản ánh tỷ trọng trực quan, là công cụ bắt buộc để so sánh giữa hai tập dữ liệu có quy mô mẫu $n_1 \ne n_2$.
- **Nguyên lý Thiết kế Đồ thị Chuẩn mực (Edward Tufte's Data-ink Ratio)**:
  - Tối đa hóa tỷ lệ dữ liệu/mực (*Data-ink ratio*): Mỗi giọt mực trên trang vẽ phải mang thông tin dữ liệu; triệt tiêu trang trí rác (*Chartjunk*).
  - *Quy chuẩn gốc tọa độ*: Trục tung thể hiện tần số/tỷ lệ bắt buộc phải bắt đầu từ số 0 để người đọc không bị ảo giác thị giác về mức độ chênh lệch.
  - *Ranh giới trực quan*: Khoảng cách giữa các cột trong Bar chart biểu thị tính tách rời của danh mục; các cột liền kề sát nhau trong Histogram biểu thị tính liên tục trên trục số.

---

#### [E3] PHƯƠNG PHÁP BẢNG & ĐỒ THỊ ĐỊNH TÍNH (CATEGORICAL TABULAR & GRAPHICAL ENGINE)
- **Bảng Phân phối Tần số Định tính**:
  - Cấu trúc: Cột Danh mục (Categories) | Tần số ($f_i$) | Tần suất ($rf_i$) | Tần suất % ($pf_i$).
  - Quy tắc thứ tự: Với biến Nominal có thể sắp theo thứ tự chữ cái hoặc theo tần số giảm dần; với biến Ordinal BẮT BUỘC giữ nguyên thứ tự cấp bậc vốn có (Kém → Trung bình → Khá → Tốt).
  - Case soft drink: Khảo sát mẫu $n = 50$ lượt mua nước giải khát gồm 5 nhãn hiệu: Classic Coke ($f = 19$, $38\%$), Diet Coke ($f = 8$, $16\%$), Dr. Pepper ($f = 5$, $10\%$), Pepsi ($f = 13$, $26\%$), Sprite ($f = 5$, $10\%$). Tổng tần số $= 50$, tổng tần suất $= 1.00$, tổng phần trăm $= 100\%$.
- **Biểu đồ Thanh (Bar Chart) & Biểu đồ Pareto**:
  - *Bar Chart*: Trục hoành là các danh mục, trục tung là tần số hoặc phần trăm; các thanh có độ rộng bằng nhau và CÁCH RỜI NHAU một khoảng trống rõ ràng để nhấn mạnh tính chất phân loại riêng biệt.
  - *Biểu đồ Pareto (Vilfredo Pareto)*: Là biểu đồ thanh đặc biệt, trong đó các thanh được sắp xếp theo thứ tự TẦN SỐ GIẢM DẦN từ trái sang phải, kết hợp với một đường biểu diễn tần suất phần trăm tích lũy.
  - *Quy tắc 80/20 (Vital Few vs. Trivial Many)*: Trong thực tiễn kinh doanh, khoảng 80% khuyết tật sản phẩm hoặc 80% doanh thu thường xuất phát từ chỉ 20% các nguyên nhân hoặc mặt hàng trọng yếu. Biểu đồ Pareto giúp nhà quản trị tách biệt "nhóm thiểu số sống còn" để tập trung nguồn lực can thiệp trước.
- **Biểu đồ Tròn (Pie Chart) & Nguy cơ Bóp méo Thị giác**:
  - Cơ chế hình học: Vòng tròn $360^\circ$ đại diện cho $100\%$ tổng thể ($1.00$). Góc ở tâm của mỗi hình quạt được tính theo công thức: $\text{Góc} = rf_i \times 360^\circ$ (Ví dụ Classic Coke: $0.38 \times 360^\circ = 136.8^\circ$).
  - *Giới hạn thực hành*: Chỉ nên dùng Pie Chart khi số lượng danh mục nhỏ (dưới 5–7 nhóm). Khi quá nhiều nhóm, mắt người rất khó phân biệt diện tích hình quạt.
  - *Cảnh báo 3D Pie Chart*: Hiệu ứng phối cảnh không gian 3 chiều khiến các lát cắt nằm ở phía trước trông lớn hơn thực tế, vi phạm nghiêm trọng tính trung thực của trực quan hóa dữ liệu.

---

#### [E6] PHƯƠNG PHÁP BẢNG & ĐỒ THỊ ĐỊNH LƯỢNG (QUANTITATIVE TABULAR & GRAPHICAL ENGINE)
- **Quy trình 3 Bước Thiết kế Bảng Phân phối Tần số theo Lớp**:
  - *Bước 1: Xác định Số lượng Lớp ($k$)*:
    - Khuyến nghị chung: Từ 5 đến 20 lớp tùy thuộc vào quy mô dữ liệu.
    - Quy tắc kinh nghiệm $2^k \ge n$ (Quy tắc Sturges biến thể): Với mẫu $n = 20$, ta chọn $k = 5$ vì $2^5 = 32 \ge 20$.
  - *Bước 2: Xác định Độ rộng Lớp (Approximate Class Width)*:
    - Công thức: $\text{Width} \approx \frac{\text{Giá trị Lớn nhất (Max)} - \text{Giá trị Nhỏ nhất (Min)}}{k}$.
    - Quy tắc làm tròn: Luôn làm tròn lên số nguyên hoặc số thập phân thuận tiện gần nhất (ví dụ: tính ra 4.2 ngày thì làm tròn thành 5 ngày). Độ rộng của tất cả các lớp nên bằng nhau.
  - *Bước 3: Xác định Giới hạn Lớp (Class Limits)*:
    - Giới hạn dưới của lớp đầu tiên phải nhỏ hơn hoặc bằng giá trị Min.
    - Các khoảng lớp không được chồng lấn nhau (ví dụ: 10–14, 15–19, 20–24...).
    - Trung điểm lớp (*Class Midpoint*): $\text{Midpoint} = \frac{\text{Giới hạn Dưới} + \text{Giới hạn Trên}}{2}$.
  - *Case Sanderson & Clifford (Kiểm toán)*: Dữ liệu thời gian kiểm toán cuối năm của 20 khách hàng: $\text{Min} = 12$, $\text{Max} = 33$. Chọn $k = 5$ lớp, $\text{Width} = \frac{33 - 12}{5} = 4.2 \rightarrow 5$ ngày. Phân thành 5 lớp: 10–14 (f=4), 15–19 (f=8), 20–24 (f=5), 25–29 (f=2), 30–34 (f=1).
- **Biểu đồ Histogram, Đồ thị Điểm (Dot Plot) & Nhận diện Hình dáng Phân phối**:
  - *Đồ thị điểm (Dot plot)*: Trục ngang là trục số ghi nhận thang đo; mỗi giá trị quan sát được đánh dấu bằng một dấu chấm tròn; các giá trị trùng nhau được xếp chồng lên nhau theo phương thẳng đứng. Ưu điểm: thấy rõ từng con số thô và độ biến thiên.
  - *Biểu đồ Histogram*: Các cột được vẽ LIỀN KỀ SÁT NHAU, không có khoảng cách trống giữa các cột (phản ánh tính liên tục của biến số). Chiều rộng đáy cột tương ứng độ rộng lớp; chiều cao cột biểu thị tần số hoặc tần suất. Diện tích của từng cột tỷ lệ thuận với tần số của lớp đó.
  - *Nhận diện Hình dáng Phân phối*:
    1. *Đối xứng (Symmetric)*: Phân phối hình chuông, hai bên cân xứng quanh trung tâm (phân phối chuẩn của chiều cao, sai số đo lường).
    2. *Lệch phải / Lệch dương (Moderately / Highly Skewed Right)*: Đuôi dài kéo dài sang phía bên phải (các giá trị rất lớn kéo dài đuôi; điển hình trong phân phối thu nhập, giá nhà, doanh số công ty công nghệ).
    3. *Lệch trái / Lệch âm (Moderately / Highly Skewed Left)*: Đuôi dài kéo dài sang phía bên trái (nhiều giá trị tập trung ở mức cao, ít giá trị ở mức thấp; ví dụ điểm thi một bài kiểm tra dễ).
- **Phân phối Tần số Tích lũy (Cumulative Distributions), Đồ thị Ogive & Đồ thị Nhánh - Lá**:
  - *Phân phối Tích lũy*: Ghi nhận tổng số quan sát có giá trị "nhỏ hơn hoặc bằng giới hạn trên của một lớp xác định".
  - *Đồ thị Ogive (Đường cong tích lũy)*: Trục hoành là giới hạn lớp, trục tung là tần số tích lũy (hoặc % tích lũy). Điểm đầu tiên bắt đầu từ giới hạn dưới của lớp đầu tiên tại giá trị tung độ bằng 0; sau đó nối các điểm tọa độ tại giới hạn trên của từng lớp tiếp theo. Giúp nhà quản lý trả lời nhanh câu hỏi: "Có bao nhiêu % khách hàng hoàn thành dịch vụ trong dưới 20 ngày?".
  - *Đồ thị Nhánh - Lá (Stem-and-Leaf Display)*:
    - Kỹ thuật phân tích dữ liệu khám phá (EDA - John Tukey). Tách mỗi số thành hai phần: **Thân (Stem)** gồm các chữ số hàng chục/trăm/nghìn đứng trước, và **Lá (Leaf)** là chữ số hàng đơn vị đứng sau.
    - *Ưu thế vượt trội*: Vừa sắp xếp thứ tự dữ liệu, vừa trực quan hóa được hình dáng phân phối (tương tự Histogram xoay ngang), nhưng **BẢO TOÀN 100% GIÁ TRỊ SỐ THÔ GỐC** (không làm mất dữ liệu như Histogram).
    - *Kỹ thuật Kéo giãn Thân (Stretched Stem)*: Khi có quá nhiều lá dồn vào một thân làm hàng lá quá dài, ta có thể tách mỗi thân thành 2 dòng (dòng 1 chứa lá 0–4, dòng 2 chứa lá 5–9) hoặc 5 dòng để nhìn rõ hình dáng chi tiết.

---

#### [E7] PHÂN TÍCH ĐA BIẾN & NGHỊCH LÝ SIMPSON (BIVARIATE ANALYSIS & SIMPSON'S PARADOX)
- **Bảng Chéo 2 Chiều (Crosstabulation / Contingency Table)**:
  - Bản chất: Ma trận bảng 2 chiều tóm tắt dữ liệu cho hai biến số cùng lúc nhằm khám phá mối quan hệ tương tác giữa chúng.
  - Ba cấu hình kết hợp biến:
    1. *Cả hai biến đều định tính*: Ví dụ Giới tính $\times$ Lựa chọn phương thức thanh toán.
    2. *Một biến định tính, một biến định lượng*: Ví dụ Giới tính $\times$ Mức thu nhập (đã chia nhóm lớp).
    3. *Cả hai biến đều định lượng*: Ví dụ Điểm đánh giá chất lượng nhà hàng $\times$ Giá bữa ăn (đều đã chia nhóm lớp).
  - Cấu trúc: Các ô trung tâm (*Cells*) chứa tần số xuất hiện đồng thời của cả 2 biến ($f_{ij}$); Hàng biên dưới cùng ghi nhận Tổng theo cột (*Column Totals*); Cột biên phải ngoài cùng ghi nhận Tổng theo dòng (*Row Totals*). Tổng dòng và tổng cột chính là phân phối tần số đơn biến (*Marginal distributions*).
  - *Chuyển đổi Tỷ lệ Bảng chéo*:
    - Phần trăm theo dòng (*Row Percentages*): Chia tần số mỗi ô cho tổng dòng tương ứng. Dùng khi muốn so sánh cơ cấu của biến cột giữa các nhóm dòng khác nhau.
    - Phần trăm theo cột (*Column Percentages*): Chia tần số mỗi ô cho tổng cột tương ứng. Dùng khi muốn so sánh cơ cấu của biến dòng giữa các nhóm cột khác nhau.
- **Nghịch lý Simpson & Cảnh báo Biến ẩn (Simpson's Paradox & Confounding Variable)**:
  - Bản chất hiện tượng: Một kết luận hoặc mối tương quan rút ra từ bảng chéo số liệu gộp chung (*Aggregated Data*) có thể bị **ĐẢO NGƯỢC HOÀN TOÀN** khi bảng số liệu được bóc tách và phân tích riêng biệt theo từng mức của một biến số thứ 3 (*Unaggregated Data*).
  - Biến ẩn / Biến can thiệp (*Confounding / Lurking Variable*): Biến số không được đưa vào bảng phân tích ban đầu nhưng lại có mối liên hệ mật thiết và chi phối mạnh mẽ lên cả hai biến đang xét.
  - *Case-study Kinh điển 2 Bác sĩ Phẫu thuật*:
    - Bác sĩ A vs Bác sĩ B phẫu thuật 100 bệnh nhân:
      - Bảng gộp chung: Tỷ lệ thành công của Bác sĩ A là $84\%$ ($84/100$), trong khi Bác sĩ B là $90\%$ ($90/100$). Ban giám đốc nếu chỉ nhìn bảng gộp sẽ vội vã kết luận Bác sĩ B giỏi hơn Bác sĩ A.
      - Bóc tách theo Biến ẩn "Mức độ nghiêm trọng của ca bệnh" (Ca nặng vs Ca nhẹ):
        - Ở các ca phẫu thuật nhẹ: Bác sĩ A đạt tỷ lệ thành công $99\%$ ($594/600$), Bác sĩ B chỉ đạt $98\%$ ($98/100$) $\rightarrow$ A giỏi hơn B!
        - Ở các ca phẫu thuật nặng/hiểm nghèo: Bác sĩ A đạt tỷ lệ thành công $80\%$ ($320/400$), Bác sĩ B chỉ đạt $70\%$ ($70/100$) $\rightarrow$ A vẫn giỏi hơn B!
    - *Giải thích nghịch lý*: Bác sĩ A có tay nghề cao vượt trội nên được phân công xử lý phần lớn các ca hiểm nghèo (nơi tỷ lệ tử vong vốn đã rất cao), trong khi Bác sĩ B chỉ xử lý hầu hết các ca bệnh nhẹ. Khi gộp chung số liệu, tỷ lệ tử vong ở ca nặng kéo tụt chỉ số tổng thể của Bác sĩ A.
  - *Bài học Quản trị Sống còn*: Nhà phân tích thống kê và lãnh đạo doanh nghiệp tuyệt đối không được vội vã ra quyết định chỉ dựa trên số liệu gộp bề mặt; bắt buộc phải chủ động rà soát sự hiện diện của các biến can thiệp tiềm ẩn.
- **Đồ thị Phân tán (Scatter Diagram) & Đường Xu hướng (Trendline)**:
  - Bản chất: Biểu diễn mối quan hệ giữa hai biến định lượng trên hệ tọa độ Descartes hai chiều. Trục hoành ($x$) thường gán cho biến độc lập/nguyên nhân; trục tung ($y$) gán cho biến phụ thuộc/kết quả.
  - Nhận diện 4 hình thái tương quan:
    1. *Tương quan Tuyến tính Dương (Positive Linear Relationship)*: Các điểm dữ liệu tạo thành dải dốc lên từ trái sang phải; khi $x$ tăng thì $y$ có xu hướng tăng theo (ví dụ: Số năm kinh nghiệm và Thu nhập).
    2. *Tương quan Tuyến tính Âm (Negative Linear Relationship)*: Các điểm dữ liệu tạo thành dải dốc xuống từ trái sang phải; khi $x$ tăng thì $y$ có xu hướng giảm (ví dụ: Giá bán sản phẩm và Sản lượng tiêu thụ).
    3. *Không có Tương quan Tuyến tính (No Linear Relationship)*: Các điểm dữ liệu phân tán tản mát hình đám mây tròn; giá trị của $x$ không cung cấp thông tin dự báo về $y$.
    4. *Tương quan Phi tuyến (Nonlinear Relationship)*: Các điểm dữ liệu uốn lượn theo dạng đường cong Parabol hoặc hình chữ U ngược (ví dụ: Mức độ lo âu và Hiệu suất làm việc).
  - *Đường Xu hướng (Trendline)*: Đường thẳng xấp xỉ tốt nhất đi qua đám mây điểm dữ liệu; cung cấp cái nhìn định lượng ban đầu và là nền tảng trực tiếp dẫn sang Phương pháp Bình phương Bé nhất trong Hồi quy Tuyến tính Đơn (Chương 14).
  - *Case Panther Products*: Khảo sát mối quan hệ giữa Chi phí quảng cáo trên truyền hình ($x$ - đơn vị 100 USD) và Doanh số bán thiết bị âm thanh ($y$ - đơn vị 1,000 USD) qua 10 tuần kinh doanh, cho thấy mối tương quan tuyến tính dương rõ nét: mỗi khi tăng chi phí quảng cáo, doanh số bán hàng đều tăng trưởng tương ứng.

---

#### [E5] TRỤ CỘT ỨNG DỤNG QUẢN TRỊ & THỊ GIÁC DỮ LIỆU (BUSINESS & VISUALIZATION PILLARS - MỞ RỘNG CHƯƠNG 2)
- **Kiểm soát Chất lượng Sản xuất (SQC) & Tối ưu hóa Pareto trong TQM**:
  - *Quản lý Sản xuất*: Biểu đồ Histogram giám sát phân phối dung sai kích thước linh kiện cơ khí, trọng lượng đóng gói hàng tiêu dùng. Sự xuất hiện của phân phối lệch (Skewed) hoặc phân phối có hai đỉnh (Bimodal) là tín hiệu cảnh báo dây chuyền đang gặp sự cố lệch tâm hoặc có sự pha trộn nguyên liệu từ hai lô cung ứng khác nhau.
  - *Tối ưu hóa chất lượng (TQM)*: Biểu đồ Pareto giúp ban giám đốc nhà máy phân loại nguyên nhân lỗi hỏng linh kiện điện tử, xác định 20% khâu lỗi gây ra 80% chi phí bảo hành để dồn ngân sách xử lý dứt điểm.
- **Phân tích Ra quyết định Đa biến trong Tài chính, Kiểm toán & Nhân sự**:
  - *Tài chính & Quản trị Rủi ro*: Đồ thị phân tán (Scatter diagram) giữa Tỷ suất sinh lời kỳ vọng và Hệ số rủi ro Beta của danh mục cổ phiếu giúp xác định đường thị trường chứng khoán (SML); scatter giữa quy mô tài sản và tỷ lệ chi phí quản lý quỹ.
  - *Kiểm toán độc lập*: Đồ thị đường cong tích lũy (Ogive) giúp các chủ nhiệm kiểm toán theo dõi tiến độ hoàn thành các hợp đồng kiểm toán, xác định tỷ lệ phần trăm hồ sơ hoàn tất trong các mốc thời gian quy định (ví dụ: cam kết 80% hồ sơ hoàn thành trong vòng 20 ngày).
  - *Quản trị Nhân sự & Trả lương*: Ứng dụng bảng chéo kiểm soát phân công lao động, đánh giá năng suất theo ca kíp kết hợp biến ẩn thâm niên nhằm tránh thiên vị hoặc đánh giá sai lệch năng lực nhân viên.
- **Tiêu chuẩn Đạo đức Đồ họa & Trách nhiệm Giải trình Trực quan**:
  - *Nghiêm cấm Cắt xén Trục tung (Truncated Vertical Axis)*: Việc bắt đầu trục tung ở một con số khác 0 (ví dụ từ 90 đến 100 thay vì từ 0) làm phóng đại thị giác mức chênh lệch nhỏ bé thành một bước nhảy vọt khổng lồ, đánh lừa nhà đầu tư và công chúng.
  - *Tiêu chuẩn Đồ họa Tufte*: Biểu đồ kinh doanh bắt buộc phải có đầy đủ tiêu đề giải thích ngữ cảnh, nhãn trục ghi rõ đơn vị tính, ghi chú kích thước mẫu ($n$) và nguồn dữ liệu kiểm chứng minh bạch.
  - *Nghĩa vụ Giải trình Dữ liệu Gộp*: Khi phát hiện nguy cơ biến ẩn, người làm thống kê có trách nhiệm trình bày song song cả bảng số liệu gộp và bảng phân tách đa chiều, nghiêm cấm việc che giấu bảng phân rã để phục vụ lợi ích cục bộ.

---

## 4. RELATIONSHIP REGISTRY (DANH MỤC QUAN HỆ LIÊN THỰC THỂ)

### 4.1. Quan hệ Kế thừa Chương 1 (Foundational Macro Flow)
| Relationship ID | Thực thể Nguồn (Source) | Thực thể Đích (Target) | Kiểu Liên kết | Bản chất Tương tác & Luồng Dữ liệu Học thuật |
| :---: | :---: | :---: | :---: | :--- |
| `CROSS_E2_E1` | **[E2] Nguồn Dữ liệu** | **[E1] Dữ liệu & Thang đo** | Ingestion & Structuring | Dữ liệu thô thu thập từ nguồn thứ cấp (báo cáo, Bloomberg) và sơ cấp (thực nghiệm, khảo sát) được chuẩn hóa vào tập dữ liệu gồm $n$ phần tử, $k$ biến số và định vị hệ thống thang đo tương ứng. |
| `CROSS_E1_E3` | **[E1] Dữ liệu & Thang đo** | **[E3] Thống kê Mô tả** | Feedforward Processing | Tập dữ liệu thô và thang đo tương thích được cung cấp làm đầu vào cho động cơ mô tả để tiến hành phân tổ, lập bảng tần số, vẽ đồ thị (Bar, Pie, Histogram) và tính giá trị trung bình $\bar{x}$. |
| `CROSS_E1_E4` | **[E1] Dữ liệu & Thang đo** | **[E4] Suy diễn Thống kê** | Evidence Supply | Cung cấp tập dữ liệu mẫu $n$ đạt chuẩn đại diện và không thiên lệch để làm căn cứ suy diễn, ước lượng tham số cho tổng thể $N$ chưa biết. |
| `CROSS_E3_E5` | **[E3] Thống kê Mô tả** | **[E5] Trụ cột Ứng dụng** | Operational Visualization | Cung cấp các công cụ trực quan hóa hiện trạng phục vụ kiểm soát chất lượng quy trình sản xuất (biểu đồ $\bar{x}$, UCL/LCL) và các bảng tóm tắt hiệu suất kinh doanh cho ban điều hành. |
| `CROSS_E4_E5` | **[E4] Suy diễn Thống kê** | **[E5] Trụ cột Ứng dụng** | Strategic Decision Driving | Cung cấp luận cứ khoa học và khoảng tin cậy sai số phục vụ kiểm toán mẫu (Accounting), phân tích định giá $P/E$ danh mục đầu tư (Finance), và mô hình dự báo vĩ mô (Economics). |
| `CROSS_E5_E2` | **[E5] Trụ cột Ứng dụng** | **[E2] Nguồn Dữ liệu** | Feedback & Goal Definition | Nhu cầu và mục tiêu ra quyết định kinh doanh xác định loại dữ liệu cần thu thập, đồng thời thiết lập ràng buộc kinh tế kiểm soát chi phí (Cost thu thập bắt buộc phải nhỏ hơn Benefit kỳ vọng). |
| `CROSS_E4_E1` | **[E4] Suy diễn Thống kê** | **[E1] Dữ liệu & Thang đo** | Ethical Integrity Guardrail | Chuẩn mực đạo đức nghề nghiệp trong suy diễn đóng vai trò hàng rào bảo vệ tính toàn vẹn của dữ liệu: nghiêm cấm hành vi cherry-picking mẫu lặp và nghiêm cấm tùy tiện gọt giũa dữ liệu ngoại lệ. |

### 4.2. Quan hệ Chuyên sâu Chương 2 (Tabular & Graphical Display Network - CH02.drawio)
| Relationship ID | Thực thể Nguồn (Source) | Thực thể Đích (Target) | Kiểu Liên kết | Bản chất Tương tác & Luồng Dữ liệu Học thuật Chương 2 |
| :---: | :---: | :---: | :---: | :--- |
| `CROSS_E1_E3` | **[E1] Dữ liệu & Thang đo** | **[E3] Động cơ Định tính** | Scale Routing | Thang đo Nominal/Ordinal định tuyến dữ liệu vào công cụ Bảng tần số/tần suất, Biểu đồ Thanh (Bar chart), Biểu đồ Pareto (80/20) và Biểu đồ Tròn (Pie chart). |
| `CROSS_E1_E6` | **[E1] Dữ liệu & Thang đo** | **[E6] Động cơ Định lượng** | Scale Routing | Thang đo Interval/Ratio định tuyến dữ liệu vào Quy trình 3 bước lập lớp ($k$, Width, Class Limits), Biểu đồ Histogram, Đồ thị điểm (Dot plot), Đường cong tích lũy (Ogive) và Đồ thị Nhánh - Lá (Stem-and-Leaf). |
| `CROSS_E3_E7` | **[E3] Động cơ Định tính** | **[E7] Phân tích Đa biến** | Bivariate Cross-linking | Các phân phối tần số đơn biến định tính được kết hợp chéo để xây dựng Bảng chéo 2 chiều (Crosstabulation) và tính toán tỷ lệ dòng/cột (Row % vs Col %). |
| `CROSS_E6_E7` | **[E6] Động cơ Định lượng** | **[E7] Phân tích Đa biến** | Bivariate Correlation | Các biến định lượng được phân tổ đưa vào Bảng chéo hoặc kết hợp thành cặp tọa độ $(x, y)$ trên Đồ thị phân tán (Scatter diagram) nhằm khảo sát tương quan và đường xu hướng (Trendline). |
| `CROSS_E6_E5` | **[E6] Động cơ Định lượng** | **[E5] Trụ cột Ứng dụng** | Operational Quality Control | Histogram và phân phối định lượng cung cấp công cụ giám sát dung sai quy trình sản xuất (SQC); Ogive cung cấp công cụ theo dõi tiến độ kiểm toán đúng hạn. |
| `CROSS_E7_E5` | **[E7] Phân tích Đa biến** | **[E5] Trụ cột Ứng dụng** | Managerial Decision Driving | Bảng chéo, đường xu hướng Scatter và bài học Nghịch lý Simpson (Simpson's Paradox) dẫn dắt các quyết định quản trị chiến lược, triệt tiêu sai lầm đánh giá khi dữ liệu bị gộp chung. |
| `CROSS_E5_E1` | **[E5] Trụ cột Ứng dụng** | **[E1] Dữ liệu & Thang đo** | Visualization Ethics Guardrail | Chuẩn mực đạo đức trực quan hóa (Data-ink ratio của Tufte, cấm cắt xén trục tung truncated axis) bảo đảm tính trung thực của thang đo và bảo vệ dữ liệu khỏi bóp méo thị giác. |

---

## 5. CHAPTER COVERAGE & COURSE ROADMAP (BẢNG TIẾN ĐỘ & ÁNH XẠ TOÀN KHÓA HỌC)

| Chương | Tên Chương Giáo trình (Anderson, Sweeney, Williams) | Thực thể Trọng tâm | Trạng thái Mindmap | Ánh xạ & Kế thừa Tri thức Xuyên suốt Khóa học |
| :---: | :--- | :---: | :---: | :--- |
| **Chương 1** | **Dữ liệu & Thống kê (Data and Statistics)** | **[E1], [E2], [E3], [E4], [E5]** | **Hoàn tất (CH01.drawio)** | Khởi tạo 5 Thực thể gốc, thiết lập ngữ pháp thị giác chuẩn, định vị 4 thang đo và quy trình suy diễn mẫu. |
| **Chương 2** | **Thống kê mô tả: Bảng biểu & Đồ thị (Descriptive: Tabular & Graphical)** | **[E1], [E3], [E6], [E7], [E5]** | **Hoàn tất (CH02.drawio)** | Kế thừa [E1], [E3], [E5]; Cấp mới [E6] (Quantitative Engine) & [E7] (Bivariate & Simpson's Paradox); Thiết lập mạng lưới 7 liên kết đa tầng. |
| Chương 3 | Thống kê mô tả: Các đại lượng số (Numerical Measures) | [E1], [E3], [E6], [E5] | Kế tiếp | Kế thừa [E1], [E6]; Mở rộng tính toán Mean, Median, Mode, Variance, Standard Deviation, z-score, Định lý Chebyshev và Quy tắc Thực nghiệm. |
| Chương 4 | Giới thiệu về Xác suất (Probability) | [E4] | Chờ triển khai | Thiết lập nền tảng toán học cho [E4]: Không gian mẫu, Biến cố, Xác suất có điều kiện, Định lý Bayes. |
| Chương 5 | Phân phối Xác suất Rời rạc | [E1], [E4] | Chờ triển khai | Kết nối biến rời rạc [E1] với phân phối Nhị thức (Binomial), Poisson, Siêu bội (Hypergeometric). |
| Chương 6 | Phân phối Xác suất Liên tục | [E1], [E4] | Chờ triển khai | Kết nối biến liên tục [E1] với Phân phối chuẩn (Normal Distribution), Chuẩn hóa $z$-score, Phân phối đều, Mũ. |
| Chương 7 | Chọn mẫu & Phân phối Mẫu | [E4] | Chờ triển khai | Mở rộng chi tiết quy trình lấy mẫu [E4], Định lý Giới hạn Trung tâm (Central Limit Theorem - CLT), Sai số chuẩn. |
| Chương 8 | Ước lượng Khoảng (Interval Estimation) | [E4], [E5] | Chờ triển khai | Cụ thể hóa ước lượng khoảng cho $\mu$ (dùng $z$ và $t$-Student) và tỷ lệ $p$; Ứng dụng kiểm toán và nghiên cứu thị trường [E5]. |
| Chương 9 | Kiểm định Giả thuyết (Hypothesis Testing) | [E4], [E5] | Chờ triển khai | Quy trình kiểm định giả thuyết $H_0/H_a$, Sai lầm loại I ($\alpha$) & loại II ($\beta$), Giá trị $p$-value trong quyết định quản trị [E5]. |
| Chương 10 | So sánh Hai Tổng thể | [E4], [E5] | Chờ triển khai | So sánh hai giá trị trung bình $\mu_1 - \mu_2$, hai tỷ lệ $p_1 - p_2$, mẫu độc lập vs mẫu cặp. |
| Chương 11 | Phân tích Phương sai (ANOVA) | [E3], [E4] | Chờ triển khai | So sánh nhiều giá trị trung bình, Thiết kế thực nghiệm hoàn toàn ngẫu nhiên và Khối ngẫu nhiên. |
| Chương 12 | Kiểm định Phi tham số & Bảng chéo (Chi-square) | [E1], [E4], [E7] | Chờ triển khai | Kiểm định tính độc lập và độ phù hợp trên Bảng chéo (Crosstabulation từ [E7]) cho dữ liệu thang Nominal [E1]. |
| Chương 14 | Hồi quy Tuyến tính Đơn (Simple Linear Regression) | [E1], [E6], [E7], [E5] | Chờ triển khai | Mô hình hóa đường xu hướng (Trendline từ [E7]) giữa biến $y$ và $x$, Bình phương bé nhất, Đánh giá $R^2$, Kiểm định $t$ và $F$. |
| Chương 15 | Hồi quy Tuyến tính Bội (Multiple Regression) | [E4], [E7], [E5] | Chờ triển khai | Tích hợp nhiều biến dự báo, Phân tích hiện tượng đa cộng tuyến, Ứng dụng dự báo tài chính và kinh tế vĩ mô [E5]. |
| Chương 18 | Phân tích Chuỗi thời gian & Dự báo (Time Series) | [E1], [E6], [E5] | Chờ triển khai | Mở rộng dạng dữ liệu Time Series từ [E1]: Thành phần xu hướng, Mùa vụ, Chu kỳ; Mô hình San bằng mũ và Trung bình trượt. |
