---
description: ขั้นตอนการเติมเงินเข้าสู่ระบบ
---

# Top up

{% embed url="https://www.youtube.com/watch?v=Kp7uOj-tj8k&feature=youtu.be" %}

การเติมเงินผ่าน **Payment** มีขั้นตอนดังนี้

ไปยังหน้า **Billing** แล้วใส่จำนวนเงินที่ต้องการเติมลงไปในเมนู Payment หลังจากนั้นให้กดปุ่ม Pay

![](../.gitbook/assets/screenshot-from-2020-02-13-15-2.png)

## **Payment Methods**

สามารถเลือกวิธีการชำระเงินที่ต้องการได้ดังนี้

* **QR Payment:** แสดง QR Code สำหรับการชำระเงิน
* **Bank Transfer:** Admin จะทำการตรวจสอบหลักฐานการชำระเงิน ภายใน 30 นาที ในช่วงเวลาทำการ แล้วจะแจ้งผลให้ผู้ใช้งานผ่านทาง E-mail ที่ลงทะเบียนไว้ 
* **Credit / Debit Card:** ทำตามขั้นตอนของ Omise 
* **Internet Banking:** ทำการขั้นตอนการทำธุรกรรมของธนาคารที่เลือก 
* **Alipay:** ทำการขั้นตอนของ Alipay 
* **Rabbit LINE Pay:** ทำตามขั้นตอนของ Rabbit LINE Pay 

![](../.gitbook/assets/topup_1.png)

### **QR Payment**

ระบบจะทำการแสดง QR Code สำหรับการชำระเงินดังภาพ

![](../.gitbook/assets/payment-ui-dev-9.png)

### Bank Transfer

สำหรับการเลือกผ่าน **Bank Transfer** นั้น มีขั้นตอนต่างจากวิธีอื่น ๆ คือระบบจะแสดงข้อมูลบัญชี ให้ผู้ใช้งานทำการเลือกบัญชีที่ต้องการชำระเงิน โดยสามารถคลิกที่เลขบัญชีที่ต้องการ เพื่อทำการ Copy เลขบัญชีได้

![](../.gitbook/assets/topup_2.png)

หลังจากชำระเงินให้ทำการอัพโหลดรูปสลิป

![](../.gitbook/assets/topup_3.png)

จากนั้นให้กดปุ่ม Pay

![](../.gitbook/assets/topup_4.png)

### **Tax invoice**

\(Optional\) คลิกที่ช่อง **"Request for payment receipt"** แล้วกรอกข้อมูลลงไปตามช่องว่าง

![](../.gitbook/assets/payment-ui-dev.nipa.cloud_payments_238ffb28f6524b7699b6-32.png)

และถ้าหากที่อยู่ที่ต้องการให้ส่ง Tax invoice ต่างกับข้อมูลที่กรอก ให้คลิกที่ช่อง **"Delivery address same as company address"** แล้วกรอกที่อยู่ที่ต้องการให้ส่ง Tax Invoice ลงไป

![](../.gitbook/assets/payment-ui-dev.nipa.cloud_payments_238ffb28f6524b7699b6-33.png)

คลิกที่ช่อง "**Agree to the payment refunds**" แล้วกดปุ่ม Comfirm เพื่อเข้าสู่ขั้นตอนการชำระเงิน ตามวิธีการชำระเงินที่ได้เลือกไว้

## Voucher

การเติมเงินผ่าน **Voucher** มีขั้นตอนดังนี้

1. ไปยังหน้า **Billing** แล้วใส่จำนวนเงินที่ต้องการเติมลงไปในเมนู **Voucher** หลังจากนั้นให้กดปุ่ม Apply

![](../.gitbook/assets/screenshot-from-2020-02-13-15-3.png)

1. หาก **Voucher** ถูกต้อง จะได้ระบบจะแจ้งดังภาพต่อไปนี้

![](../.gitbook/assets/fn-customer-portal-dev-nipacloud-dev-2-1.png)

