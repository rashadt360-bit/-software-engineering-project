# Registration Page Plan - MVP

## Goal
Implement the Registration Page using MVP architecture for the Instagram clone app.

## Files to Create
- registration_page.dart
- registration_presenter.dart
- auth_repository.dart
- user_model.dart

## Steps
1. Create the registration UI with input fields.
2. Connect the Register button to the Presenter.
3. The Presenter checks validation rules.
4. If inputs are correct, the Presenter calls the Repository.
5. The Repository handles registration data.
6. The Presenter receives the result.
7. The Presenter updates the View with success or error messages.

## Benefits
- Good separation between UI and logic
- Easier to understand for smaller projects
- Presenter directly controls UI updates
