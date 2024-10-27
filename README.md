# Markdown Picture Test

The image below should show a black image with white text if dark mode is the preferred colorscheme.
Else it should show a black text with a white background.

<picture>
    <source media="(prefers-color-scheme: dark)" srcset="./dark.png">
    <img src="./light.png" alt="Testpicture" />
</picture>