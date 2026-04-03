# AOCMS
AI-Oriented Corpus Management System (AOCMS)

Status: Work In Progress (WIP) / Research & Development
Proposed by: ぼちぴ (Bochipi)
Date: April 4, 2026

Declaration
In an era where AI determines the "truth" of information, the systematization of knowledge is indispensable. This project aims to construct a multi-layered knowledge base designed for AI agents to accurately interpret the context and definitions of information.
I am currently experimenting with "AI-Native Corpus Construction," integrating schema designs for glossaries, corpus dictionaries, bidirectional linking between articles and terms, concept mapping, and implementation of llms.txt.

Problems Solved
Prevention of AI Hallucinations: Minimizing errors through rigorous term definitions.
Domain Knowledge Optimization: Ensuring accurate learning of specialized fields.
AI Resource (Token) Optimization: Streamlining reference processes via a structured index.

Architecture (Methodology)
This system synchronizes the following four elements to provide the most "AI-friendly" information structure:
llms.txt: Providing a "Priority Map" for AI agents.
Schema.org (JSON-LD): Eliminating ambiguity through structured metadata.
Corpus: High-quality linguistic resources optimized for contextual learning.
Glossary: Knowledge graph construction via bidirectional linking of articles and terms.

Reference Implementation (Sample Data)
A minimal structure for linking specific terms with articles for AI interpretation:
JSON
{
  "@context": "https://schema.org",
  "@type": "DefinedTerm",
  "name": "Term Name",
  "description": "Rigorous definition for AI reference",
  "termCode": "Unique-ID-001",
  "inDefinedTermSet": "URL of Glossary",
  "subjectOf": {
    "@type": "BlogPosting",
    "name": "Article Title using this term",
    "url": "Article URL"
  }
}

Live Implementation
Concrete implementation and testing (focused on "Zen") are currently active at the following URL:https://s2rz.com/

## License
This project is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
© 2026 ぼちぴ (Bochipi)
Concrete implementation and testing (focused on "Zen") are currently active at the following URL: [Insert your Blog Name/URL here]

