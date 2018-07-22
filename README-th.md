[![cover](images/cover.png)](SUMMARY.md)

## รายละเอียดเกี่ยวกับหนังสือ

หนังสือเล่มนี้เป็นหนังสือแนะนำการเขียนโปรแกรมแบบ functional programming โดยในหนังสือจะใช้ภาษา JavaScript เป็นหลักในการแนะนำ ซึ่งหลายคนอาจจะเห็นว่าเป็นตัวเลือกที่ไม่ดีนัก แต่อย่างไรก็ตามเราเชื่อว่า JavaScript เป็นหนึ่งในทางเลือกที่เหมาะสมในการเรียนรู้ functional programming (FP) ด้วยเหตุผลต่างๆดังนี้:

 * **เราสามารถใช้ FP ในงานที่ทำอยู่เป็นประจำได้**

    การที่เราสามารถนำเอาความรู้ที่ได้จากศึกษาไปใช้กับงานจริงๆนั้น ส่งผลดีมากกว่าการทำโครงการเล็กๆ


 * **ไม่จำเป็นต้องเริ่มต้นเรียนทุกสิ่งทุกอย่างใหม่หมด**

    ในภาษาแบบ pure functional นั้นเป็นการยากที่เราจะ log ค่าตัวแปร หรืออ่าน DOM โดยไม่ต้องใช้ monads แต่ด่วย JavaScript เราสามารถแอบโกงเล็กๆ ด้วยการผสม imperative method เข้าไปเมื่อเรายังมีความรู้ไม่พอในการทำบางอย่างด้วยแนวคิดแบบ functional


 * **JavaScript เป็นภาษาที่เหมาะสมกับการเขียนโค้ดแบบ functional**

    ในขณะที่การเขียนโปรแกรมเชิงวัตถุกำลังเป็นที่นิยมเป็นอย่างมาก เมื่อเรานำเอาเทคนิคเดียวกันมาใช้กับ JavaScript เรากลับพบว่ามันกลายเป็นเรื่องที่น่าประหลาดใจมากที่ มันทำให้เราต้องเขียน code ที่ดูแปลกประหลาด เช่น เราต้อง bind ทุกครั้งที่มีการใช้งาน this เพราะ scope ของ this ใน JavaScript นั้นไม่เหมือนกับภาษาอื่นๆ JavaScript (ยัง)ไม่มีคลาส ซึ่งเมื่อได้เปรียบเทียบกับการเขียนด้วย Functional Programming แล้วเรากลับพบว่าเราสามารถเขียนได้อย่างเป็นธรรมชาติกว่ามาก

ในหนังสือเล่มนี้จะใช้ JavaScript ในการอธิบายถึงแนวคิดในการเขียนโปรแกรมแบบ functional ซึ่งเมื่อผู้อ่านนำเอาแนวคิดที่ได้ไปใช้กับภาษาอื่นๆ เช่ร Swiftz, Scalaz, Haskell, Purescript และภาษาอื่นๆที่ใช้คณิตศาสตร์เป็นแนวคิดจะพบว่าสามารถเขียนโปรแกรมแบบ functional กับภาษาเหล่านั้นได้อย่างกลมกลืน


## อ่านแบบออนไลน์

เพื่อให้ได้อรรถรสในการอ่าน, [เราแนะนำให้อ่านจาก Gitbook](https://mostly-adequate.gitbooks.io/mostly-adequate-guide/).

- Gitbook มี Sidebar ที่จะช่วยให้คุณสามารถเข้าถึงเนื้อหาได้สะดวก
- เรามีแบบทดสอบให้ทดลองทำออนไลน์ได้ทันที
- มีตัวอย่างเชิงลึกให้ทำความเข้าใจตามได้ทันที


## ดาวน์โหลดได้ที่นี่

* [ดาว์นโหลดไฟล์ PDF](https://www.gitbook.com/download/pdf/book/mostly-adequate/mostly-adequate-guide)
* [ดาว์นโหลดไฟล์ EPUB](https://www.gitbook.com/download/epub/book/mostly-adequate/mostly-adequate-guide)
* [ดาว์นโหลดไฟล์ Mobi (Kindle)](https://www.gitbook.com/download/mobi/book/mostly-adequate/mostly-adequate-guide)


## สร้างไฟล์หนังสือด้วยตัวเอง

```
git clone https://github.com/MostlyAdequate/mostly-adequate-guide.git
cd mostly-adequate-guide/
npm install
npm run setup
gitbook pdf
```


# สารบัญ

ดู [SUMMARY.md](SUMMARY.md)

### Contributing

ดู [CONTRIBUTING.md](CONTRIBUTING.md)

### Translations

ดู [TRANSLATIONS.md](TRANSLATIONS.md)

### FAQ

ดู [FAQ.md](FAQ.md)



# แผนงานในอนาคต

* **Part 1** (บทที่ 1-7) เป็นเนื้อหาขั้นต้นซึ่งทางผู้เขียนจะมีกรปรับปรุงเนื้อหาเมื่อพบข้อผิดพลาดเสมอ ถ้าพบข้อผิดพลาด โปรดแจ้งได้ทันที
* **Part 2** (บทที่ 8-10) จะเป็นการลงรายละเอียดเกี่ยวกับ functor และ monad รวมไปถึง transformers และ pure application
* **Part 3** (บทที่ 11+) จะเริ่มอธิบายถึงความแตกต่างระหว่างการเขียนโปรแกรมในมุมของการใช้งานทั่วไป และการใช้งานในเชิงวิชาการ ซึ่งจะมองไปจนถึง comonads, f-algebras, free monads, yoneda, และส่วนอื่นๆ


---


<p align="center">
  <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
    <img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" />
  </a>
  <br />
  งานเขียนชิ้นนี้ถูกคุ้มครองภายใต้ลิขสิทธิ์แบบ <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
</p>
