# Chrome Gemini Nano Demo

This is a simple demo showcasing the new `window.ai` API in Chrome Canary, which exposes the Gemini Nano language model to JavaScript applications. This differs from other language models in that it runs on-device, rather than in the cloud. It opens up the possibility of making cost-free (for the developer) AI-enabled web apps.

## Prerequisites

-   Chrome Canary version 135 or above

## Installation

1.  Download Chrome Canary from the official website: [Download Canary](https://www.google.com/chrome/canary/?)
2.  Open `chrome://flags/` in Chrome Canary.
3.  Enable the **Prompt API for Gemini Nano** flag.
4.  Visit the demo site at [https://rmccrear.github.io/chrome-gemini-nano-test/](https://rmccrear.github.io/chrome-gemini-nano-test/) or clone this repository:

    ```bash
    git clone https://github.com/rmccrear/chrome-gemini-nano-test.git
    ```

5.  Open `index.html` in Chrome Canary.

## Usage

1.  Enter your question in the input field.
2.  Click the "Submit" button.
3.  The answer generated by the Gemini Nano model will be displayed below the input field.

## Note

-   The first time you run the demo, it may take a minute to load the language model.
-   This is the finalized `window.ai` API may change and break this page. Be warned!
