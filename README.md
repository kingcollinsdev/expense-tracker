# Project Name

This project consists of a expense tracker that can track your income and expenses and calculates the balances of both.


## Screenshots

![<img width="1920" height="1127" alt="screencapture-expense-tracker-three-eosin-83-vercel-app-2026-04-28-13_00_21" src="https://github.com/user-attachments/assets/6dff73b9-0689-4573-a242-b05853bd0546" />
]()


## Features

- Feature 1: A user can upload their expenses and incomes.
- Feature 2: The application can calculate the sum of both to create a standard balance after the calculations.
- Feature 3: The user can remove any inputs and all of the data is stored on the localStorage.
- Responsive design
- Cross-browser compatible

## Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling and layout
- **JavaScript** - Interactivity and functionality

## Installation

1. Clone the repository:
```bash
git@github.com:kingcollinsdev/expense-tracker.git
```

2. Navigate to the project directory:
```bash
cd expense-tracker
```

3. Open `index.html` in your browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

## Usage

Format the currencies of the amount being input to be universally USD($).

```javascript
// Example code snippet
function formatCurrency(number) {
    return new Intl.NumberFormat("en-US", {
        style: "currency",
        currency: "USD",
    }).format(number);
}
});
```

## Project Structure

```
project-name/
│
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── script.js       # Main JavaScript file
├── images/             # Image assets
└── README.md           # Project documentation
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)


## Contact

Your Name - Collins Wachira Ndegwa - collinswachira2004@gmail.com

Project Link: [https://github.com/your-username/project-name](https://github.com/your-username/project-name)

## Acknowledgments

- Inspiration or resources you used
- Libraries or tools that helped
- People who contributed or inspired the project
