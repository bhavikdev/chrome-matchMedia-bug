# About

This repo contains a single `index.html` file to show the bug that we have in Google Chrome for `matchMedia`. When you have a window width, let say **_960_**, it does return true for **_959.99_** and **_960.01_**. this will create a problem when you are checking specific size using `@screen`. If you test **_959.98_** or **_960.02_**, chrome returns value as expected.

# Instruction to reproduce bug in Google Chrome`

1. Clone Repo
2. serve index.html 
3. Please open dev tool (F12)
4. Make Device toolbar visible using toggle Devide Toolbar icon (for ,  ⌘ ⇧ M)
5. Set window to responsive with width=960
6. Reload the page

To check difference, load the same page in Firefox.


## License

MIT


