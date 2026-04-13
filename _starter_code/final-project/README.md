# Final Project

This file is the canonical project handout for Spring 2025 Artificial
Intelligence.

## Summary

Build a private web application that:

1. takes a spoken description of a book,
2. transcribes the request,
3. decides whether the description is specific enough to identify the target,
4. asks a follow-up question when needed,
5. retrieves the text from an authorized corpus or course-provided backend,
6. safely unpacks or normalizes the retrieved file, and
7. reads the result aloud using the student's own synthesized voice or a close
   approved approximation.

## Expected Components

- Browser-based or web-app voice input
- Speech-to-text
- LLM or equivalent reasoning component for disambiguation
- Clarification dialogue
- Retrieval backend
- Safe extraction or normalization pipeline
- Text-to-speech
- Azure-backed deployment or infrastructure

## Evaluation Notes

This project is judged substantially on integration and infrastructure, not
only on model demos. Common failure points are:

- no working fully agentic component
- no working cloned voice end-to-end
- local-only implementations without a real web front end
- incomplete retrieval or file-handling logic

## Sample Test Prompts

Sample prompts include:

- "Wolf Story by William McCleery"
- "The Dolls' House by Rumer Godden"
- "Twig by Elizabeth Orton Jones"
- "The Twenty-One Balloons by William Pene du Bois"
- "Emil is sedated with laced chocolate and robbed on a train..."
- "15th century Poland, alchemy, the Philosopher's Stone..."

These make it clear that the system was supposed to handle both exact titles
and vague natural-language descriptions.

## Deployment

Students will deploy their site to Azure.

## Note on Public Framing

For a public rebuilt course site, the retrieval component is described here in
lawful terms. If you want a historically literal private note for your own
records, keep that in the reconstruction materials rather than the public site.
