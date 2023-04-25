# Fylo-tailwindCSS

Install dependencies

```
npm install
```
```
npm run watch
```
Copy the script and add it into your html file or find code on the website [www.freecodecamp.org](https://www.freecodecamp.org/news/how-to-build-a-dark-mode-switcher-with-tailwind-css-and-flowbite)
```
    <script>
      if (
        localStorage.getItem('color-theme') === 'dark' ||
        (!('color-theme' in localStorage) &&
          window.matchMedia('(prefers-color-scheme: dark)').matches)
      ) {
        document.documentElement.classList.add('dark')
      } else {
        document.documentElement.classList.remove('dark')
      }
    </script>
```
[View the Website](https://hannafleming.github.io/Fylo-tailwindCSS/)

![127 0 0 1_5500_index html](https://user-images.githubusercontent.com/124400864/234415849-a8c94e64-c2cc-4e38-a524-b664b2b0741a.png)
