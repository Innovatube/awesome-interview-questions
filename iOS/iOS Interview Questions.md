# iOS Interview Questions

1. Objective-C
2. Swift
3. Memory
4. Networking
5. Database
6. Multithread
7. UI
8. OOP
9. Design Pattern
10. Testing
11. Frameworks and other languages, tools
12. Algorithm Exercise
13. OOP Design Exercise

## Objective-C

1. Differences between __@property__ definition and instance variable
2. What does __@synthesize__ do?
3. What is __Category__. When to use?
4. Name some _property attributes_?
5. How to define property in a __Category__

## Swift

1. Advantages and disadvantages of __struct__ compare to __class__
2. How to init __enum__ with raw values? What is associated values in __enum__. What is recursive __enum__?
3. How to make _setters_ and _getters_ for a property?
4. Name 2 property observers in Swift? What do __didSet__ and __willSet__ do?
5. When to use _protocol extension_? How to define protocol extension for specific classes?
6. Differences between __guard__ and __if__
7. Differences between __?__ and __!__
8. What is _optional chaining_?
9. Differences between _designated initializers_ and _convenience initializers_?
10. When to use __lazy__ variables and computed variables
11. What is _generics_, when to use? Make a _generics_ _Collection_ with _add()_, _get()_, _remove()_ methods.

## Memory

1. Differences between __strong__ and __weak__?
2. Differences between __weak__ and __unowned__?
3. What is _retain cycle_? Specify some cases that cause _retain cycle_?
4. How to solve the _retain cycle_ problem?
5. When to use __copy__ attribute?

## Networking

1. Name 3 types of __NSURLSession__?
2. Name 3 tasks of __NSURLSession__?
3. How to make __HTTPS__ requests?
4. What is _socket_? How to communicate between clients and servers via _socket_?
5. What is __REST__? Name some __REST__ methods? When to use each methods?
6. Advantages and disadvantages of __JSON__ compared to __XML__ format?
7. Differences between __application/x-www-form-urlencoded__ and __multipart/form-data__?

## Database

1. Specify some ways to persistent data in iOS?
2. What is __NSArchiver__? What is __NSKeyedArchiver__? How to use them?
3. What is __CoreData__? Is it a database?
4. Describe how to setup a __CoreData__ stack
5. How to use __CoreData__ to manage data between multithread?
6. What is __ORM__?
7. How to keep login/user data secured?
8. Advantages and disadvantages of __Realm__ compared to __CoreData__

## Multithread

1. Specify some technics in iOS _concurrency_ programming?
2. Describe how NSOperation and NSOperationQueue work?
3. How to make a custom NSOperation?
4. What will happen when cancel a NSOperation?
5. Name some __GCD__ functions?
6. Differences between __dispatch_sync__ and __dispatch_async__?
7. Name all __dispatch_queue_t__ types? When to use them?
8. __Exercise:__ Assume there are 10 files stored in a server. A iOS app must download them asynchronously. After finishing download, the app has to display an alert that informs whether the task completed successfully or it failed. Specify how to deal with this case?

## UI

1. Differences between __frame__ and __bounds__
2. Specify some methods that a UIViewController must to invoke during the _life-cycle_?
3. What is _Size Classes_? How does it work?
4. How to _autolayout_ subviews in a __UIScrollView__?
5. How to _autolayout_ a __UITableViewCell__ with dynamic height?
6. Differences between __UICollectionView__ and __UITableView__? How does __UICollectionView__ work?
7. Differences between these methods: _setNeedsLayout()_, _layoutIfNeeded()_, _layoutSubviews()_, _updateConstraintsIfNeeded()_, _updateConstraints()_.
8. How about __CALayer__ in relationship to __UIView__? When to use it?
9. How to link scenes between multi _Storyboard_?
10. Exercise: Make a custom _button_ likes them in the game _Threes_.

## OOP

1. Specify 3 attributes of OOP? Make some examples?
2. Differences between __Overloading__ and __Overriding__?
3. What is __tight coupling__ and __loose coupling__? Make some examples?
4. Advantages and disadvantages of using __protocol__/__interface__ over __inheritance__?
5. What is the __Single Responsibility Principle (SRP)__? Make some examples?
6. What is the __Open Closed Principle__? Make some examples?
7. What is the __Liskov Substitution Principle__? Make some examples?
8. What is the __Interface Sergregation Principle__? Make some examples?
9. What is the __Dependency Inversion Principle__? Make some examples?
10. What is __Dependency Injection__? How to do that?
11.

## Design Pattern

1. Differences between __delegate__ and __NSNotification__? When to use them?
2. Describe the __MVC__ pattern? Specify some technics to communicate between __Model__, __View__ and __Controller__. How does iOS's __MVC__ different to the standard one?
3. Disadvantages of iOS's __MVC__?
4. Tell whatever you know about these modern architecture: __MVVM__ / __Clean Architect__ / __MVC-N__ / __VIPER__
5. Name 4 types of _design pattern_? What do they do?
6. What is a __Factory__? What is an __Abstract Factory__?
7. Make some examples using __Decorator__ pattern?
8. What is __Singleton__ and when to use?

## Testing

1. Make an examples of __Unit test__?
2. What is __Mock__? Why to use?
3. What is __Stub__? Why to use?
4. What is __TDD__? __BDD__? Advantages of __TDD__ and __BDD__?
5. Exercise: do __TDD__ to make a _Collection_ data structure with _add(item)_, _remove(item)_ methods.

## Frameworks and other languages, tools

1. Do you know some other languages?
2. What is __Git__? How it works?
3. How to get a __Git__ repository?
4. How to find out __leaks__ in __Instruments__?
5. How to find out methods that make the app run slower than expected using __Instruments__?
6. What is __Refactoring__? What is __code smells__? Give some examples on __code smells__?
7. What is __Continuous Integration (CI)__? Why should use __CI__? Specify some tools to make a __CI__?

## Algorithm Exercise

1. Remove duplicated items in an array
2. Parse HTML from given page

## OOP Design Exercise

1. Design classes to make a social network

```
Social network

  User      => Can Add Friend                                         --- Users
  Page      => Likeable                                               -<> Users

  Photo   => Shareable, Tagable, have URL, Commentable, Likeable      -<> User
  Status  => Shareable, Likeable, Commentable                         -<> User
  Link    => Shareable, Tagable, have URL, Likeable, Commentable      -<> User
  Comment => Likeable, Commentable                                    -<> User
```
