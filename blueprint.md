# Chinese Learning Website Blueprint

## Project Overview
This project aims to create an interactive web application for learning Chinese, catering to learners of all levels (beginner, intermediate, advanced) categorized by HSK standards. The website will provide essential vocabulary, example sentences, and a user-friendly, clickable interface.

## Implemented Features
- A complete HTML structure provided by the user, including embedded CSS and JavaScript.
- Navigation between "학습" (learning) and "단어 리스트" (word list) pages.
- HSK level sections with toggle functionality for displaying vocabulary.
- Basic vocabulary cards with Chinese characters, Pinyin, and example sentences.
- A search bar for filtering words on the "단어 리스트" page.
- Removal of separate `style.css` and `main.js` files as content is now inlined.

## Current Plan
1. **Refactor the HSK data structure:** Move the hardcoded vocabulary data into a structured JavaScript object within the `<script>` tag of `index.html`.
2. **Dynamically generate HSK sections and word cards:** Use JavaScript to generate the HSK level buttons and the vocabulary word cards for both the "학습" and "단어 리스트" pages from the centralized JavaScript data structure.
3. **Populate comprehensive HSK data:** Add more extensive data for HSK levels 1-6, including essential words, pinyin, definitions, and example sentences.
4. **Implement search and filtering:** Ensure the search function works effectively with the dynamically generated data, allowing users to find specific words across HSK levels.
5. **Add audio pronunciation:** Integrate audio playback functionality for individual words and example sentences.
6. **Implement a progress tracking system:** Develop a system to allow users to track their learning progress (e.g., words learned, HSK levels completed).
7. **Refine UI/UX:** Enhance the visual design, add animations, and ensure responsiveness across different devices.