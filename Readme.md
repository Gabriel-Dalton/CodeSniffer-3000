# CodeSniffer 3000 🕵️‍♂️

The **CodeSniffer 3000** is a powerful web-based tool designed to analyze a piece of code and estimate the likelihood that it was generated by an AI. This project is ideal for developers, educators, and anyone curious about distinguishing between AI-generated and human-written code.

![image](https://github.com/user-attachments/assets/7c2a7b4a-44b2-40bd-81b9-97b9981c7da0)



## Features

- **Code Analysis**: Analyzes code based on several criteria to determine whether it is likely AI-generated or human-written.
- **Clear Feedback**: Provides detailed feedback on the specific characteristics found in the code, such as formatting consistency, variable naming conventions, and more.
- **User-Friendly Interface**: Simple and intuitive interface built with Tailwind CSS, allowing users to easily paste their code and get results.
- **Customizable**: Easily modify the analysis criteria to suit different programming languages or coding styles.

## How It Works

The CodeSniffer 3000 evaluates the pasted code against a set of predefined criteria that are commonly associated with AI-generated or human-written code. Each criterion contributes to a score that determines the likelihood of AI generation.

### Criteria Evaluated

1. **Consistent Formatting**: Checks for uniform indentation and formatting, which is often a trait of AI-generated code.
2. **Generic Variable Names**: Identifies the use of common, non-specific variable names like `data`, `result`, or `input`.
3. **Lack of Comments**: Detects the absence of comments, which is more common in AI-generated code.
4. **Repetitive Patterns**: Looks for repetitive code structures that are typical in AI-generated scripts.
5. **Overly Structured Patterns**: Flags repeated and overly structured logic, such as multiple `if-else` statements or loops.
6. **Code Complexity**: Considers the complexity of the code, with simpler code often indicating AI generation.

## Getting Started

### Prerequisites

- A modern web browser
- Basic understanding of HTML, CSS, and JavaScript

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/codesniffer-3000.git
   cd codesniffer-3000
   ```

2. Open `index.html` in your web browser.

### Usage

1. Paste the code you want to analyze into the text area.
2. Click the "Analyze Code" button.
3. Review the analysis results, including the estimated likelihood of AI generation and detailed feedback.

### Example

```javascript
// Function to generate a random number within a given range
function getRandomNumber(min, max) {
    return Math.floor(Math.random() * (max - min + 1)) + min;
}
```

Paste the above code into the tool to see how it works.

## Customization

The CodeSniffer 3000's criteria can be customized by editing the JavaScript functions in `aiCodeDetector.js`. For example, you can add new checks or adjust the scoring for existing ones to better suit your needs.

## Contributing

Contributions are welcome! If you have ideas for improving this project or find a bug, feel free to open an issue or submit a pull request.

### To Do:

- [ ] Expand the criteria list for different programming languages.
- [ ] Improve the accuracy of AI detection.
- [ ] Add support for analyzing multiple files at once.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Acknowledgements

- [Tailwind CSS](https://tailwindcss.com/) - For the beautiful and responsive design framework.
- [OpenAI](https://openai.com/) - For inspiring this project.
