
### View (Handles UI and displays data)
- RegisterActivity.kt

### Presenter (Handles business logic and communicates with View)
- RegisterPresenter.kt

### Model (Handles data operations)
- UserRepository.kt

### Data Flow
User inputs registration info → View → Presenter → Model → Presenter → View

### Steps
1. Create UI layout
2. Create Presenter class
3. Implement validation logic in Presenter
4. Connect View and Presenter
5. Update UI based on results
