# Đánh Giá Thuật Toán

## 1. SELECTION SORT
**Phân Loại:**
- Offline sorting: Cần toàn bộ dữ liệu để bắt đầu sắp xếp.

**Ý Tưởng Sơ Bộ:**
Thuật toán Selection Sort hoạt động bằng cách liên tục chọn phần tử nhỏ nhất trong danh sách chưa được sắp xếp và di chuyển nó đến vị trí đã được sắp xếp.

**Thuật Toán:**
1. Bước 1: Bắt đầu từ đầu mảng, giả sử phần tử đầu tiên là nhỏ nhất.
2. Bước 2: Tìm phần tử nhỏ nhất trong danh sách chưa được sắp xếp.
3. Bước 3: Đổi chỗ phần tử nhỏ nhất với phần tử đầu tiên của danh sách chưa được sắp xếp.
4. Bước 4: Di chuyển ranh giới của danh sách đã sắp xếp sang phải một phần tử.
5. Lặp lại quá trình cho đến khi toàn bộ mảng được sắp xếp.

**Độ Phức Tạp:**
- Trường hợp tốt nhất: Mảng đã sắp xếp sẵn (vẫn cần O(n²) so sánh).
- Trường hợp trung bình: O(n²).
- Trường hợp xấu nhất: O(n²).

**Đặc Trưng:**
Đặc điểm nổi bật của Selection Sort: cách hoạt động dựa trên việc tìm kiếm và đổi chỗ.

**Nhận Xét Khác:**
- Ưu điểm: Đơn giản, dễ hiểu, dễ cài đặt. Không cần bộ nhớ thêm.
- Nhược điểm: Không hiệu quả với mảng lớn.

**Tham Khảo:**
- Selection Sort - GeeksforGeeks
  https://www.geeksforgeeks.org/selection-sort/

## 2. INTERCHANGE SORT
**Phân Loại:**
- Offline sorting: Cần toàn bộ dữ liệu để bắt đầu sắp xếp.

**Ý Tưởng Sơ Bộ:**
Thuật toán Interchange Sort là một thuật toán sắp xếp đơn giản dựa trên việc đổi chỗ.

**Thuật Toán:**
1. Bước 1: Khởi tạo hai vòng lặp lồng nhau. Vòng lặp bên ngoài chạy từ 0 đến n-1, vòng lặp bên trong chạy từ i+1 đến n.
2. Bước 2: So sánh từng cặp phần tử và đổi chỗ nếu phần tử sau nhỏ hơn phần tử trước.
3. Bước 3: Lặp lại cho đến khi toàn bộ mảng được sắp xếp.

**Độ Phức Tạp:**
- Trường hợp tốt nhất: Khi mảng đã được sắp xếp, độ phức tạp là O(n²).
- Trường hợp trung bình: O(n²).
- Trường hợp xấu nhất: O(n²).

**Đặc Trưng:**
Đặc điểm nổi bật Interchange Sort: nổi bật với cách tiếp cận đổi chỗ trực tiếp.

**Nhận Xét Khác:**
- Ưu điểm: Đơn giản, dễ hiểu, dễ cài đặt.
- Nhược điểm: Không hiệu quả với mảng lớn.

**Tham Khảo:**
- Interchange Sort - GeeksforGeeks
  https://www.geeksforgeeks.org/interchange-sort/

## 3. INSERTION SORT
**Phân Loại:**
- Offline sorting: Cần toàn bộ dữ liệu để bắt đầu sắp xếp.

**Ý Tưởng Sơ Bộ:**
Thuật toán Insertion Sort hoạt động tương tự như cách sắp xếp bài lá, nơi mỗi lá bài được chèn vào vị trí đúng trong tay đã sắp xếp.

**Thuật Toán:**
1. Bước 1: Bắt đầu từ phần tử thứ hai trong mảng (giả sử phần tử đầu tiên đã được sắp xếp).
2. Bước 2: Chèn phần tử hiện tại vào vị trí đúng trong mảng con đã sắp xếp.
3. Bước 3: Lặp lại cho đến khi toàn bộ mảng được sắp xếp.

