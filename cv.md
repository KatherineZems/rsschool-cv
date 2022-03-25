# Ekaterina Zemskova

Junior Frontend Developer

---

## Contacts

Phone: +7 (995) 540-72-93
E-mail: zems.ekaterina@gmail.com
GitHub: [KatherineZems](https://github.com/KatherineZems)
Location: Russia, Ryazan

---

## About Me

I have been studying layout and programming (HTML, CSS, JavaScript) for about a year.
During this time, my portfolio has been replenished with several works, some of which
are presented on Github. For example, my personal site, which features a few simple
JavaScript games, a password generator and my achievements, also has a Caesar code
cipher-decryptor program, and other sites. I set most of the tasks myself, but there
is also a project that I did for a Ryazan company (product catalog and documentation).

---

## Skills

- HTML, CSS (SASS)
- JavaScript (Basic)
- Git, GitHub
- Figma, Adobe Photoshop

---

## Code Example

```
generatorForm.addEventListener('submit', e => {
  e.preventDefault()
  const data = new FormData(e.target)
  const lengthPassword = data.get('lengthPassword')
  let password = ""
  for(let i = 0; i < lengthPassword; i++){
      const n = getRandomNumber(letters.length - 1)
      password += letters[n]
  }
  write(password, "password")
})
```

---

## Experience

[My portfolio](https://katherinezems.github.io/my-portfolio/)

---
