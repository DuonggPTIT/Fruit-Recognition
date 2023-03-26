Ứng dụng có thể chạy trên Pycharm cho cả Window và Macbook
I. Để chạy
    1. Chọn system interpreter: python 3.8
    2. Run svr_moddel.py
    3. Nhấn vào link trên kết quả chạy
    4. Trên trang web chọn 1 ảnh hoa
    5. Trang web trả về dự đoán từng loại hoa dựa trên model
II. Để huấn luyện mô hình dự đoán hình ảnh
    1. Chọn system interpreter: python 3.8
    2. Gõ lệnh pip install các thư viện trong setup.txt
    3. pip install --upgrade tensorflowjs==3.9.0
    4. Run train.py
    5. Trong terminal của Pycharm, gõ lệnh tensorflowjs_wizard
    6. Gõ directory: models/best.hdf5
    7. Chọn input model: Keras (HDFS)
    8. Chọn output model: Layer Model
    9. Chọn nén model không: No compression
    10. Enter
    11. Chọn No
    12. Enter
    13. Chọn địa chỉ lưu: static/tfjs_model
