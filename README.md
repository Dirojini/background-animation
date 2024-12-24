# LED Multi-Color Background Animation

A vibrant LED multi-color background animation created using HTML and CSS. This design can be used to create eye-catching static pages, landing pages, or UI sections with dynamic, glowing effects.
##Demo Screenshort
![backgroundani](https://github.com/Dirojini/background-animation/blob/72532a73947b33d507adcfed09becde3a2af9dbf/Screenshot%202024-12-24%20123625.png)
## Features

- **Multi-Color Gradient Animation**
- **Customizable Speed and Colors**: Easily adjust the colors and animation duration.
- **Lightweight**: Pure HTML and CSS with no dependencies.

## Technologies Used

- **HTML** – For the structure of the page.
- **CSS** – For the animation and styling.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Dirojini/background-animation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd background-animation
   ```
3. Open the `index.html` file in your web browser.

## File Structure

```
led-background-animation/
│
├── index.html       # Main HTML file
└── style.css        # CSS for LED background animation
```

## Sample LED Background Animation (style.css)

```css
body {
  margin: 0;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background: linear-gradient(45deg, #ff0000, #ff7300, #ffeb00, #47ff00, #00ffee, #2b65ff, #8000ff);
  background-size: 400% 400%;
  animation: gradientBG 10s ease infinite;
}

@keyframes gradientBG {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}
```


## Future Enhancements

- **Customizable Color Palettes**
- **Interactive Click Effects**
- **JavaScript Integration for Dynamic Speed Control**
- **Text or Logo Overlay**

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

