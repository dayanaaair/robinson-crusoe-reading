# Robinson Crusoe · Reading Journal

Static illustrated reading app. Serve the repository root via HTTP, or publish the main branch root with GitHub Pages.

- Source text: user-supplied книга.docx, 31 chapters; reader exposes all chapters 1–31. Paragraph text preserved exactly, including original nonbreaking spaces, wording and typographical errors.
- Questions: 10 per chapter 1–31, with Russian prompts and model answers for self-comparison.
- Vocabulary: 310 unique multiword chunks (10 per chapter), chapter filters for all 31 chapters. Some chunks use normalized or reusable teaching forms; flagged in the UI. Examples are newly written.
- Images: 31 custom illustrations made with the built-in ImageGen tool; local WebP assets in assets.
- Persistence: browser localStorage only; JSON export/import transfers progress between devices. No cross-device or teacher/student synchronization.

Validation: exact paragraph comparison with the supplied DOCX; dataset and asset checks; node syntax check; browser checks for reading, saving after reload, flashcards, chapter filters, choice feedback, typed correct/incorrect answers, and 390px layouts.
