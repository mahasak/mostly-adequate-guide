[![cover](images/cover.png)](SUMMARY.md)

## รายละเอียดเกี่ยวกับหนังสือ

หนังสือเล่มนี้เป็นหนังสือเกี่ยวกับการเขียนโปรแกรมแบบ functional programming ในมุมมองทั่วไป โดยในหนังสือจะใช้ภาษา JavaScript เป็นหลักการดำเนินเรื่อง บางคนอาจจะเห็นว่าเป็นตัวเลือกที่ไม่ดีนัก แต่อย่างไรก็ตามเราเชื่อว่านี่เป็นหนึ่งในทางเลือกที่เหมาะสมในการเรียนรู้ functional programming (FP) ด้วยเหตุผลต่างๆดังนี้:

 * **สามารถใช้ FP ในงานที่ต้องทำอยู่เป็นประจำได้**

    This makes it possible to practice and apply your acquired knowledge each day on real world programs rather than pet projects on nights and weekends in an esoteric FP language.


 * **ไม่จำเป็นต้องเริ่มต้นเรียนทุกสิ่งทุกอย่างใหม่หมด**

    In a pure functional language, you cannot log a variable or read a DOM node without using monads. Here we can cheat a little as we learn to purify our codebase. It's also easier to get started in this language since it's mixed paradigm and you can fall back on your current practices while there are gaps in your knowledge.


 * **JavaScript เป็นภาษาที่มีสนับสนุนในการเขียนโค้ดแบบ functional**

    We have all the features we need to mimic a language like Scala or Haskell with the help of a tiny library or two. Object-oriented programming currently dominates the industry, but it's clearly awkward in JavaScript. It's akin to camping off of a highway or tap dancing in galoshes. We have to `bind` all over the place lest `this` change out from under us, we don't have classes (yet), we have various work arounds for the quirky behavior when the `new` keyword is forgotten, private members are only available via closures. To a lot of us, FP feels more natural anyways.

That said, typed functional languages will, without a doubt, be the best place to code in the style presented by this book. JavaScript will be our means of learning a paradigm, where you apply it is up to you. Luckily, the interfaces are mathematical and, as such, ubiquitous. You'll find yourself at home with Swiftz, Scalaz, Haskell, PureScript, and other mathematically inclined environments.


## อ่านแบบออนไลน์

เพื่อให้ได้ความสะดวกในการอ่าน, [เราแนะนำให้อ่านจาก Gitbook](https://mostly-adequate.gitbooks.io/mostly-adequate-guide/).

- มี Sidebar ที่จะช่วยให้คุณสามารถเข้าถึงเนื้อหาได้สะดวก
- มีแบบทดสอบให้ทดลองทำออนไลน์
- มีตัวอย่างเชิงลึกให้ทำความเข้าใจ


## ดาวน์โหลดได้ที่นี่

* [ดาว์นโหลดไฟล์ PDF](https://www.gitbook.com/download/pdf/book/mostly-adequate/mostly-adequate-guide)
* [ดาว์นโหลดไฟล์ EPUB](https://www.gitbook.com/download/epub/book/mostly-adequate/mostly-adequate-guide)
* [ดาว์นโหลดไฟล์ Mobi (Kindle)](https://www.gitbook.com/download/mobi/book/mostly-adequate/mostly-adequate-guide)


## Do it yourself

```
git clone https://github.com/MostlyAdequate/mostly-adequate-guide.git
cd mostly-adequate-guide/
npm install
npm run setup
gitbook pdf
```


# Table of Contents

See [SUMMARY.md](SUMMARY.md)

### Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)

### Translations

See [TRANSLATIONS.md](TRANSLATIONS.md)

### FAQ

See [FAQ.md](FAQ.md)



# Plans for the future

* **Part 1** (chapters 1-7) is a guide to the basics. I'm updating as I find errors since this is the initial draft. Feel free to help!
* **Part 2** (chapters 8-10) will address type classes like functors and monads all the way through to traversable. I hope to squeeze in transformers and a pure application.
* **Part 3** (chapters 11+) will start to dance the fine line between practical programming and academic absurdity. We'll look at comonads, f-algebras, free monads, yoneda, and other categorical constructs.


---


<p align="center">
  <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
    <img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" />
  </a>
  <br />
  This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
</p>
