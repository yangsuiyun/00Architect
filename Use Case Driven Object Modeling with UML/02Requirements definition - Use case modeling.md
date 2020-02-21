# Tips use case
The purpose for use case is to answer follow questions: What are the users of the system trying to do? What’s the user experience?

We need to take care of the condition when things go wrong, or when the user tries some infrequently used feature of the program.

All the terms that used in domain model should be used directly in your use case text. And find the wrong place by analyzing use cases and correct domain model. 

# Top 10 Use case modeling guidelines
1. Follow the two-paragraph rule

    Each use case should fit comfortabaly into two paragraphs including both the basic course and alternate course. If your use case goes over two paragraphs, it probably needs to be divided into two or more separate use cases.

    The use case writer should not include long lists of functional requirements in his or her scenario text. Instead, the writer should just write about how the users will be using the system and what the system will do in response.

```
    **HOW TO WRITE A USE CASE: THE THREE MAGIC QUESTIONS**
    1. What happens?
    (This gets your “sunny-day scenario” started.)
    2. And then what happens?
    (Keep asking this question until your “sunny-day scenario” is complete.)
    3. What else might happen?
    (Keep asking this one until you’ve identified all the “rainy-day scenarios” you can think of, and described the related behavior.)
```

2. Write your use cases in active voice（主动语态）

    One example is that:

        *Passive voice*
        The capability is provided for users to log in, using a password-protected authorization scheme.

        *Active voice*
        The user enters her username and password, and then clicks the Login button. The system looks up the user profile using the username and checks the password. The system then logs in the user. 
    
    Form above, we can see in passive voice, actor and system functions are hided.

3. Write your use case using an event/response flow

    When write use case, we need to think about the whole process in a response flow, just like the dialog between actor and system. Both side should be described.

4. Use storyboards, GUI prototypes, and screen mock-ups

    Use line drawings or prototype GUI to help show what will be included in a web in the use case. The focus is on event/response behavior, not on the details.

5. Use cases is really a runtime behavior specification

    The sequence diagram shows in great detail how object instances collaborate together at runtime to accomplish the behavior of the use case. Therefore, the use case text will serve as a specification of the runtime behavior that you show on the sequence diagrams.

6. Write use case using a noun-verb-noun sentence structure

    The nouns are the object instances. These usually either come from the domain model or are boundary/GUI objects

    The verbs are the messages between objects. These represent the software functions that need to be built.

7. Reference domain classes by name

