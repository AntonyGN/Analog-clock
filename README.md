# Analog Clock
This is a simple web page that displays an analog clock. The clock displays the current time in hours, minutes, and seconds, and updates itself in real-time. It also includes a switch that allows the user to switch between light and dark modes.

## Getting Started
To run the analog clock on your local machine, simply clone this repository and open the index.html file in your web browser.

```bash
git clone https://github.com/AntonyGN/Analog-clock.git
cd analog-clock
```

## Usage
You can customize the appearance of the clock by editing the CSS code in the style.css file. For example, you can change the colors, size, and position of the clock and its hands.

```bash
/* Example CSS code */
.container .clock {
  display: flex;
  height: 500px;
  width: 500px;
  border-radius: 50%;
  align-items: center;
  justify-content: center;
  background: #f6f7fb;
}
.hand.minute {
  height: 150px;
  width: 6px;
  background: #18191a;
}
```
You can also modify the JavaScript code in the script.js file to add new features or change the clock behavior.

```
/* Example JavaScript code */
function updateClock() {
  const now = new Date();
  const seconds = now.getSeconds();
  const minutes = now.getMinutes();
  const hours = now.getHours() % 12;
}
```

## License
This project is licensed under the MIT License
