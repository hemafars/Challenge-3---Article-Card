تمام يا نجم 🔥 نبدأ **CSS Mastery — Challenge 3**

# 🎯 Challenge 3 — Article Card

**الصعوبة:** ⭐⭐
**الهدف:** التحكم في النصوص، المسافات، الحدود، والـ pseudo-elements.

## 📝 فكرة المشروع

أنشئ بطاقة مقال لموقع تقني:

```text
┌──────────────────────────┐
│       Article Image      │
├──────────────────────────┤
│ TECHNOLOGY               │
│                          │
│ How to Become a          │
│ Front-End Developer      │
│                          │
│ Learn HTML, CSS and      │
│ JavaScript step by step. │
│                          │
│ Ahmed Fars • 5 min read  │
│                          │
│ Read More →              │
└──────────────────────────┘
```

## 🧱 المحتوى

استخدم:

- صورة
- `span` للتصنيف
- `h2` للعنوان
- `p` للوصف
- `small` لمعلومات الكاتب
- رابط `Read More`

---

## 🎨 CSS المطلوب

### 1. البطاقة

استخدم:

- `width`
- `max-width`
- `padding`
- `margin`
- `border`
- `border-radius`
- `box-shadow`

### 2. النص

طبّق:

- `font-family`
- `font-size`
- `font-weight`
- `line-height`
- `letter-spacing`

واجعل العنوان لا يلتصق بالوصف.

### 3. الصورة

اجعلها:

- بعرض البطاقة.
- بارتفاع مناسب.
- لا تتشوه باستخدام `object-fit`.

---

## 🔥 Pseudo-classes

عند عمل Hover على البطاقة:

```text
Card
 ↓
ارتفاع بسيط
Shadow أقوى
```

وعند Hover على:

```text
Read More →
```

يتغير شكله.

استخدم:

```css
:hover;
```

و:

```css
transition
transform
```

---

## 🧠 تحدي إضافي

أضف علامة صغيرة قبل اسم التصنيف:

```text
● TECHNOLOGY
```

لكن **ممنوع إضافة عنصر HTML جديد لهذه النقطة**.

استخدم:

```css
::before;
```

وهنا تبدأ أول مرة في استخدام **Pseudo-elements**.

---

## ⚠️ الشروط

❌ لا Bootstrap
❌ لا JavaScript
❌ لا `position: absolute`
❌ لا `!important`

✅ CSS فقط
✅ HTML + CSS
✅ استخدم `::before` للـ Bonus

### 🏆 التقييم

عندما ترسل الكود سأقيمه من **100**، مع التركيز خصوصًا على **جودة الـ CSS وليس مجرد أن التصميم يعمل**.
