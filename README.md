# Online Shop Automation System
یک سیستم اتوماسیون سفارش، مشتری، و تحلیل فروش برای فروشگاه‌های اینستاگرامی و تلگرامی  
با تمرکز بر ساختاردهی، گزارش‌گیری، و ساده‌سازی فرآیند فروش آنلاین و حضوری

---

##  معرفی پروژه
در مدل فعلی فروشگاه‌های آنلاین محلی که در شبکه‌های اجتماعی فعالیت می‌کنند، مشکلات متعددی از جمله بی‌نظمی در ثبت سفارش، نبود داشبورد تحلیلی، و عدم پیگیری دقیق مشتری دیده می‌شود. این پروژه با هدف رفع این گلوگاه‌ها طراحی شده است.
 هدف : تبدیل فروشگاه دستی به یک سیستم ساختارمند، تحلیلی، و خودکار

---

##  امکانات کلیدی
- ثبت سفارش از طریق ربات تلگرام یا واتساپ با کد محصول
- تأیید دستی یا نیمه‌خودکار پرداخت‌ها
- مدیریت مشتری فقط با شماره تلفن
- سیستم کش‌بک (وفاداری) خودکار برای مشتریان
- داشبورد تحلیلی فروش (پرفروش‌ترین‌ها، میانگین سفارش، درآمد کل)
- سیستم سبد خرید QR برای فروش حضوری با کاهش موجودی لحظه‌ای
- خروجی‌گیری از اطلاعات برای آرشیو یا استفاده آفلاین

---

##  ساختار پایگاه داده (PostgreSQL)
شامل جداول:
- `customers`
- `products`
- `orders`, `order_items`
- `cashback_logs`
- `cart_items`
- `feedback`
- `product_stats`

---
