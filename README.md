# 📄 Markdown Cheat Sheet (สำหรับ Dev Note)

> สำหรับใช้บน GitHub หรือจดความรู้ในไฟล์ .md แบบมือโปร

---

## 🧠 พื้นฐาน Markdown

| ประเภท | ตัวอย่าง |
|--------|----------|
| 📌 หัวข้อใหญ่ | `# หัวข้อ` |
| 📌 หัวข้อย่อย | `## หัวข้อย่อย`, `### หัวข้อรอง` |
| 📋 Bullet list | `- รายการ` หรือ `* รายการ` |
| 🔢 Numbered list | `1. รายการ` |
| ✅ Checklist | `- [x] ทำแล้ว` / `- [ ] ยังไม่ทำ` |
| 💬 Blockquote | `> ข้อความอธิบาย` |
| 💻 Inline Code | \`code\` |
| 💻 Code block หลายบรรทัด | \```js\nconsole.log("Hello");\n\``` |
| 🖼️ แทรกรูปภาพ | `![คำอธิบาย](path/to/image.png)` |
| 🔗 ลิงก์ | `[ลิงก์](https://example.com)` |
| ➕ เน้นตัวอักษร | `**ตัวหนา**`, `*ตัวเอียง*`, `***หนาเอียง***` |
| 📎 เส้นคั่น | `---` |

---

## 🧪 ตัวอย่าง Code Block

### JavaScript

```js
const greet = (name) => `Hello, ${name}`;
```

### C# Razor

```csharp
@foreach (var item in Model.Children()) {
    <p>@item.Name</p>
}
```

### Bash

```bash
npm install
dotnet run
```

---

## 📋 Checklist ตัวอย่าง

- [x] เข้าใจ Markdown
- [x] ใช้ได้ใน GitHub / Notion / VSCode
- [ ] ลองเขียน Dev Note ของตัวเอง

---

## 🧠 สรุป

Markdown คือภาษาที่ง่ายแต่ทรงพลัง เหมาะกับ Dev ทุกคนที่อยากจดความรู้ให้เป็นระบบ ใช้กับ GitHub, README.md, หรือโน้ตส่วนตัวได้อย่างดีเยี่ยม
