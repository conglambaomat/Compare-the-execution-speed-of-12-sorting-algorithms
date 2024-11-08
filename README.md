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

## 6. SHAKE/SHAKER SORT
**Phân Loại:**
- Offline sorting: cần toàn bộ dữ liệu để bắt đầu sắp xếp.

**Ý Tưởng Sơ Bộ:**
Thuật toán Shaker Sort là một biến thể của Bubble Sort, trong đó thay vì chỉ di chuyển các phần tử theo một chiều, nó di chuyển chúng theo cả hai chiều.

**Thuật Toán:**
1. Bước 1: Khởi tạo hai biến đánh dấu biên trái và biên phải của mảng.
2. Bước 2: Di chuyển từ trái sang phải và đổi chỗ các phần tử nếu chúng không theo thứ tự.
3. Bước 3: Giảm biên phải và di chuyển từ phải sang trái, đổi chỗ các phần tử nếu cần.
4. Bước 4: Lặp lại cho đến khi biên trái và biên phải gặp nhau.

**Độ Phức Tạp:**
- Trường hợp tốt nhất: O(n) - Khi mảng đã sắp xếp.
- Trường hợp trung bình: O(n²).
- Trường hợp xấu nhất: O(n²).

**Đặc Trưng:**
Đặc điểm nổi bật Shaker Sort: Là một phiên bản cải tiến của Bubble Sort, giảm số lần duyệt không cần thiết.

**Nhận Xét Khác:**
- Ưu điểm: Giảm số lần duyệt không cần thiết so với Bubble Sort.
- Nhược điểm: Vẫn không hiệu quả với mảng lớn.

**Tham Khảo:**
- Cocktail Sort - GeeksforGeeks
  https://www.geeksforgeeks.org/cocktail-sort/

## 7. COUNTING SORT
**Phân Loại:**
- Offline sorting: Cần toàn bộ dữ liệu để bắt đầu sắp xếp.

**Ý Tưởng Sơ Bộ:**
Thuật toán Counting Sort sắp xếp các phần tử bằng cách đếm số lần xuất hiện của mỗi giá trị riêng biệt.

**Thuật Toán:**
1. Bước 1: Tìm giá trị lớn nhất trong mảng để xác định phạm vi của mảng đếm.
2. Bước 2: Khởi tạo mảng đếm với tất cả giá trị bằng 0.
3. Bước 3: Đếm số lần xuất hiện của mỗi giá trị trong mảng và lưu vào mảng đếm.
4. Bước 4: Tính toán vị trí chính xác của mỗi phần tử trong mảng đếm.
5. Bước 5: Xây dựng mảng đã sắp xếp bằng cách duyệt ngược qua mảng ban đầu và sử dụng mảng đếm để xác định vị trí.

**Độ Phức Tạp:**
- Trường hợp tốt nhất: O(n+k) - với k là phạm vi giá trị của các phần tử.
- Trường hợp trung bình: O(n+k).
- Trường hợp xấu nhất: O(n+k).

**Đặc Trưng:**
Đặc điểm nổi bật Counting Sort: Không thực hiện so sánh phần tử, hiệu quả với mảng có phạm vi giá trị nhỏ.

**Nhận Xét Khác:**
- Ưu điểm: Hiệu quả cao với các mảng chứa các phần tử có phạm vi giá trị nhỏ.
- Nhược điểm: Không hiệu quả với các mảng có phạm vi giá trị lớn.

**Tham Khảo:**
- Counting Sort - GeeksforGeeks
  https://www.geeksforgeeks.org/counting-sort/

## 8. QUICK SORT
**Phân Loại:**
- Offline sorting: Cần toàn bộ dữ liệu để bắt đầu sắp xếp.

**Ý Tưởng Sơ Bộ:**
Thuật toán Quick Sort là một thuật toán sắp xếp chia để trị, trong đó chọn một phần tử làm trục và phân chia mảng thành hai phần sao cho các phần tử nhỏ hơn trục ở bên trái và các phần tử lớn hơn trục ở bên phải.

**Thuật Toán:**
1. Bước 1: Chọn một phần tử làm trục.
2. Bước 2: Phân chia mảng thành hai phần sao cho các phần tử nhỏ hơn trục ở bên trái và các phần tử lớn hơn trục ở bên phải.
3. Bước 3: Đệ quy sắp xếp hai phần của mảng.

**Độ Phức Tạp:**
- Trường hợp tốt nhất: O(n log n) - khi trục chia mảng thành hai phần gần bằng nhau.
- Trường hợp trung bình: O(n log n).
- Trường hợp xấu nhất: O(n²) - khi trục là phần tử lớn nhất hoặc nhỏ nhất.

**Đặc Trưng:**
Đặc điểm nổi bật Quick Sort: có đặc điểm nổi bật là nhanh và hiệu quả trong thực tế.

**Nhận Xét Khác:**
- Ưu điểm: Rất nhanh cho các tập dữ liệu lớn, sử dụng bộ nhớ hiệu quả.
- Nhược điểm: Hiệu quả phụ thuộc vào việc chọn trục, có thể không ổn định.

**Tham Khảo:**
- Quick Sort - GeeksforGeeks
  https://www.geeksforgeeks.org/quick-sort/

## 9. MERGE SORT
**Phân Loại:**
- Offline sorting: cần toàn bộ dữ liệu để bắt đầu sắp xếp.

**Ý Tưởng Sơ Bộ:**
Thuật toán Merge Sort là thuật toán sắp xếp dựa trên kỹ thuật chia để trị, trong đó mảng được chia thành hai nửa và mỗi nửa được sắp xếp đệ quy trước khi được hợp nhất.

