```markdown
# 🍽️ Lunch Picker Program

A simple JavaScript program to manage a dynamic lunch menu. Users can add, remove, view, and randomly select lunch items.

## 🧠 Features

- Add lunch items to the **start** or **end** of the menu
- Remove lunch items from the **start** or **end**
- Randomly pick a lunch item
- Display the full lunch menu
- Console logging for all actions

## 📁 File Structure

``

lunch-picker/
├── index.js      # Main script with lunch menu logic
├── README.md     # Project documentation

``

## 📦 Getting Started

### Requirements
- A browser console or Node.js environment

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/lunch-picker.git
   cd lunch-picker
``

2. Run the script:

   * Open `index.js` in a browser console or execute via Node:

     ```bash
     node index.js
     ```

## 🧪 Usage & Function Reference

### 1. `addLunchToEnd(array, lunchItem)`

Adds a lunch item to the end of the menu.

```js
addLunchToEnd(lunches, "Tacos");
// Logs: Tacos added to the end of the lunch menu.
``

---

### 2. `addLunchToStart(array, lunchItem)`

Adds a lunch item to the beginning of the menu.

```js
addLunchToStart(lunches, "Sushi");
// Logs: Sushi added to the start of the lunch menu.
``

---

### 3. `removeLastLunch(array)`

Removes the last item in the menu.

```js
removeLastLunch(lunches);
// Logs: [Item] removed from the end of the lunch menu.
``

---

### 4. `removeFirstLunch(array)`

Removes the first item in the menu.

```js
removeFirstLunch(lunches);
// Logs: [Item] removed from the start of the lunch menu.
``

---

### 5. `getRandomLunch(array)`

Randomly selects a lunch item.

```js
getRandomLunch(lunches);
// Logs: Randomly selected lunch: [Item]
``

---

### 6. `showLunchMenu(array)`

Displays all current lunch items.

```js
showLunchMenu(lunches);
// Logs: Menu items: Item1, Item2, Item3
``

---

## 🛠 Example

```js
let lunches = [];
addLunchToEnd(lunches, "Burger");
addLunchToStart(lunches, "Salad");
removeLastLunch(lunches);
getRandomLunch(lunches);
showLunchMenu(lunches);


## 📄 License

MIT License — feel free to use and modify.

---

Happy coding and bon appétit! 🍴

```

