# q2a-mention-notifier
This is originated from http://www.question2answer.org/qa/6084/notification-plugin-available
But it has a limitation that it works only with external user, and the version from arjunsuresh fixed that problem.

However, it still has following issues:
  1) using mysql_row_num, it shall be replaced with
  $num_rows = $result->num_rows;
  2) doesn't support digits (0-9) in the user name (handle)
  detect file shall be updated.
  
I'll push new versions to the source files later.
