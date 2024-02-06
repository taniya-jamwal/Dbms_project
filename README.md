# Dbms_project
Social Media Database Management system

The provided database appears to be a social media or messaging platform database, containing multiple tables that store various types of data related to users, posts, reactions, comments, messages, threads, and thread participants. Here's a breakdown of the tables and their likely purposes:

1) ACCOUNT: This table likely stores information about users, including their first name, last name, nickname, email, password, and gender. It serves as the primary table for user authentication and identification.

2) FRIEND: This table likely represents the friendships between users. It stores pairs of user emails indicating that one user is friends with another.

3) POST: This table likely stores posts made by users. It includes fields such as PostID, Content, PostDate, PostTime, and UserEmail, indicating the unique identifier, content, timestamp, and author of each post.

4) MEDIA: This table appears to store media files associated with posts. It includes fields such as Type, Caption, PostID, and FileName, indicating the type of media, caption, post ID it belongs to, and the file name.

5) REACTION: This table likely stores predefined reaction types that users can apply to posts, such as 'Smile', 'Sad', 'Like', etc.

6) POST_REACTION: This table represents reactions given by users to posts. It includes fields such as UserEmail, PostID, and ReactionType, indicating which user reacted to which post with which reaction type.

7) POST_COMMENT: This table likely stores comments made by users on posts. It includes fields such as PostID, CommentTime, CommentDate, Content, and UserEmail, indicating the post being commented on, the timestamp of the comment, the content of the comment, and the user who made the comment.

8) MESSAGE_THREAD: This table likely represents message threads or conversations between users. It includes fields such as ThreadID, OwnerEmail, ThDate, and ThTime, indicating the unique identifier, owner of the thread, date, and time of the thread creation.

9) THREAD_PARTICIPANT: This table likely associates users with message threads, indicating which users participate in which threads.

10) MESSAGE: This table likely stores individual messages within message threads. It includes fields such as ThreadID, Sender, MsgDate, MsgTime, and Content, indicating the thread the message belongs to, the sender's email, timestamp of the message, and the message content.

Overall, this database support a social media platform or messaging system, allowing users to create posts, react to posts, comment on posts, participate in message threads, and exchange messages with other users.






