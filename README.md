I try to develop 2 machine learning models by following example via public internet
- Association Rule
-   โดยการนำ data เกี่ยวกับร้านเบเกอรี่ จาก kaggle มาศึกษา โดยการหาความสัมพันธ์ของสินค้า เพื่อเพิ่มโอกาสในการเพิ่มยอดขายที่ลูกค้าจะซื้อสินค้าอื่นๆเพิ่มขึ้น
-   จาก result ที่ได้ จะเห็นว่า  model แนะนำว่า สินค้าที่ควรจะมาขายคู่กับกาแฟ เพื่อเพิ่มยอดขาย 3 อันดับแรก ได้แก่ Toast, Spanish Brunch และ medialuna
- Predictive model
-   โดยการนำ data เกี่ยวกับลูกค้าที่ซื้อสินค้าใน supermarket จาก kaggle มาศึกษา โดยการทำ classification model เพื่อศึกษาว่าลูกค้าคนไหนมีโอกาสตอบรับ campaign โดยได้นำ xgboost algorithm มาใช้ develop model
-    จาก result ที่ได้ จะเห็นว่า  model มีทั้งหมด 5 ตัวแปรที่มีผลต่อการทำนาย ได้แก่ response, recency, frequency, monetary, AOU and ticket_size ซึ่ง Model ที่ได้มีค่า accuracy (GINI) อยู่ที่ 0.6955 สำหรับ Train Data และ 0.4291 สำหรับ Test Data

thanks to รุ่นพี่จาก credit risk community ที่ช่วยให้คำปรึกษา

Note: ยังมีหลายส่วนที่ผมยังไม่เข้าใจ และต้องศึกษาเพิ่มเติม
