# PolyCortex
MVP for a Multi-LLLM Cognitive Co-Piot
# PolyCortex - Next-Gen AI Companion

PolyCortex is a next-generation, multimodal, privacy-first AI companion integrating multiple frontier LLMs via intelligent agent orchestration.

## Features

*   **Multimodal AI:** Supports text, image, voice, and video inputs.
*   **Privacy-First:** Offers comprehensive privacy controls, including data personalization, collection, third-party sharing, and retention period settings.
*   **Expert System:** Allows users to select from a range of AI experts, each specialized in different domains.
*   **LLM Orchestration:** Integrates multiple Large Language Models (LLMs) such as Claude and Gemini for intelligent response generation.

## Technologies Used

*   **React:** A JavaScript library for building user interfaces.
*   **TypeScript:** A typed superset of JavaScript that compiles to plain JavaScript.
*   **Vite:** A build tool that provides a fast and performant development experience.
*   **Tailwind CSS:** A utility-first CSS framework for rapidly designing custom user interfaces.
*   **Lucide React:** A library of beautiful, consistent icons.
*   **Google Generative AI:** Google's API for generative AI models.
*   **Anthropic:** Anthropic's API for the Claude LLM.

## Getting Started

1.  **Install Dependencies:**

    ```bash
    npm install
    ```

2.  **Configure API Keys:**

    *   Obtain API keys for Gemini and Claude.
    *   Create a `.env` file in the project root and add the following:

        ```
        VITE_GEMINI_API_KEY=<your_gemini_api_key>
        VITE_ANTHROPIC_API_KEY=<your_anthropic_api_key>
        ```

3.  **Run the Application:**

    ```bash
    npm run dev
    ```

    This will start the development server. Open your browser and navigate to `http://localhost:5173` to view the application.

## Privacy

PolyCortex is designed with privacy in mind. You can control your privacy settings in the Privacy Dashboard, including:

*   **Personalization:** Allow PolyCortex to remember your preferences.
*   **Data Collection:** Allow PolyCortex to collect data to improve services.
*   **Third-Party Sharing:** Allow PolyCortex to share anonymized data with third parties.
*   **Data Retention:** Choose how long PolyCortex should keep your conversation data.

You can also export or delete all your data at any time.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues to suggest improvements or report bugs.
