# Devoxx Genie 

<img height="128" src="src/main/resources/META-INF/pluginIcon.svg" width="128"/>

DevoxxGenie is a plugin for IntelliJ IDEA that uses local LLM's (Ollama, LMStudio and GPT4All) to help review, test, explain your project code.

### Key Features:

- **Generate**: Generate code using local LLM's.
- **Review**: Review your code using local LLM's.
- **Test**: Test your code using local LLM's.
- Plugin is developed completely in Java, so easy to maintain and extend.
 
### Installation:

- **From IntelliJ IDEA**: Go to `Settings` -> `Plugins` -> `Marketplace` -> Install Plugin from Disk
- **From Source Code**: Clone the repository, build the plugin using `./gradlew shadowJar`, and install the plugin from the `build/libs` directory and select file 'DevoxxGenie-0.0.1.jar'

### Usage:
1) Select an LLM provider from the DevoxxGenie panel (right corner)
2) Select some code 
4) Enter shortcode command review, explain, generate unit tests of the selected code or enter a custom prompt.

Enjoy! 
