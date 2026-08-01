
[![project chat](https://img.shields.io/badge/zulip-join_chat-brightgreen.svg?logo=zulip)](https://anitab-org.zulipchat.com/#narrow/stream/222534-mentorship-system)
[![Documentation](https://img.shields.io/badge/documentation-mentorship--android-green.svg)](https://anitab-org.github.io/mentorship-android/)
[![GitHub forks](https://img.shields.io/github/forks/anitab-org/mentorship-android?style=social)](https://github.com/Unity-Billal-mesloub/mentorship-android/network)
[![GitHub stars](https://img.shields.io/github/stars/anitab-org/mentorship-android?style=social)](https://github.com/Unity-Billal-mesloub/mentorship-android/stargazers)

# Mentorship System (Android)

[Mentorship System](https://github.com/Unity-Billal-mesloub/mentorship-backend) is an application that allows women in tech to mentor each other, on career development topics, through 1:1 relations for a certain period.

This is the Android client for the Mentorship System.

## Features
* Once the App is installed, the user can view an onboarding screen that introduces the app and gives the user an idea of how it works.
* A member gets an option to be a Mentor, a Mentee, or Both.
* A member can build/customize the app profile with their username, bio, skills, interests, location, occupation, etc. anytime.
* A member can read and know more about the Mentorship System including the terms and conditions, privacy and policy, and code of conduct.
* A member can directly access the AnitaB-org Github repo, Zulip chat, and website from this App.
* A member can refresh every page.
* A member can view a list of other members and search for a member on the Members Page.
* A member can search for particular members there in the Mentorship System.
* A member can sort other members based on their name either (A-Z) OR (Z-A), registration date, and age.
* A member can filter other members by the label **need mentoring** or **available to mentor**, interest, location, and skills that are given while creating a profile.
* A member can either send mentorship requests to other members as a Mentor or Mentee according to their interests or reject mentorship requests from other members.
* A member can track the number of **Pending Requests**, **Accepted Requests**, **Rejected Requests**, and **Completed Requests** and view **Recent Achievements** on the Home Page.
* A member can view the details of pending, past, and all mentorship requests on the Requests Page.
* A member can create, update, or delete tasks in their current mentorship relationship.
* A member can send feedback about the Mentorship System such as reporting a bug, giving suggestions, or other comments.
* A member can delete their account.
* A member can change their account password anytime.

## Setting up the project

To setup the project locally read these wiki pages and follow the instructions:

 - [Fork, Clone and Remote](https://github.com/Unity-Billal-mesloub/mentorship-android/wiki/Fork%2C-Clone-%26-Remote)
 - [Open project in Android Studio](https://github.com/Unity-Billal-mesloub/mentorship-android/wiki/Open-the-project-in-Android-Studio)

## Contributing

Please read our [Contributing guidelines](https://github.com/Unity-Billal-mesloub/mentorship-android/blob/develop/.github/CONTRIBUTING.md), [Code of Conduct](http://systers.io/code-of-conduct) and [Reporting Guidelines](http://systers.io/reporting-guidelines)

Please follow our [Commit Message Style Guide](https://github.com/Unity-Billal-mesloub/mentorship-android/wiki/Commit-Message-Style-Guide) while sending PRs.

Please follow Kotlin official docs for [Coding Conventions](https://kotlinlang.org/docs/reference/coding-conventions.html) to maintain a consistent code style in the repository.

### Contributors

Thanks goes to these people ([emoji key](https://github.com/Unity-Billal-mesloub/all-contributors#emoji-key)):

This project follows the [all-contributors](https://github.com/Unity-Billal-mesloub/all-contributors) specification.
Contributions of any kind welcome!

## Running the UI tests

To run the existing UI tests follow the steps given below:
* Connect your Android device or open the emulator.
* On the terminal type: `./gradlew clean build connectedAndroidTest --stacktrace`
* If the above command is not working try using the command: `gradlew clean build connectedAndroidTest --stacktrace`
* Wait until all the tests are completed.
* You will get a report generated with a test summary.
* See the complete report `./mentorship-android/app/build/reports/androidTests/connected/index.html`
* The report `./mentorship-android/app/build/reports/androidTests/connected/index.html` will show all the testsuites that have passed as well as failed.
* To get a more detailed explanation about the tests of a particular testsuite visit respective html file of the testsuite.
  For e.g.: `org.anitab.mentorship.LoginActivityTest.html` will contain the results of all the tests run under that particular testsuite.
* You can find the respective html files of the different testsuites under the heading classes in `index.html` report.

## Documentation

To learn more about the project's goals and progress, check out [Mentorship Roadmap](https://github.com/orgs/anitab-org/projects/2).

To learn more about this app you can look at [Unity-Billal-mesloub](https://github.com/Unity-Billal-mesloub).

Our tech stack includes:
- **Language:** [Kotlin](https://kotlinlang.org/)
- **Architecture:** Model View ViewModel (MVVM)
- **Libraries:** [Retrofit](http://square.github.io/retrofit/), ViewModel, LiveData, DataBinding

## Branches

The repository has the following permanent branches:

 * **main** This contains the code which has been released.

 * **develop** This contains the latest code. All the contributing PRs must be sent to this branch. When we want to release the next version of the app, this branch is merged into the `main` branch.

 * **apk** This branch contains the apks for the code in the develop branch. The apks are automatically updated when a commit is pushed to `develop` branch.

## Contact

You can reach our community at [AnitaB.org Open Source Zulip](https://anitab-org.zulipchat.com/).

We use [#mentorship-system](https://anitab-org.zulipchat.com/#narrow/stream/222534-mentorship-system) stream on Zulip to discuss this project and interact with the community. If you're interested in contributing to this project, join us there!

