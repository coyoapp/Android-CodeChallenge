# COYO- Android Code Challenge

Welcome to COYO's Android dev challenge!

### Position: **Android Developer**
We're glad that you're considering a position here at COYO. Thank you for having time to invest in this code challenge


### Deliverable : **COYO Demo Project**
We need you to submit an Android Demo Project to be evaluated by our software engineers.

The COYO demo project:
- The app architecture, project, code organization, file structure, and comments will be evaluated.
- Send your code challenge in a .zip file or url of your git repo by e-mail to your respective recruiter.
- We need you to create an app that allows our users from a test social network to see posts and comments for relevant posts

The app consists of two screens:
1. Posts list Screen
2. The post detail Screen

We won't provide any UI specifications, this is totally up to you. Free the designer soul inside you. ;)

Posts List Screen
- A post has a title.
- When a post is tapped, the user should be redirected to the detail screen.
- The user should be able to refresh the content.

**Note**: Our backend server is weak, 10 items per response should be enough to not melt it down.

Post Detail Screen
- For the post detail, we expect to see its author, description, number of comments, and the comments.
- Press back should lead to posts list screen.


API
Here is the [API docs](http://jsonplaceholder.typicode.com/), you should use the following endpoints:

- `/posts`
- `/comments`
- `/users`

Hint: We expect you to use the **GET** method only.

**Requirements:**
- Android minimum version: 6
- Language: Kotlin
- Compileable and runnable code
- Have some sort of persistence/cache mechanism.
- Provide a COMMENTS.md file mentioned in Notes.

**Nice to have:**
- [Coroutines](https://developer.android.com/kotlin/coroutines)
- [Koin](https://github.com/InsertKoinIO/koin) or [Hilt](https://dagger.dev/hilt/)
- [Compose](https://developer.android.com/jetpack/getting-started)


Notes: 
- This assessment must be delivered within 2 days.
- We like code that is simple, but simple is different from easy.
- Keep in mind the SOLID principles when doing the project.
- Testing is very important for us. Even if you don't write a single test (for instance, because of time constraints), your app should be easy to test.
- Error scenarios should be taken into consideration and it should be easy to add them, even if you don't explicitly handle them.
- MVVM architectures are preferred, but not mandatory.
- Although UI and UX are important, we are more concerned in this demo with your thought process and with how you architect your application. Your demo should take into consideration features that might be added in the future.
- You can use any third-party libraries you wish, but be prepared to justify why you did so (don't forget that we want to evaluate YOUR skills). If so, please use a dependency Injection.
- Keep in mind you're developing an app to be used over cellular data. Would be nice if you provide a way to save the user's data plan.
- Be consistent in your code with respect to code styles, design patterns etc.
- You must provide a COMMENTS.md file at the root of your repository, explaining:
- Main architecture decisions you've made and a quick explanation of why.
- List of third-party libraries if any with WHYS
- What could be improved if you had more time.
- Mention anything that was asked but not delivered and why, and any additional comments.


**Final Words: Don't panic, Just be yourself.**

