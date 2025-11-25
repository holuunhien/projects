🐍 Python – Ví dụ xử lý mảng
# Tính tổng các phần tử trong mảng
numbers = [1, 2, 3, 4, 5]
total = sum(numbers)
print("Tổng =", total)

# Lọc phần tử chẵn
even = [n for n in numbers if n % 2 == 0]
print("Số chẵn:", even)
🐍 Python – Ví dụ xử lý mảng
# Tính tổng các phần tử trong mảng
numbers = [1, 2, 3, 4, 5]
total = sum(numbers)
print("Tổng =", total)

# Lọc phần tử chẵn
even = [n for n in numbers if n % 2 == 0]
print("Số chẵn:", even)

💻 C++ – Ví dụ xử lý mảng
#include <iostream>
using namespace std;

int main() {
    int arr[] = {1, 2, 3, 4, 5};
    int total = 0;

    for (int x : arr) {
        total += x;
    }

    cout << "Tong = " << total << endl;

    return 0;
}

⚡ JavaScript – Ví dụ xử lý mảng
// Tính tổng
const arr = [1, 2, 3, 4, 5];
const total = arr.reduce((a, b) => a + b, 0);
console.log("Tổng =", total);

// Lọc số lẻ
const odd = arr.filter(x => x % 2 === 1);
console.log("Số lẻ:", odd);

📂 Cấu trúc thư mục
/
├── README.md
└── drawing.svg      # Hình được tạo bằng Inkscape

⭐ Góp ý & Phát triển

Bạn có thể mở issue hoặc pull request nếu muốn đóng góp thêm các ví dụ hoặc minh hoạ.
💻 C++ – Ví dụ xử lý mảng
#include <iostream>
using namespace std;

int main() {
    int arr[] = {1, 2, 3, 4, 5};
    int total = 0;

    for (int x : arr) {
        total += x;
    }

    cout << "Tong = " << total << endl;

    return 0;
}

⚡ JavaScript – Ví dụ xử lý mảng
// Tính tổng
const arr = [1, 2, 3, 4, 5];
const total = arr.reduce((a, b) => a + b, 0);
console.log("Tổng =", total);

// Lọc số lẻ
const odd = arr.filter(x => x % 2 === 1);
console.log("Số lẻ:", odd);

📂 Cấu trúc thư mục
/
├── README.md
└── drawing.svg      # Hình được tạo bằng Inkscape

⭐ Góp ý & Phát triển

Bạn có thể mở issue hoặc pull request nếu muốn đóng góp thêm các ví dụ hoặc minh hoạ.
