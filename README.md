# Team minekraft - DataFlow 2025

## Giải thích bài toán và thiết kế hệ thống:
**Dữ liệu và yêu cầu bài toán:**
* Các thông tin nằm tại link Kaggle của cuộc thi: [Dữ liệu và yêu cầu bài toán](https://www.kaggle.com/datasets/grizmo/dataflow2025-product-recommendation)

**Thiết kế hệ thống:**
![ProductRec drawio](https://github.com/user-attachments/assets/66d619e0-2bcf-4922-b136-2bf4d4631964)

* Các thông tin chi tiết được giải thích trong mã nguồn và file Báo cáo (BaoCao.pdf).


## Hướng dẫn cài đặt và chạy project

**Yêu cầu:**

*   Docker và Docker Compose đã được cài đặt trên máy.
*   RAM tối thiểu 32GB.
*   Sử dụng WSL (Windows Subsystem for Linux).

**Các bước thực hiện:**
- Các bước này đã được hướng dẫn trong video đính kèm "huong_dan_chay_code.mp4".

1.  **Giải nén tệp chứa code của bài.**

2.  **Copy file vào trong môi trường WSL.**

3.  **Copy file data vào thư mục `workspace`.**

4.  **Mở WSL terminal ở thư mục đã copy và chạy lệnh sau:**

    ```bash
    docker-compose up --build
    ```

    Lệnh này sẽ build và khởi chạy các container được định nghĩa trong file `docker-compose.yml`.

5.  **Kết nối đến Jupyter Server:**

    *   Mở Visual Studio Code.
    *   Kết nối đến Jupyter server trên Docker với URL sau:

        ```
        http://127.0.0.1:8888/tree?token=mysecrettoken
        ```

6.  **Chạy Notebooks:**

    *   Mở và chạy lần lượt hai file notebook sau:
        *   `data_ana.ipynb`
        *   `data_cleaning_and_feature_engineering.ipynb`
    *   Sử dụng chức năng "Run All" để chạy tất cả các cell trong mỗi notebook và xem kết quả.

7.  **Chạy Model:**

    *   Model sẽ được chạy trên Kaggle.
    *   Link dẫn đến Kaggle Notebook: [Kaggle Notebook](https://www.kaggle.com/code/hctingnht/team-minekraft-dataflow2025?scriptVersionId=224259196).
    *   Kết quả của model sẽ được trình bày chi tiết trong báo cáo.

    * Submission file: [Submission](https://drive.google.com/file/d/11548jL43zieZPNwflbCjzhOo1Ye4A7Hk/view)
    * Google Drive (backup): [Google Drive](https://drive.google.com/drive/folders/1FNEojdlB4bYaEr3I6NwHy17KAHsX_UvV)

---

## 🌟 Nhóm chúng mình

| Role                          | Contributor(s)                                                                                                                                                                                                     |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **🗄️ Thiết kế, chạy và tối ưu mô hình**             | [Phan Hoang Hai](https://github.com/ToJupiter),[Do Binh Minh](https://github.com/dobinhminh06)                                                                                                                                                                  |
| **🧹 Xử lý và làm sạch dữ liệu**  | [Vu Nguyen Duc Minh](https://github.com/D3etMe4n), [Dang Phuong Nam](https://github.com/fdv45fs), [Phan Hoang Hai](https://github.com/ToJupiter) ,[Do Binh Minh](https://github.com/dobinhminh06)                                                                                                                                                                                           |
| **🔍 Data Discovery**         | [Vu Nguyen Duc Minh](https://github.com/D3etMe4n), [Dang Phuong Nam](https://github.com/fdv45fs),[Do Binh Minh](https://github.com/dobinhminh06)                                                                                                                                                                                             |
| **✨ Feature Engineering**    | [Vu Nguyen Duc Minh](https://github.com/D3etMe4n), [Phan Hoang Hai](https://github.com/ToJupiter)  ,[Do Binh Minh](https://github.com/dobinhminh06)                                                                                                                                                                                           |
| **📊 Data Visualization**       | [Vu Nguyen Duc Minh](https://github.com/D3etMe4n), [Nguyen Thanh Vinh](https://github.com/VinhNguyen203) , [Do Binh Minh](https://github.com/dobinhminh06)                                                                                                                                                                                           |
| **⚙️ Thiết kế hệ thống**       | [Vu Nguyen Duc Minh](https://github.com/D3etMe4n), [Phan Hoang Hai](https://github.com/ToJupiter), [Dang Phuong Nam](https://github.com/fdv45fs), [Do Binh Minh](https://github.com/dobinhminh06)                                                                                                                                                                                           |
| **📝 Tổng hợp và báo cáo**    | [Vu Nguyen Duc Minh](https://github.com/D3etMe4n), [Phan Hoang Hai](https://github.com/ToJupiter), [Nguyen Thanh Vinh](https://github.com/VinhNguyen203), [Do Binh Minh](https://github.com/dobinhminh06)                                                                                |


Cảm ơn và xin được ghi nhận tất cả góp ý từ các bạn!

