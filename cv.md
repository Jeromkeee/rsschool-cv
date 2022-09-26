# Dmitry Petrenko

## Contacts:
- Phone: +995595035979
- E-mail: altcreaw@gmail.com
- Discord: Jeromkeee#5657
- Vk.com: [profile](https://vk.com/kotletkyspureshkoy)

---

### About me:
Hi! I'm an engineer in an old design bureau located in Saint-Petersburg. Seeing the limitations of career that I've chosen, I decided to master new craft (typical switcher hehe).

---

## My code
This is the part of my previous project 2048. Function takes array of 4 cell values, adds and shifts numbers to the right and returns array.

``` javascript
function act(arg) {
    let arr = []
    let sum = true
    arg.forEach(el => {
      if (el !== '') {
        if (arr[arr.length - 1] == el && sum == true) {
          arr.splice(arr.length - 1, 1, 2 * el)
          arr.unshift('')
          sum = false
        } else {
          arr.push(el)
          sum = true
        }
      } else {
        arr.unshift('')
      }
    })
      return arr
}
```

## Education
- SPb SUACE* 2012-2016 Bachelor's degree "Engineering systems in construction"
- SPb SUACE* 2016-2019 Master's degree "Water and sanitation"
- RS-School 2021-now

*Saint-Petersburg State University of Architecture and Civil Engineering

---

## Not native languages
- English B1. Studying by myself.
- Swedish A2. Attended evening courses and group classes.