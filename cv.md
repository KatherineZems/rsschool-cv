# Ekaterina Zemskova

Junior Frontend Developer

## Contacts

- Phone: +7 (995) 540-72-93
- E-mail: zems.ekaterina@gmail.com
- GitHub: [KatherineZems](https://github.com/KatherineZems)
- Location: Russia, Ryazan

## About Me

I have been studying layout and programming (HTML, CSS, JavaScript) for about a year.
During this time, my portfolio has been replenished with several works, some of which
are presented on Github. For example, my personal site, which features a few simple
JavaScript games, a password generator and my achievements, also has a Caesar code
cipher-decryptor program, and other sites. I set most of the tasks myself, but there
is also a project that I did for a Ryazan company (product catalog and documentation).

## Skills

- HTML, CSS (SASS)
- JavaScript (Basic)
- Git, GitHub
- Figma, Adobe Photoshop

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

## Experience

[My portfolio](https://katherinezems.github.io/my-portfolio/)

## Education

- University: Ryazan State Radio Engineering University
  (Department of Information Technologies in Graphics and Design)
- Courses:
  - [HTML Academy](https://htmlacademy.ru/courses)
  - [RS Schools Course «JavaScript/Front-end»](https://rs.school/index.html)
  - JS, CSS, HTML, Git video courses on YouTube

## Languages

- Russian (native)
- English (A2)
