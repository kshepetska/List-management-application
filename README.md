Todo App Implementation Summary:

Loading Todos by userID:
  Implemented user registration using email, saving the received userId.
  Utilized the userId to fetch todos from the API.
  Implemented logic to hide the list and the footer if no todos are present.

Displaying Error Messages:
  Developed a notification system to display appropriate error messages at the bottom upon encountering errors.
  Implemented close button functionality for notifications.
  Ensured automatic dismissal of notifications after 3 seconds or before any subsequent request.

Filtering Todos by Status:
  Implemented filtering of todos by status: All / Active / Completed.
  By default, displayed all todos and highlighted the selected link with the selected class.

Adding a Todo:
  Enabled users to add a todo with the entered title upon form submission.
  Ensured that the text field is focused by default for improved user experience.
  Provided notifications for empty titles and disabled the input until the response is received from the API.
  Implemented a loader to indicate processing and cleared the text field upon successful addition of a todo.

Deleting Todos:
  Allowed users to remove a todo by clicking the TodoDeleteButton.
  Implemented a loader while waiting for the API response and removed the todo from the list upon success.
  Displayed error messages in case of API errors for enhanced error handling.

Removing all Completed Todos:
  Enabled users to remove all completed todos by clicking the Clear completed button.
  Handled API errors and processed successful deletions accordingly.

Toggling a Todo Status:
  Implemented toggling of the completed status upon TodoStatus change.
  Showed a loader overlay while waiting for the API response and updated the status upon success.
  Displayed error messages in case of API errors to ensure robust error handling.

Renaming a Todo:
  Provided users with the ability to edit a todo title upon double click.
  Saved changes on form submission or onBlur events and canceled editing on pressing the Escape key.
  Implemented a loader while waiting for the API response and updated the todo title upon success.