**Độ Phức Tạp:**
- Trường hợp tốt nhất: Mảng đã sắp xếp sẵn - O(n).
- Trường hợp trung bình: O(n²).
- Trường hợp xấu nhất: O(n²).

**Đặc Trưng:**
Đặc điểm nổi bật thuật toán Insertion Sort: dễ cài đặt và hiệu quả với mảng nhỏ hoặc gần như đã sắp xếp.

**Nhận Xét Khác:**
- Ưu điểm: Dễ cài đặt, hiệu quả với mảng nhỏ hoặc gần như đã sắp xếp.
- Nhược điểm: Không hiệu quả với mảng lớn.

**Tham Khảo:**
- Insertion Sort - GeeksforGeeks
  https://www.geeksforgeeks.org/insertion-sort/

## 4. BINARY INSERTION SORT
**Phân Loại:**
- Online sorting: sắp xếp từng phần tử khi nhận được.

**Ý Tưởng Sơ Bộ:**
Thuật toán Binary Insertion Sort là phiên bản nâng cao của Insertion Sort, sử dụng tìm kiếm nhị phân để tìm vị trí chèn thích hợp.

**Thuật Toán:**
1. Bước 1: Khởi tạo một vòng lặp với biến đếm i từ 1 đến n-1.
2. Bước 2: Sử dụng tìm kiếm nhị phân để tìm vị trí chèn phần tử hiện tại.
3. Bước 3: Chèn phần tử vào vị trí tìm được và dịch chuyển các phần tử phía sau.
4. Bước 4: Lặp lại cho đến khi toàn bộ mảng được sắp xếp.

**Độ Phức Tạp:**
- Trường hợp tốt nhất: Mảng đã được sắp xếp. Chi phí tìm kiếm nhị phân là O(log n).
- Trường hợp trung bình: O(n log n) cho tìm kiếm và O(n²) cho chèn.
- Trường hợp xấu nhất: O(n²).

**Đặc Trưng:**
Đặc điểm nổi bật của Binary Insertion Sort: kết hợp giữa tìm kiếm nhị phân và chèn.

**Nhận Xét Khác:**
- Ưu điểm: Phù hợp với mảng nhỏ, dễ cài đặt, hiệu quả hơn Insertion Sort thông thường.
- Nhược điểm: Không hiệu quả với mảng lớn.

**Tham Khảo:**
- Binary Insertion Sort - GeeksforGeeks
  https://www.geeksforgeeks.org/binary-insertion-sort/

## 5. BUBBLE SORT
**Phân Loại:**
- Offline sorting: cần toàn bộ dữ liệu để bắt đầu sắp xếp.

**Ý Tưởng Sơ Bộ:**
Thuật toán Bubble Sort là thuật toán sắp xếp đơn giản nhất, hoạt động bằng cách lặp đi lặp lại qua danh sách, so sánh từng cặp phần tử liền kề và đổi chỗ nếu chúng không theo thứ tự.

**Thuật Toán:**
1. Bước 1: Khởi tạo một vòng lặp i chạy từ 0 đến n-1.
2. Bước 2: Khởi tạo vòng lặp j chạy từ 0 đến n-i-1.
3. Bước 3: So sánh từng cặp phần tử liền kề và đổi chỗ nếu chúng không theo thứ tự.
4. Bước 4: Lặp lại cho đến khi không còn cặp phần tử nào để đổi chỗ.

**Độ Phức Tạp:**
- Trường hợp tốt nhất: Mảng đã sắp xếp - O(n) (với cải tiến nhận diện mảng đã sắp xếp).
- Trường hợp trung bình: O(n²).
- Trường hợp xấu nhất: O(n²).

**Đặc Trưng:**
Đặc điểm nổi bật Bubble Sort: có đặc điểm nổi bật là đơn giản và dễ hiểu.

**Nhận Xét Khác:**
- Ưu điểm: Đơn giản, dễ hiểu, và dễ cài đặt.
- Nhược điểm: Không hiệu quả với mảng lớn.

**Tham Khảo:**
- Bubble Sort - GeeksforGeeks
  https://www.geeksforgeeks.org/bubble-sort/
