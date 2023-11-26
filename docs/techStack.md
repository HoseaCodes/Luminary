# Scalable React Native App

## State management

Redux has been in state management for a long time now and gained a lot of attention. Recent developments in Redux ToolKit & RTK Query have boosted its power to great extent. React Query is another awesome solution when your app is more API-centric. MobX, Recoil, and a few others are also making waves and might suit your requirements better.

## Code sharing

The best part about React is its ability to port concepts and ideas from one platform to another. The motto “learn once, write everywhere” is more practical than ever before. If the foundations of React Native apps are laid down properly, it can enable teams to share a huge code base across different platforms including Web & VR. Teams can also leverage git submodules to share components and logic across different repos.

Libraries like expo and react native web are paving the way to porting 100% of the code base across web and mobile platforms. For small- and medium-scale apps this can be an ideal way to save money.

## Theming
It’s rightly said that great design can lead to the best front-end architectures. While applying sophisticated techniques like monorepos & micro-frontends, a design language can serve as a cornerstone for solid architecture.

A good design system sets the tone for your design and development teams. Consistency across components used in different parts of the app allows developers to create better APIs for each component. This makes components more usable and avoids incurring extra technical debt over time.

## Wrapping dependencies
Large-scale React Native apps usually depend on a lot of third-party libraries that help them work faster. As time passes, however, a situation might arise where a third-party library doesn’t serve its purpose as well as it did when we started using it or a better alternative might emerge.

In such cases, switching from one library to another can prove to be a costly decision. As this change can hit our app quite hard if the library in question is used widely across different modules. It is always good to wrap your own API around any such libraries and use them via wrapper across your app. This can be super helpful in the event that you switch third-party libraries.

## Maintaining code & repo quality
As an application grows in size, the execution of tests becomes more costly. Thus, it is best to plan ahead to save time, and make sure there aren’t any fundamental issues (such as typos) in our code.

Static typing & linting can help us avoid basic issues that could eat up tons of our CI resources. Issues like spelling mistakes, linting, static type checking, and package audits can be performed on a developer’s machine as soon as they commit any code to the repository. Git hooks can also assist in maintaining code quality across a large codebase with several contributors.

You can also use git hooks to check commit messages, make commit history more readable, and for generating automated changelogs. 

## Testing
“Move fast & break things” is no longer an acceptable mantra in today’s world. Benchmarks and expectations are getting higher with every passing day. For apps being developed at a high pace, automated testing is the most crucial step for continued success.

An industry expert, who has been working as a software developer for the past 30 years, recently mentioned that testing is still the most difficult part of software development.

Thankfully, we have tools that can make testing a joyful experience. 

For developers looking to start with testing in React Native, we have put together an in-depth guide to implement unit, integration, and e2e tests for React Native apps.

## CI/CD
Today, moving fast is not just an advantage, it’s crucial for the survival of businesses. CI/CD gives you the ability to ship your apps with confidence and peace of mind. If done right, CI/CD can significantly increase the pace of development & distribution .

As discussed earlier, a top demotivating factor for many developers is sitting idle and waiting for processes to complete. It’s in the best interest of developers and businesses to automate tedious tasks so that developers can do innovative and productive work. Besides allowing developers to deliver apps and updates faster, CI/CD takes away the cost of managing & maintaining different environments on development machines. As mentioned in the McKinsey survey:

“Organizations with strong tools for continuous integration and delivery—are 65 percent more innovative”

If you want to leverage CI/CD for React Native apps, we’ve put together amazing guides for you to fully implement best in class CI/CD for React Native apps. 

## Performance Tracking
Like we mentioned earlier, moving fast is a necessity these days. It’s not always easy, and faster iterations can result in problems even when a solid test suite and CI/CD are in place. For tracking issues and monitoring the performance of your app as it is being used, you can leverage Firebase SDK for its performance monitoring & crashlytics. 

Key takeaways:

Firebase performance monitoring/crashlytics
LogRocket crash monitoring


## OTA updates
One of the top challenges faced by app developers is getting users to upgrade to new versions of apps. Unlike web apps, businesses have less control over what version of their app users are using. Both Android & iOS now have libraries and methods available to notify users whenever a newer version of the app is available. React Native In-App Update is an open-source library that wraps in-app updates for both android & iOS.

This might be useful for many apps but still isn’t enough by itself. Because most of the business & UI logic resides within the JavaScript in React Native apps, it is possible to update apps over the air. Microsoft CodePush enables us to update the JS bundle of React Native apps without bothering our users.


## Developer experience
Developers are the core of every business that relies on technology. Delivering the best user experience is only possible when the people developing it have the best experience themselves. Developers equipped with the right development tools and processes are more committed and productive.

Automating repetitive tasks such as writing skeletal code, utility libraries, unit test cases, and performing testing, frees up a considerable amount of productive time for developers. Taking assistance from AI can also bolster the development speed of teams.

## Resoruces

- https://semaphoreci.com/blog/react-native-architecture
- https://www.linkedin.com/pulse/why-choose-react-native-enterprise-app-development-2023-/
- https://github.com/infinitered/ignite
- https://github.com/obytes/react-native-template-obytes
- https://mobidev.biz/blog/react-native-app-development-guide
- https://climbtheladder.com/10-react-native-architecture-best-practices/
- https://www.thirdrocktechkno.com/blog/react-native-best-practices/
- https://www.emizentech.com/blog/native-mobile-app-architecture.html
- https://www.techaheadcorp.com/blog/enterprise-app-architecture-long-term-growth/
- https://appinventiv.com/blog/cost-of-cash-app-development/
- https://www.freshbooks.com/hub/accounting/how-cash-app-works
- https://shakuro.com/blog/how-to-make-a-payment-service-like-cash-app
- https://www.retrocube.com/blog/how-much-does-it-cost-to-create-an-app-like-cashapp/
- https://www.pewresearch.org/short-reads/2022/09/08/payment-apps-like-venmo-and-cash-app-bring-convenience-and-security-concerns-to-some-users/
- https://code-care.com/blog/technology-stack-for-app-development/
- https://www.linkedin.com/pulse/whats-best-tech-stack-mobile-app-development-2023-strivemindz/
- https://www.indiehackers.com/post/7-reasons-to-choose-react-native-for-enterprise-app-development-57fd1091ce
- https://www.uptech.team/blog/mobile-app-technology-stack
- https://www.netguru.com/blog/technology-stack-mobile-app-development
- https://www.prismetric.com/mobile-app-development-tech-stacks/
- https://appinventiv.com/blog/cross-platform-app-frameworks/
- https://www.spaceotechnologies.com/blog/cross-platform-app-frameworks/
- https://www.techaheadcorp.com/blog/best-cross-platform-app-development-frameworks/
- https://www.linkedin.com/pulse/how-develop-app-like-cash-step-by-step-guide-prachi-singh/
- https://www.appypie.com/how-to-make-an-app-like-cash-app
- https://topflightapps.com/ideas/how-to-build-p2p-payment-money-transfer-app/
- https://chudovo.com/how-to-make-a-peer-to-peer-payment-app/
- https://productmint.com/how-does-cash-app-make-money/
- https://www.peerbits.com/blog/how-to-build-a-p2p-payment-app-like-venmo-and-square-cash.html
- https://www.nichepursuits.com/how-to-make-money-on-the-cash-app/
- https://www.stilt.com/blog/2022/09/how-to-make-money-on-cash-app/
- https://www.techaheadcorp.com/blog/how-to-develop-a-p2p-payment-app-like-the-cash-app/
- https://www.brainvire.com/blog/cash-app/
- 
