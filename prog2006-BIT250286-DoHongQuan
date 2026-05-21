Bai 1

#include <iostream>

using namespace std;

int main() {
    int so;
    cout << "Nhap vao mot so nguyen: ";
    cin >> so;

    // Kiem tra chan le
    if (so % 2 == 0) {
        cout << "So " << so << " la so chan." << endl;
    } else {
        cout << "So " << so << " la so le." << endl;
    }

    return 0;
}

Bai 2

#include <iostream>

using namespace std;

int main() {
    double W, H;

    // Nhap du lieu tu ban phim
    cout << "Nhap chieu rong (W): ";
    cin >> W;
    cout << "Nhap chieu cao (H): ";
    cin >> H;

    // Tinh dien tich
    double dienTich = W * H;

    // In ket qua ra man hinh
    cout << "Dien tich hinh chu nhat la: " << dienTich << endl;

    return 0;
}

Bai 3

#include <iostream>

using namespace std;

int main() {
    int n;

    // Nhap so n tu ban phim
    cout << "Nhap vao so n: ";
    cin >> n;

    // In cac so tu n xuong 1 bang vong lap for
    cout << "Cac so tu " << n << " xuong 1 la: " << endl;
    for (int i = n; i >= 1; i--) {
        cout << i << " ";
    }
    cout << endl; // Xuong dong khi ket thuc

    return 0;
}

Bai 4 

#include <iostream>

using namespace std;

int main() {
    double a, b;

    // Nhap he so a va b tu ban phim
    cout << "Nhap he so a: ";
    cin >> a;
    cout << "Nhap he so b: ";
    cin >> b;

    // Bien luan phuong trinh ax + b = 0
    if (a == 0) {
        if (b == 0) {
            cout << "Phuong trinh co vo so nghiem." << endl;
        } else {
            cout << "Phuong trinh vo nghiem." << endl;
        }
    } else {
        // Tinh nghiem duy nhat
        double x = -b / a;
        cout << "Phuong trinh co nghiem duy nhat x = " << x << endl;
    }

    return 0;
}

Bai 5

#include <iostream>

using namespace std;

// Ham tim gia tri lon nhat cua mang
int timGiaTriLonNhat(int mang[], int soPhanTu) {
    // Gia su phan tu dau tien la lon nhat
    int giaTriMax = mang[0];

    // Duyet qua cac phan tu con lai trong mang
    for (int i = 1; i < soPhanTu; i++) {
        if (mang[i] > giaTriMax) {
            giaTriMax = mang[i]; // Cap nhat lai max neu tim thay so lon hon
        }
    }

    return giaTriMax; // Tra ve ket qua cuoi cung
}

int main() {
    // Thu nghiem voi mot mang co san
    int MyArray[] = {15, 4, 23, 8, 42, 16};
    
    // Tinh so luong phan tu cua mang
    int n = sizeof(MyArray) / sizeof(MyArray[0]);

    // Goi ham va in ket qua
    int ketQua = timGiaTriLonNhat(MyArray, n);
    cout << "Gia tri lon nhat trong mang la: " << ketQua << endl;

    return 0;
}

Bai 6

#include <iostream>

using namespace std;

int main() {
    int ngay;

    // Nhap so tu ban phim
    cout << "Nhap vao mot so (1-7): ";
    cin >> ngay;

    // Su dung switch-case de kiem tra
    switch (ngay) {
    case 1:
        cout << "Chu Nhat" << endl;
        break;
    case 2:
        cout << "Thu Hai" << endl;
        break;
    case 3:
        cout << "Thu Ba" << endl;
        break;
    case 4:
        cout << "Thu Tu" << endl;
        break;
    case 5:
        cout << "Thu Nam" << endl;
        break;
    case 6:
        cout << "Thu Sau" << endl;
        break;
    case 7:
        cout << "Thu Bay" << endl;
        break;
    default:
        cout << "So nhap vao khong hop le! Vui long nhap tu 1 den 7." << endl;
        break;
    }

    return 0;
}

Bai 7 

#include <iostream>

using namespace std;

int main() {
    int n;

    // Nhap so nguyen duong n
    cout << "Nhap vao so nguyen duong n: ";
    cin >> n;

    // Kiem tra dieu kien neu nguoi dung nhap sai
    if (n <= 0) {
        cout << "Vui long nhap mot so lon hon 0!" << endl;
        return 0; // Ket thuc chuong trinh
    }

    // --- CACH 1: DUNG VONG LAP FOR ---
    long long tongFor = 0; // Dung kieu long long de tranh bi tran so khi n lon
    for (int i = 1; i <= n; i++) {
        tongFor += i; // Tuong duong tongFor = tongFor + i
    }
    cout << "(Cach 1 - For) Tong S = " << tongFor << endl;


    // --- CACH 2: DUNG CONG THUC TOAN HOC (TOI UU NHAT) ---
    // Ep kieu (long long) truoc khi nhan de dam bao khong bi tran du lieu
    long long tongCongThuc = (long long)n * (n + 1) / 2;
    cout << "(Cach 2 - Cong thuc) Tong S = " << tongCongThuc << endl;

    return 0;
}



}