**Thuật Toán:**
1. Bước 1: Chia mảng thành hai nửa.
2. Bước 2: Đệ quy sắp xếp hai nửa.
3. Bước 3: Hợp nhất hai nửa đã được sắp xếp thành một mảng đã sắp xếp.

**Độ Phức Tạp:**
- Trường hợp tốt nhất: O(n log n).
- Trường hợp trung bình: O(n log n).
- Trường hợp xấu nhất: O(n log n).

**Đặc Trưng:**
Điểm nổi bật của Merge Sort là tính ổn định và hiệu quả ngay cả trong trường hợp xấu nhất.

**Nhận Xét Khác:**
- Ưu điểm: Ổn định, hiệu quả tốt ngay cả trong trường hợp xấu nhất.
- Nhược điểm: Cần thêm bộ nhớ cho mảng phụ.

**Tham Khảo:**
- Merge Sort - GeeksforGeeks
  https://www.geeksforgeeks.org/merge-sort/

## 10. HEAP SORT
**Phân Loại:**
- Offline sorting: Cần toàn bộ dữ liệu để bắt đầu sắp xếp.

**Ý Tưởng Sơ Bộ:**
Thuật toán Heap Sort là một thuật toán sắp xếp dựa trên cấu trúc dữ liệu heap (đống), trong đó mảng được coi như là một heap và các phần tử được sắp xếp bằng cách liên tục lấy phần tử lớn nhất từ heap.

**Thuật Toán:**
1. Bước 1: Xây dựng một heap từ mảng đầu vào.
2. Bước 2: Liên tục trích xuất phần tử lớn nhất từ heap và đặt nó vào vị trí cuối cùng trong mảng đã sắp xếp.
3. Bước 3: Giảm kích thước của heap và lặp lại cho đến khi toàn bộ mảng được sắp xếp.

**Độ Phức Tạp:**
- Trường hợp tốt nhất: O(n log n).
- Trường hợp trung bình: O(n log n).
- Trường hợp xấu nhất: O(n log n).

**Đặc Trưng:**
Điểm nổi bật của Heap Sort là khả năng sắp xếp trong thời gian O(n log n) ổn định.

**Nhận Xét Khác:**
- Ưu điểm: Hiệu quả, độ phức tạp O(n log n) ổn định.
- Nhược điểm: Cần cấu trúc dữ liệu heap, có thể không ổn định.

**Tham Khảo:**
- Heap Sort - GeeksforGeeks
  https://www.geeksforgeeks.org/heap-sort/

## 11. SHELL SORT
**Phân Loại:**
- Offline sorting: Cần toàn bộ dữ liệu để bắt đầu sắp xếp.

**Ý Tưởng Sơ Bộ:**
Thuật toán Shell Sort là một cải tiến của thuật toán Insertion Sort, trong đó mảng được chia thành các khoảng cách nhỏ hơn và sắp xếp từng khoảng cách trước khi sắp xếp toàn bộ mảng.

**Thuật Toán:**
1. Bước 1: Chia mảng thành các khoảng cách nhỏ hơn.
2. Bước 2: Sắp xếp từng khoảng cách bằng thuật toán Insertion Sort.
3. Bước 3: Giảm kích thước của khoảng cách và lặp lại cho đến khi khoảng cách là 1.

**Độ Phức Tạp:**
- Trường hợp tốt nhất: O(n log n).
- Trường hợp trung bình: Phụ thuộc vào lựa chọn khoảng cách.
- Trường hợp xấu nhất: O(n log² n).

**Đặc Trưng:**
Shell Sort nổi bật với việc giảm dần khoảng cách và hiệu quả cao hơn Insertion Sort.

**Nhận Xét Khác:**
- Ưu điểm: Shell Sort cải tiến từ Insertion Sort, hiệu quả với mảng lớn.
- Nhược điểm: Hiệu quả phụ thuộc vào lựa chọn khoảng cách.

**Tham Khảo:**
- Shell Sort - GeeksforGeeks
  https://www.geeksforgeeks.org/shell-sort/

## 12. RADIX SORT
**Phân Loại:**
- Offline sorting: cần toàn bộ dữ liệu để bắt đầu sắp xếp.

**Ý Tưởng Sơ Bộ:**
Thuật toán Radix Sort sắp xếp dãy bằng cách xử lý từng chữ số của các số nguyên.

**Thuật Toán:**
1. Bước 1: Bắt đầu từ chữ số ít quan trọng nhất.
2. Bước 2: Sắp xếp các phần tử theo chữ số hiện tại sử dụng thuật toán sắp xếp ổn định như Counting Sort.
3. Bước 3: Chuyển sang chữ số quan trọng tiếp theo và lặp lại cho đến khi toàn bộ dãy được sắp xếp.

**Độ Phức Tạp:**
- Trường hợp tốt nhất: O(nk) - với k là số chữ số của số lớn nhất.
- Trường hợp trung bình: O(nk).
- Trường hợp xấu nhất: O(nk).

**Đặc Trưng:**
Radix Sort nổi bật với khả năng sắp xếp hiệu quả khi các phần tử có cùng số lượng chữ số.

**Nhận Xét Khác:**
- Ưu điểm: Hiệu quả cao với các dãy có số lượng chữ số nhỏ.
- Nhược điểm: Không hiệu quả với các dãy có phạm vi giá trị lớn.

**Tham Khảo:**
- Radix Sort - GeeksforGeeks
  https://www.geeksforgeeks.org/radix-sort/
