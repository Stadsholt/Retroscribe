# Retroscribe: Rewriting Classic Literature Into Contemporary Language

### 7th-Semester Project · Aalborg University

**Retroscribe** is an AI-powered rewriting tool that takes classic literature and adapts its language to suit modern readers. Born out of a user-centred design project targeting 17–22 year-olds, Retroscribe makes older texts more engaging without altering their plots.

Classic books often feature dense, outdated language that makes them difficult to read and relate to, especially for younger audiences. Retroscribe aims to remove that barrier by translating the style of these works into more relatable, modern forms—ranging from casual slang to formal modern English.

**How does it work?**

Retroscribe is built with Python and powered by OpenAI’s GPT-3.5 Turbo model, wrapped in an intuitive Gradio interface. The process is as follows:

1. **Text Extraction**  
   Upload a PDF or type in text manually. The app uses PyMuPDF to extract and clean the content.

2. **Language Processing**  
   The text is processed through GPT with a prompt tailored to the selected formality level: _Slang, Informal, Semi-formal, or Formal_.

3. **PDF Generation**  
   The rewritten text is formatted into a styled PDF output for download.

4. **Interface Interaction**  
   Users interact through a simple Gradio web interface that accepts input, allows formality selection, and returns the result.

## Retroscribe Mock-Up Interface:

Alongside the coding prototype, we also designed a Figma mock-up of the application. To create realistic examples in the interface, we used rewritten output from the Python script and pasted them into the UI screens. These were based on real excerpts, rephrased by the AI.

**Home Screen**

Allows quick access to your current book and library. Upload new books and start reading instantly.

<img src="https://github.com/user-attachments/assets/06017a1c-3151-40cb-90f3-13677b6a5543" width="300"/>

**Reading Interface**  
Read your rewritten text in a distraction-free format. Use a slider to compare with the original and offer feedback on phrasing.

<img src="https://github.com/user-attachments/assets/83e5994e-4ee4-4363-8471-041d352624ab" width="300"/>

## Tech Stack

- Python
- Gradio
- OpenAI (GPT-3.5 Turbo)
- LangChain
- PyMuPDF (`fitz`)
- Figma (UI Design)
