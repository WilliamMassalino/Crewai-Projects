# AI News Generator

Welcome to the AI News Generator, a web application that leverages AI agents to generate comprehensive blog posts on any topic. This application is powered by CrewAI and Gemini, and is built using Streamlit.

## Features

- **Content Planning**: The application uses AI agents to plan engaging and factually accurate content.
- **Content Writing**: AI agents write insightful and factually accurate opinion pieces.
- **Content Editing**: AI agents edit the content to align with journalistic best practices and the organization's writing style.
- **Customizable Settings**: Users can adjust the temperature for creativity and input their desired topic.
- **Downloadable Content**: Generated content can be downloaded as a markdown file.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/WilliamMassalino/Crewai-Projects.git
   cd Crewai-Projects/Research_Agent
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add your Gemini and Serper API key:
     ```
     SERPER_API_KEY=your_serper_api_key_here
     GEMINI_API_KEY=your_gemini_api_key_here
     ```

## Usage

1. Run the application:
   ```bash
   streamlit run app.py
   ```

2. Open your web browser and navigate to the local server address provided by Streamlit.

3. Enter your desired topic in the text area on the sidebar.

4. Adjust the temperature slider if needed (higher values result in more creative content).

5. Click the "Generate Content" button to start the content generation process.

6. Once the content is generated, you can view it on the main page and download it as a markdown file.

## How It Works

The application uses a series of AI agents to generate content:

- **Content Planner**: Plans the content by prioritizing trends, identifying the target audience, and developing a content outline.
- **Content Writer**: Crafts a blog post based on the content plan, incorporating SEO keywords and ensuring the content is engaging and well-structured.
- **Editor**: Reviews the blog post to ensure it aligns with the brand's voice and journalistic standards.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Built with [CrewAI](https://crewai.com) and [Streamlit](https://streamlit.io)
- Powered by [Gemini](https://gemini.com)
