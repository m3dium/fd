# fd


![image](https://user-images.githubusercontent.com/72652376/182317886-99ca9dd6-4323-4126-9891-36c678dcee7f.png)

Chương trình này viết bằng C

đầu tiên khai báo một mảng buf[32]

![image](https://user-images.githubusercontent.com/72652376/182319932-fa84627c-da29-4e1f-8643-ab1f585b7b02.png)

Đoạn IF đầu tiên nếu nhập <2 ký tự thì sẽ in ra "pass argv[1] a number". Trông nó như này

![image](https://user-images.githubusercontent.com/72652376/182320244-609daffd-d99b-442a-a3da-636a19ccef7f.png)

Tiếp tục là dòng

int fd = atoi( argv[1] ) - 0x1234;

Hàm int atoi(const char *str) trong Thư viện C chuẩn chuyển đổi một chuỗi được trỏ tới bởi tham số str thành một số nguyên (kiểu int).

Nghĩa là fd trả về một số nguyên (gồm cả việc trừ đi 0x1234)

![image](https://user-images.githubusercontent.com/72652376/182321721-1866b5a3-f0be-496f-a1ce-a05c6bc0bb3f.png)
