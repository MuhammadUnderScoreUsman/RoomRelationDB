# Sample project for Room Relational Database

This Sample is just to domonstrate how relational database works in Room.<br/>
There is no other advance framework are used in this playground. Mainly it is for focusing on Room with Basic MVVM approach.<br/>
The use case is pretty simple. In One To One Relation a user can have only one account on one roomail address.<br/>
User roomail and username will be saved in ``user`` and ``user account`` table through relationship. If user try to make another account on same roomail address the dialog will
appear with some important message. Once you are done with account try to signin with username and you will be procceed towards the post fragment.<br/>
All the above process mentioned are happening through *Room Relations*. Saving the user, querying the user, checking for the users.
**Recommendation:** *Try to use room *Database Inspector*(A new feature in android studio to inspect your database). It's
gonna be helpful to see your user input.*<br/>
This project is based on following dependencies:<br/>
> Livedata/Lifecycle<br/> Fragmentktx<br/> Coroutines<br/> Room<br/>
For dialogs: https://github.com/afollestad/material-dialogs
