# TODO List for React Fetch CRUD Lab

- [x] Move state to App.js: Add useState for questions array and useEffect to fetch on mount. Pass questions and setQuestions as props to QuestionList and QuestionForm.
- [x] Implement GET in App.js: Use fetch in useEffect to load questions from API and set state.
- [x] Update QuestionList.js: Accept questions prop, map over them to render QuestionItem components.
- [x] Update QuestionItem.js: Accept question and onDelete/onUpdate props. Add onClick handler for delete button to call onDelete with question.id. Add onChange handler for select to call onUpdate with question.id and new correctIndex.
- [x] Implement DELETE in App.js: Add deleteQuestion function that sends DELETE request and filters out the deleted question from state.
- [x] Implement PATCH in App.js: Add updateQuestion function that sends PATCH request with new correctIndex and updates state.
- [x] Update QuestionForm.js: Accept onAddQuestion prop. Modify handleSubmit to format formData (collect answers into array), POST to API, and call onAddQuestion with new question to update state.
- [x] Implement POST in App.js: Add addQuestion function that updates state with new question.
