#Typing Keyboard 

The keyboard reacts to real keyboard presses with animations and sound effects.
It also includes a random typing mode where keys are automatically pressed on the screen.

##  Technologies Used

* **HTML5** — Keyboard structure
* **CSS3** — Layout, colors, animations and styling
* **JavaScript** — Keyboard interactions and sound
* **Web Audio API** — Playing keyboard sounds
* **Feather Icons** — Keyboard icons

##  How It Works

When you press a key on your physical keyboard, JavaScript detects the `keydown` event and finds the corresponding virtual key.

The pressed key receives an active style:

```javascript
keyElement.classList.add('key--active');
```

When the key is released, the active style is removed:

```javascript
keyElement.classList.remove('key--active');
```

The project also uses the Web Audio API to play a keyboard sound whenever a key is pressed.

## Random Typing

The project contains a random typing feature that automatically selects and simulates different keys.

A random key is selected every **300 milliseconds**, creating an automatic typing effect.

```javascript
startTypingRandomly();
```

Screenshot:
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/7a692ed0-6a35-486b-9497-d6744a9124d8" />



Built as a creative HTML, CSS and JavaScript project.
