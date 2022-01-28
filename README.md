
# currency_exchange_app
 This app lets you select and convert between different currencies

###### Reason
I am doing this to improve my knowledge in using state management with Provider flutter dependencies

###### Learnt about
- Architecture my App
- Implementing a provider
- Managing app states like a pro
- update the UI based on app state changes

###### Dependencies
- [Provider module](https://pub.dev/packages/provider)


###### Goals
Keep the core business logic separate from the UI, database, network, and third-party packages
![example](https://koenig-media.raywenderlich.com/uploads/2019/11/architecture_1.png)
Ui shouldn't communicate directly with the web
hence a **plug-in** architecture

###### App architecture
Business logic in the middle handles the calculations related to currency exchange.
Local storage, the web API, and the UI along with Flutter and Provider are completely
separate from the business logic and from one another
![e.g.](https://www.raywenderlich.com/6373413-state-management-with-provider)

###### References
- [Principles of clean architecture](https://pusher.com/tutorials/clean-architecture-introduction)
