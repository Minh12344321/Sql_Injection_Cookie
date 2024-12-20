![{72025454-4C92-4DAB-8384-B6A41B07A9AF}](https://github.com/user-attachments/assets/fca3d3d8-15ff-49e9-9163-bbb23b710041)

- Bước 1 Test username với password
  ![{CBE8AB5E-22A7-4CD8-91F8-81B27228E422}](https://github.com/user-attachments/assets/e45482fb-5114-4474-b820-20f50e4100c4)


- Bước 2 Cách 1 : Nếu không đúng nhập thêm ' OR 1=1 -- - vào sau username
  ![{6228D62A-9E3D-4E01-AD3B-B78BD3F83FF0}](https://github.com/user-attachments/assets/48857d30-a735-4553-81ec-9e79c3edfca4)

  thêm ' OR 1=1 -- - vào sau password
  ![{5F2F81C0-5BC5-411C-87A0-34DA5AE6245C}](https://github.com/user-attachments/assets/2af2ed0b-6a01-4579-b8b2-41682b975718)

  
- Bước 3 Đăng nhập tìm được flag
![{60E260C7-DA86-461E-94A7-B02C1278DDE3}](https://github.com/user-attachments/assets/f0161993-e652-4c10-8934-2a2a2c4abaf4)


![{50A95C46-3638-4E14-B062-860C16D4FEE8}](https://github.com/user-attachments/assets/033c7be2-4460-44cb-80e1-f027c61b2388)
![{46BFEB62-4C11-4A27-B3D6-52F0CAE5EAE3}](https://github.com/user-attachments/assets/18e24985-3002-4fe4-a46a-f7099a820e32)
![{EF3EDD7B-1B03-4D2F-8989-80A689B3B4A4}](https://github.com/user-attachments/assets/b01433ff-295c-4618-b806-e50694d02a85)

![{C6382275-7E2D-4348-9249-ADF1B8F524D6}](https://github.com/user-attachments/assets/b6af5669-75a7-487c-bedb-6a666ca8c07f)
![{394CDD9F-4FAB-490F-9298-A781A53F105A}](https://github.com/user-attachments/assets/8e1fa189-b65a-4c6a-bd1e-1eabe84a5871)

![{7F2DFD1E-2FCE-484C-B1CF-B51E26478346}](https://github.com/user-attachments/assets/063bd04a-cf7e-4323-99b9-945a96b06961)
![{F52B99AA-88ED-4F0C-903A-5182495D3355}](https://github.com/user-attachments/assets/f6f116bf-bd9d-4616-b243-a5495127449d)
![{BEDEDA3F-46ED-4F3A-9FA8-79B2DC00096B}](https://github.com/user-attachments/assets/4b19cbb2-a2ad-4d48-a4f2-338bd3504f15)


## Có 3 loại SQL injection
![{2CF7EEA2-0BA4-43F3-AABC-AA52B90598C9}](https://github.com/user-attachments/assets/0a9b1cc8-ccb1-4d08-b77e-935a2dc0019a)

### In band Sql injection (Classic) ổ điển
- Tấn công trực tiếp vào ứng dụng,kẻ tấn công sẽ nhận phản hồi từ ứng dụng đó

# Có 2 kiểu tấn công 
+ Error -based SQLi : Lợi dụng thông báo lỗi cửa cơ sở dữ liệu để thu thập thông tin
+ Union -based SQLi : Sử dụng union select kết hợp nhiều truy vấn sql và lấy dữ liệu

### Blind Sql injecttion 
- Ứng dụng không báo lỗi trực tiếp,kẻ tấn công  suy luận thông quan phản hồi (http status, time)
+ Boolean-based blind sqli : Dựa vào phản hồi đúng/sai để suy ra dữ liệu
+ Time -based blind sqli : Dựa vào câu lệnh sleep() đo thời gian phản
+ Content-based blind sqli : Dưa vào nội dung để suy đoán từ cơ sở dữ liệu

### Out of band sql inhection 
- Kẻ tấn công không thể lấy dữ liệu từ phản hồi trực tiếp hoặc đoán thời gian
- ữ liệu bị đánh cắp được gửi tới máy chủ từ xa thông qua DNS hoặc HTTP requests.





 
