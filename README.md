# ASU Civil Sophomore Schedule

**Ain Shams University — Faculty of Engineering**  
**Academic Year 2025–2026**  
**Civil Engineering — Sophomore (Group 1)**

---

## Live Demo

*(أضف لينك GitHub Pages هنا بعد الرفع)*

---

## عن الموقع

موقع تفاعلي سينمائي يعرض جدول المحاضرات والتمارين والمعامل لطلاب السنة الثانية (Sophomore) بقسم الهندسة المدنية — كلية الهندسة جامعة عين شمس.

التجربة: شاشة مظلمة في البداية → سحب الحبل → الإضاءة تشتغل → الجدول يظهر.

الموقع **Time-Aware**: يعرف توقيت القاهرة، اليوم الحالي، والمحاضرة الجارية الآن.

---

## الأقسام المتاحة

| القسم   | الوصف التقريبي        |
|---------|------------------------|
| **1-CES** | Structural             |
| **1-CEP** | Surveying              |
| **1-CEI** | Water / Hydraulics     |

التبديل بين الأقسام من الأزرار في الهيدر.

---

## المميزات

- **تجربة تفاعلية**: سحب الحبل لتشغيل الإضاءة وكشف الجدول
- **ثلاثة أقسام منفصلة**: 1-CES · 1-CEP · 1-CEI
- **ساعة وتاريخ Live** بتوقيت القاهرة (`Africa/Cairo`) — نظام 24 ساعة
- **تمييز المحاضرة الحالية**: badge **LIVE** + glow خفيف على الحصة الجارية
- **تمييز اليوم الحالي**: قسم اليوم عليه pill **Today**
- **أسماء المواد كاملة** (مش أكواد فقط)
- **تصميم سينمائي**: خلفية داكنة، إضاءة دافئة، جزيئات غبار
- **متجاوب**: Desktop و Mobile
- **كل التحديثات Live** بدون Refresh

---

## المواد المعروضة

| الكود     | اسم المادة                                      |
|-----------|-------------------------------------------------|
| CEI211s   | Fluid Mechanics                                 |
| CEI212s   | Hydraulics                                      |
| CEI231s   | Civil Drawing                                   |
| CEI241s   | Engineering Hydrology                           |
| CEP211s   | Introduction to Plane Surveying                 |
| CES211s   | Structural Mechanics (1)                        |
| CES212s   | Structural Mechanics (2)                        |
| CES251s   | Structures and Properties of Construction Materials |
| PHM212s   | Differential Equations for Civil Engineering    |

---

## طريقة التشغيل

1. حمّل ملف `index.html`
2. افتحه في أي متصفح حديث (Chrome / Edge / Firefox / Safari)
3. اسحب الحبل أو اضغط **Turn On Light**
4. اختر القسم من الأزرار أعلى الصفحة

لا يحتاج سيرفر ولا تثبيت.

### النشر على GitHub Pages

1. أنشئ Repository جديد
2. ارفع `index.html` (و`README.md` اختياري)
3. من Settings → Pages → Source: Deploy from branch `main`
4. افتح اللينك الظاهر

---

## التقنيات

- HTML5 + CSS3
- React 18 (CDN)
- Babel Standalone
- Tailwind CSS (CDN)
- Google Fonts (Inter, Manrope, Cairo)
- `Intl` API لتوقيت `Africa/Cairo`

---

## المطور

**Abdelrahman Ashraf**  
Student Code: **2401727**  
Ain Shams University — Faculty of Engineering

---

## ملاحظات

- بعض الحصص **Biweekly** (كل أسبوعين)
- الجداول مبنية على الصفحة الأولى من الجدول الرسمي لسوفومور Group 1
- الساعة والمحاضرة الحالية تعتمد على توقيت القاهرة وليس جهاز المستخدم
'''
