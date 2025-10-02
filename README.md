This converter implements the traditional Roman numeral system using a greedy algorithm approach. Users can input any number between 1 and 3999 and instantly receive the corresponding Roman numeral representation. The application includes comprehensive input validation to ensure only valid numbers are processed, with clear error messages guiding the user when invalid inputs are detected.
The interface combines functionality with aesthetics, featuring a clean, centered design overlaid on a subtle Colosseum background image that evokes the historical context of Roman numerals without compromising readability.
Features

Converts numbers from 1 to 3999 to Roman numerals
Real-time input validation with descriptive error messages
Responsive design compatible with mobile and desktop devices
Keyboard support (Enter key to convert)
Classical Roman-inspired visual design
Background image of the Colosseum for thematic context

Technologies Used

HTML5
CSS3 (Flexbox, gradients, transitions)
Vanilla JavaScript (ES6+)
Google Fonts (optional)

Installation
bash# Clone the repository
git clone https://github.com/your-username/roman-numeral-converter.git

# Navigate to the project directory
cd roman-numeral-converter

# Open index.html in your browser
open index.html
Usage

Enter a number between 1 and 3999 in the input field
Click the "CONVERTIR" button or press Enter
The Roman numeral equivalent will be displayed below

Empty input: "Please enter a valid number"
Numbers less than 1: "Please enter a number greater than or equal to 1"
Numbers 4000 or greater: "Please enter a number less than or equal to 3999"

Algorithm
The converter uses a greedy algorithm based on a lookup table of Roman numeral values in descending order:
M (1000), CM (900), D (500), CD (400), C (100), XC (90),
L (50), XL (40), X (10), IX (9), V (5), IV (4), I (1)
The algorithm iteratively subtracts the largest possible value and appends the corresponding Roman numeral until the input number reaches zero.


Project Structure
roman-numeral-converter/

├── index.html      # HTML structure

├── styles.css      # Styling and layout

├── script.js       # Conversion logic and validation

└── README.md       # Project documentation
Customization
Colors and styling can be modified in styles.css

Contributions are welcome.



