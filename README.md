# 🚗 Car License Eligibility Checker

## 📌 About
This JavaScript script checks whether individuals meet the minimum age requirement to obtain a car license and logs the results to the console.

## 📂 Project Structure
- `script.js` - Contains the logic for checking license eligibility.

## 📝 Code
```javascript
const jonasAge = 31;
const annaAge = 28;
const lucasAge = 16;
const ageForLicense = 18;

if (jonasAge >= ageForLicense) {
  console.log('Jonas is able to get car license');
} else {
  console.log('Jonas is not able to get car license');
}

if (annaAge >= ageForLicense) {
  console.log('Anna is able to get car license');
} else {
  console.log('Anna is not able to get car license');
}

if (lucasAge >= ageForLicense) {
  console.log('Lucas is able to get car license');
} else {
  console.log('Lucas is not able to get car license');
}
```

## 🚀 Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. Navigate to the project folder:
   ```sh
   cd your-repo-name
   ```
3. Run the script using Node.js:
   ```sh
   node script.js
   ```

## 🔥 Output Example
```
Jonas is able to get car license
Anna is able to get car license
Lucas is not able to get car license
```

## 💡 Features
- Checks if individuals meet the required age for a driving license
- Uses conditional statements to determine eligibility
- Outputs the results dynamically

## 👨‍💻 Author
**Goga Gabelia** - Software Developer

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
