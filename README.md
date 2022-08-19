# cai-may-in-may-chu-va-may-chia-se
Cách cài máy in cho máy chủ và máy chia sẽ, cách fix lỗi máy in

# CÁCH CÀI MÁY IN MÁY CHỦ VÀ MÁY CHIA SẺ KHI GẶP LỖI #

## Khi cài máy in cho máy chủ và máy tính chia sẻ thì đầy dãy các hướng dẫn trên mạng, nhưng khi gặp lỗi thì có nhiều hướng dẫn làm kiểu này làm kiểu khác, đôi lúc cũng không hiệu quả. Tôi sẽ dùng cách này giúp các bạn fix lỗi thành công như ý muốn ##

Cài máy in cho máy chủ và bật chia sẻ, cài máy in chia sẻ

## Bước 1: Chia sẻ máy in qua mạng Lan với máy tính khác (Thao tác này sẽ được thực hiện trên máy tính đang được kết nối với máy in) ##

1. Các bạn vào Control Panel rồi chọn Devices and Printers

![1](https://user-images.githubusercontent.com/82578024/163692698-6dd618de-8a07-446a-a93f-eca8f7a38b6e.jpg)

2. Tiếp theo, hãy check dòng Set as default printer rồi nhấn Printer properties

![1](https://user-images.githubusercontent.com/82578024/163692726-6bac7049-58b5-4ffb-b6f9-85c4c9eb1ffb.jpg)

3. Trong hộp thoại mới mở ra, hãy chọn tab Sharing rồi check vào dòng Share this printer. Sau đó bấm OK

![1](https://user-images.githubusercontent.com/82578024/163692772-b2a86e7d-037a-4904-a8fa-ed2e154e0fbe.jpg)

4. Quay lại Control Panel, hãy click Network and Sharing Center

![1](https://user-images.githubusercontent.com/82578024/163692804-0b22f6bf-613c-489c-9a80-f3fa7a49deb5.jpg)

5. Hãy nhấn Change advanced sharing settings

![1](https://user-images.githubusercontent.com/82578024/163692825-dd9b5517-ecab-49a9-8897-e531f8e62cec.jpg)

6. Hãy đánh dấu vào các tùy chọn được đánh số bên dưới

![1](https://user-images.githubusercontent.com/82578024/163692853-a4ef705e-07ee-4cb3-b290-24eb41da8b3c.jpg)

7. Kéo xuống mục Password protecting sharing rồi đánh dấu vào tùy chọn Turn off password protected sharing. Sau đó, nhấn Save changes

![1](https://user-images.githubusercontent.com/82578024/163692872-634b208a-793b-4762-9ec3-a61dc8db10c8.jpg)

## Bước 2: Truy cập vào máy in đã được chia sẻ trong mạng LAN (Thao tác này sẽ được thực hiện trên máy tính cần in tài liệu) ##

Các bạn vào Control Panel > Devices and Printers rồi click Add a Printer

![1](https://user-images.githubusercontent.com/82578024/163692938-0647a5b2-fa13-4fcc-9369-53fb8edbdbb0.jpg)

Trong cửa sổ hiện ra bạn chọn Add a network, Wireless or Bluetooth printer, khi hiện ra cửa sổ sau bạn chọn The printer that I want isn't listed.

![1](https://user-images.githubusercontent.com/82578024/163692972-6ee99d4e-984c-4856-9217-1e1f3bc0ea7f.jpg)

Bạn hãy đánh dấu vào tùy chọn Select a shared printer by name và chọn đúng tên máy tính đã share máy in rồi bấm Next là xong.

![1](https://user-images.githubusercontent.com/82578024/163693030-3da5ee7c-019a-45ad-a8e6-92e613bbb509.jpg)

Ví dụ: bạn đặt tên máy chủ là BsThanh và tên máy in chia sẻ là CanonLBP2900, cú pháp ta làm như sau:

![1](https://user-images.githubusercontent.com/82578024/163693100-20321bf2-7bc0-422f-aa68-4a1e07b8069e.jpg)

## FIX LỖI CÀI MÁY IN (MÁY BÁO LỖI CÀI MÁY IN NHƯ THẾ NÀO ĐI CHĂNG NỮA FIX KIỂU NÀY LÀ OK HẾT ##

Khi cài máy in đôi lúc gặp lỗi cực kì khó chịu. Vì thế tôi đề nghị một cách hữu hiệu, trước khi cài máy in nên Reset network, sau cài máy in gặp lỗi thì tiến hành Reset network rồi cài lại máy in vẫn ok các bác ạ! Trên biểu tượng mạng, bấm chuột phải và chọn dòng cuối.
![1](https://user-images.githubusercontent.com/82578024/163693304-3a8cbd0c-78b7-43cb-80f3-03d3c2c07010.jpg)
![1](https://user-images.githubusercontent.com/82578024/163693326-bf921a02-e46e-41e7-87f1-a936fa1f9710.jpg)

Chọn dòng cuối cùng, Chọn Network reset. Bấm yes, biểu tượng mạng sẽ mất mạng, máy tính sẽ khởi động lại sau 5 phút, sau khi máy tính tự động khởi động trở lại, chờ khoản 10 phút, sau đó cài đặt máy in diễn ra suôn sẻ, OK!

Cài máy in cho máy chủ gặp lỗi cũng sử dụng Fix này là OK!

### Một lưu ý là máy chủ và máy chia sẻ phải cùng số Bit, trường hợp máy chủ 64Bit và máy chia sẻ là 32Bit đôi khi vẫn được nhưng điều ngược lại thì không! ###

Trường hợp vẫn còn báo lỗi, xem kĩ nó là lỗi gì để sửa, sửa thì phải đồng loạt cả máy chủ và máy được chia sẻ.

## Lỗi 0x0000011b ##

Mở NotePad lên Copy đoạn mã bên dưới rồi bấm **Save As** với tên: 0x0000011b.cmd rồi run chúng với quyền **Run Administrator**

```php
@echo off
cls
echo.
echo "Fixing registry value..."
echo.
REG ADD HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\Print\ /f /v RpcAuthnLevelPrivacyEnabled /t REG_DWORD /d 0


echo.
echo "Restarting Print Spooler Service"

echo.
net stop spooler
net start spooler
pause
```

Chúc các bác thành công.

[Chia sẻ địa điểm Google map](https://maps.app.goo.gl/wmAPRFYyF3nNeHd87)
