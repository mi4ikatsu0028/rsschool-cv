Roman Murashov

Beginner Frontend Developer

Contacts:

Phone: +7 950 022 551

E-mail: mi4ikatsu0028@yandex.ru

Telegram-nickname: @mi4ikatsu028

Discord: @mi4ikatsu028

About me:

I'm a beggining Frontend Developer, my life before that course was not tied up with IT, but i really want to master a new major. I believe this course will give me a new skills to achive my goal

Skills:

HTML

CSS

JS

Git, GitHub

Photoshop, Figma

My first program:

```
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```
