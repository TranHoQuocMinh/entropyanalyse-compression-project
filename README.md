# entropyanalyse-compression-project
Phân tích entropy &amp; nén dữ liệu mạng (gzip, Brotli, JSON, Protobuf)
network-compression-project/
│
├── main.py                  # Chạy toàn bộ
├── utils.py                 # Hàm chung
├── requirements.txt         # pip install -r
├── README.md                # Hướng dẫn nhóm
│
├── data/
│   ├── raw/                 # .pcap, .proto
│   └── processed/           # .pkl, .csv
│
├── scripts/
│   ├── capture.py           # TV1
│   ├── extract_payload.py   # TV1
│   ├── generate_data.py     # TV1
│   ├── entropy_compress.py  # TV2
│   ├── structured_compress.py # TV3
│   └── visualize.py         # TV5
│
├── report/
│   ├── figures.png
│   ├── report.pdf
│   └── essay.pdf            # Bonus tiểu luận
│
└── .gitignore               # Tự động tạo
